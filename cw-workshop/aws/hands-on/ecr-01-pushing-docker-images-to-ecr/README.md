# Hands-on ECR-01 : Pushing Docker Images to ECR Manually

Purpose of the this hands-on training is to give basic understanding of how to use AWS Elastic Container Registry (ECR) and how to manage docker images using ECR.

## Learning Outcomes

At the end of the this hands-on training, students will be able to;

- prepare a Docker Machine with Cloudformation.

- setup an EC2 instance with IAM role and AWS CLI for managing ECR.

- create and configure AWS ECR from the AWS Management Console.

- create and configure AWS ECR from the AWS CLI.

- demonstrate how to build a docker image with Dockerfile.

- configure AWS CLI to work with ECR.

- use Docker commands effectively to tag, push, and pull images to/from ECR.

- delete images and repositories on ECR from the AWS Management Console.

- delete images and repositories on ECR from the AWS CLI.

## Outline

- Part 1 - Launching a Docker Machine Instance Configured for ECR Management

- Part 2 - Creating Repositories on AWS ECR

- Part 3 - Configuring AWS CLI to Work with AWS ECR

- Part 4 - Managing Docker Images using AWS ECR as Repository

## Part 1 - Launching a Docker Machine Instance Configured for ECR Management

- Launch a Compose enabled Docker machine on Amazon Linux 2 AMI with security group allowing HTTP and SSH connections using the [Cloudformation Template for Installing Docker Machine Configured to Work with ECR](./docker-machine-with-ecr-cfn-template.yml).

- Explain the resources in the cloudformation template and connect to your instance with SSH. (***This Cloudformation Template creates a Compose enabled Docker machine on EC2 Instance. Docker Machine is configured to work with AWS ECR using IAM role, and also upgraded to AWS CLI Version 2 to enable ECR commands.***)

```bash
ssh -i .ssh/call-training.pem ec2-user@ec2-3-133-106-98.us-east-2.compute.amazonaws.com
```

## Part 2 - Creating Repositories on AWS ECR

- Go to the `Amazon Elastic Container Registry` service and explain what it is.

- Introduce menus on the left side, `Amazon ECS`, `Amazon EKS`, `Amazon ECR`.

- Click on `Repositories` on ECR section, and explain the UI.

- Click on `Create Repository` and explain the default `registry` for user account. (`aws_account_id`.dkr.ecr.`region`.amazonaws.com)

- Explain repository name convention. (*Repository names can support namespaces, which you can use to group similar repositories. For example if there are several teams using the same registry, `Team A` could use the `team-a` namespace while `Team B` uses the `team-b` namespace. Each team could have their own image called `web-app`, but because they are each prefaced with the team namespace, the two images can be used simultaneously without interference. Team A's image would be called `team-a/web-app`, while Team B's image would be called `team-b/web-app`.*)

- Enter a repository name ex. `callahan-repo/todo-app` (***In this hands-on, we will be working with a simple `todo list manager` that is running in `Node.js`. If you're not familiar with Node.js, don't worry! No real JavaScript experience is needed!***)

- Explain `tag immutability` and leave it as default.

- Explain `scan on push` and leave it as default.

- Create the repository and explain the complete URI.(*Combination of registry and repo name*)

```text
046402772087.dkr.ecr.us-east-1.amazonaws.com/callahan-repo/to-do-app
```

## Part 3 - Configuring AWS CLI to Work with AWS ECR

- Check your AWS CLI version `aws --version` command.(*AWS CLI is already installed on Amazon Linux 2 AMIs, but Amazon ECR functionality is available in the AWS CLI starting with version 1.9.15*).

- Install the latest AWS CLI Version 2 if the current version is older than `1.9.15`, to use the AWS CLI with Amazon ECR. (*For this hands-on, AWS CLI Version 2 is installed by Cloudformation template*)

```bash
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
./aws/install
```

- Authenticate the Docker CLI to your default `registry` with ***"aws ecr get-login-password --region `region` | docker login --username AWS --password-stdin `aws_account_id`.dkr.ecr.`region`.amazonaws.com"***
(*Since we have launhced EC2 instance with IAM role and give permission to work with ECR within the Cloudformation template, we **do not need to configure AWS CLI** with `aws configure` command*)

