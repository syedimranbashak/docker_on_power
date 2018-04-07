# docker_on_power
Installing docker-ce on IBM Power Server

A simple script that automates the installation and configuration of Docker for ppc64le. That's all!

To execute it, ensure you are logged as root user, then just go inside the docker_on_power directory and  execute ./install_docker.sh.

You can allow an user to run Docker without sudo by executing the following commands:

# Add Docker group
groupadd docker

# Add current user as member of the Docker group
usermod -aG docker $USER

Reboot when the installation is completed.
