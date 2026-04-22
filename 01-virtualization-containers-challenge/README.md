# Challenge 1 - Virtualization and Containers

## Objective
Create an Ubuntu VM with Vagrant and install Docker manually.

## Tools
- VirtualBox
- Vagrant
- Ubuntu 20.04
- Docker

## Steps
1. Installed VirtualBox and Vagrant
2. Created Ubuntu VM with Vagrant
3. Connected with `vagrant ssh`
4. Installed Docker manually
5. Validated with `docker run hello-world`

## Bonus
- Packaged the VM as a Vagrant box
- Published it
- Reused it as the new base box

## Validation
- `uname -a`
- `lsb_release -a`
- `docker --version`
- `docker run hello-world`