```bash
aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 046402772087.dkr.ecr.us-east-1.amazonaws.com
```

## Part 4 - Managing Docker Images using AWS ECR as Repository

- Download the sample project `to-do-app-nodejs.tar.gz` file from the GitHub Repo on your instance. In this hands-on, we will be working with a simple `todo list manager` that is running in `Node.js`.
  
```bash
TOKEN="XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
FOLDER="https://$TOKEN@raw.githubusercontent.com/clarusway/cw-workshop/aws/ho-ecr-01/aws/hands-on/ecr-01-pushing-docker-images-to-ecr/"
curl -s --create-dirs -o "/home/ec2-user/to-do-app-nodejs.tar.gz" -L "$FOLDER"to-do-app-nodejs.tar.gz
```

- Extract the `to-do-app-nodejs.tar.gz` file and change into the app directory.

```bash
tar -xzvf to-do-app-nodejs.tar.gz
cd /home/ec2-user/to-do-app-nodejs
```

- Download the Dockerfile within app folder.

```bash
curl -O -L "$FOLDER"Dockerfile
```

- Or create a Dockerfile with following content.

```dockerfile
FROM node:12-alpine
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "/app/src/index.js"]
```

- Build the Docker container image using the `docker build` command.

```bash
docker build -t todo-app:latest .
```

- Show the Docker image is created successfully.

```bash
docker image ls
```

- Run `todo app` from the local image.

```bash
docker run --name todo -d -p 80:3000 todo-app
```

- List running container.

```bash
docker ps
# or
docker container ls
```

- Check if the To-Do App is running by entering `http://<ec2-host-name>` in a browser.

- Stop and remove container

```bash
docker stop todo
docker rm todo
```

- Tag the image to push it to ECR repository.

```bash
docker tag todo-app:latest 046402772087.dkr.ecr.us-east-1.amazonaws.com/callahan-repo/todo-app:latest
```

- Push the image to your ECR repository and show the pushed image on AWS ECR Console.

```bash
docker push 046402772087.dkr.ecr.us-east-1.amazonaws.com/callahan-repo/todo-app:latest
```

- Create a ECR repository named `clarusway-repo/todo-app` from AWS CLI and show it is created on AWS ECR Console.

```bash
aws ecr create-repository \
    --repository-name clarusway-repo/to-do-app \
    --image-scanning-configuration scanOnPush=false \
    --image-tag-mutability IMMUTABLE \
    --region us-east-1
```

- Tag and push the image to your `clarusway-repo/todo-app` repository and show the pushed image on AWS ECR Console.

```bash
docker tag todo-app:latest 046402772087.dkr.ecr.us-east-1.amazonaws.com/clarusway-repo/todo-app:latest
docker push 046402772087.dkr.ecr.us-east-1.amazonaws.com/clarusway-repo/todo-app:latest
```

- Delete the all local images of `todo-app`.

```bash
docker image rm --force <image_id>
```

- Show that there is no image locally

```bash
docker image ls
```

- Pull the image from your `clarusway-repo/todo-app` repository  to the local.

```bash
docker pull 046402772087.dkr.ecr.us-east-1.amazonaws.com/clarusway-repo/todo-app:latest
docker run -dp 80:3000 046402772087.dkr.ecr.us-east-1.amazonaws.com/clarusway-repo/todo-app:latest
```

- Or directly run the `todo-app` from the ECR repo.

```bash
docker run -dp 80:3000 046402772087.dkr.ecr.us-east-1.amazonaws.com/clarusway-repo/todo-app:latest
```

- Check if the To-Do App is running by entering `http://<ec2-host-name>` in a browser.

- Delete Docker image on your `clarusway-repo/todo-app` repository from AWS CLI.

```bash
aws ecr batch-delete-image \
      --repository-name clarusway-repo/todo-app \
      --image-ids imageTag=latest
```

- Delete the ECR repository  `clarusway-repo/todo-app` from AWS CLI.

```bash
aws ecr delete-repository \
      --repository-name clarusway-repo/todo-app \
      --force
```

- Delete the image and repository of `callahan-repo/todo-app` from AWS ECR Console.
