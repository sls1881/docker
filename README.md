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





