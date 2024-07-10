# rocketseat-journey
A travel planner

Features:
- save links
-

## Docker
Reasons to use Docker on this project:


Set up on Debian:

_Installing Docker:_
``` bash
    sudo apt update
```
``` bash
    sudo apt install qemu-kvm libvirt-daemon-system libvirt-clients bridge-utils virtinst libvirt-daemon
```

_Check if KVM is installed & if your CPU supports KVM:_
``` bash
    kvm-ok
```

My CPU does not support KVM extentions :( Link to instructions: https://reintech.io/blog/installing-using-kvm-virtualization-debian-12


About Docker:
> Docker Desktop is a one-click-install application for your Mac, Linux, or Windows environment that lets you build, share, and run containerized applications and microservices.

> It provides a straightforward GUI (Graphical User Interface) that lets you manage your containers, applications, and images directly from your machine.

> Docker Desktop reduces the time spent on complex setups so you can focus on writing code. It takes care of port mappings, file system concerns, and other default settings, and is regularly updated with bug fixes and security updates.


### What is a container?
> A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.
> A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

> Container images become containers at runtime and in the case of Docker containers – images become containers when they run on Docker Engine. Available for both Linux and Windows-based applications, containerized software will always run the same, regardless of the infrastructure. Containers isolate software from its environment and ensure that it works uniformly despite differences for instance between development and staging.


### Open Container Initiative
> The Open Container Initiative is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

- https://github.com/opencontainers/runc


### Docker Compose
> Docker Compose is a tool for defining and running multi-container applications.

> Compose simplifies the control of your entire application stack, making it easy to manage services, networks, and volumes in a single, comprehensible YAML configuration file. Then, with a single command, you create and start all the services from your configuration file.


## Golang

_Set up on Debian:_




---

## Refs

Docker
- https://docs.docker.com/desktop/
Docker Compose
- https://github.com/docker/compose
- https://github.com/compose-spec/compose-spec/blob/master/spec.md
- https://docs.docker.com/compose/
Containers
- https://www.docker.com/resources/what-container/
- https://en.wikipedia.org/wiki/Containerization_(computing)
- https://opencontainers.org/
- https://github.com/opencontainers/runc

---
