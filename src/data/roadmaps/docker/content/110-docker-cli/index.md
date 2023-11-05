# Docker CLI

The Docker CLI (Command Line Interface) is a powerful tool that allows you to interact with and manage Docker containers, images, volumes, and networks. It provides a wide range of commands for users to create, run, and manage Docker containers and other Docker resources in their development and production workflows.

In this topic, we'll dive into some key aspects of Docker CLI, covering the following:

## 1. Installation

To get started with Docker CLI, you need to have Docker installed on your machine. You can follow the official installation guide for your respective operating system from the [Docker documentation](https://docs.docker.com/get-docker/).

## 2. Basic Commands

Here are some essential Docker CLI commands to familiarize yourself with:

- `docker run`: Create and start a container from a Docker image
- `docker container`: List running containers
- `docker image`: List all available images on your system
- `docker pull`: Pull an image from Docker Hub or another registry
- `docker push`: Push an image to Docker Hub or another registry
- `docker build`: Build an image from a Dockerfile
- `docker exec`: Run a command in a running container
- `docker logs`: Show logs of a container

## 3. Docker Run Options

`docker run` is one of the most important commands in the Docker CLI. You can customize the behavior of a container using various options, such as:

- `-d, --detach`: Run the container in the background
- `-e, --env`: Set environment variables for the container
- `-v, --volume`: Bind-mount a volume
- `-p, --publish`: Publish the container's port to the host
- `--name`: Assign a name to the container
- `--restart`: Specify the container's restart policy
- `--rm`: Automatically remove the container when it exits

## 4. Dockerfile

A Dockerfile is a script containing instructions to build a Docker image. You can use the Docker CLI to build, update, and manage Docker images using a Dockerfile.

Here is a simple example of a Dockerfile:

```dockerfile
# Set the base image to use
FROM alpine:3.7

# Update the system and install packages
RUN apk update && apk add curl

# Set the working directory
WORKDIR /app

# Copy the application file
COPY app.sh .

# Set the entry point
ENTRYPOINT ["./app.sh"]
```

To build the image, use the command:

```bash
docker build -t my-image .
```

## 5. Docker Compose

Docker Compose is a CLI tool for defining and managing multi-container Docker applications using YAML files. It works together with the Docker CLI, offering a consistent way to manage multiple containers and their dependencies.

Install Docker Compose using the official [installation guide](https://docs.docker.com/compose/install/), and then you can create a `docker-compose.yml` file to define and run multi-container applications:

```yaml
version: '3'
services:
  web:
    image: webapp-image
    ports:
      - "80:80"
  database:
    image: mysql
    environment:
      - MYSQL_ROOT_PASSWORD=my-secret-pw
```

Run the application using the command:

```bash
docker-compose up
```

In conclusion, the Docker CLI is a robust and versatile tool for managing all aspects of Docker containers and resources. Once familiar with its commands and capabilities, you'll be well-equipped to develop, maintain and deploy applications using Docker with ease.
