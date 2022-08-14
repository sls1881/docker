# docker
Learning docker

# What is Docker?
A platform for consistently building, running and shipping applications.

Docker allows you to build the same application on another/different machine.

We can package our application and deliver it to any machine that serves docker. 

Keeps the development machine clean.

## Architecture
Client/Server 
Client -> REST API -> Server 
Server = Docker Engine takes care of the docker containers

**Docker is a process
**Shares host kernel OS
**Mac uses Linux VM since it doesn't have a kernel

## Dockerizing 
Packages up your application into an image
- A cut-down OS
- A runtime environment like node
- Application files
- Third-party libraries
- Environment variables

## Process
1. Package application into an image
2. Tell docker to start a container with the image
3. The container has it's own file system
4. Run process locally inside a container
5. Push image DockerHub (like GitHub) to push to other machines.
6. Run it virtually anywhere
## Why wouldn't the application build the same on another machine?
- One or more files are missing
- Software version mismatch
- Different config settup like environment variables

# What is a container?
An isolated environment for running an application. 

- More lightweight than a VM
- Use host OS
- Need less hardware and memory

# What is a Virtual Machine (VM)
An abstraction of a machine or physical hardware. 

- Running windows and linux
- Each VM needs it full OS

## How do we manage a VM?
Hypervisors: Software we use to create and manage VMs.
- VirtualBox
- VMware

## What is the benefit of a VM?
We can run an application in an isolated environment.





