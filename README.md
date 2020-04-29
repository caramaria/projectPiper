This github documents the setup of the CX-Server on Linux Ubuntu 16.4 LTS

#1. Install docker

Follow the steps mentioned in the Docker Setup Guide:
[https://docs.docker.com/install/linux/docker-ce/ubuntu/](https://docs.docker.com/install/linux/docker-ce/ubuntu/)

#2. Install CX/ Server
Please use the Project Piper documentation available here:

If zou receive the following error when executing the docker cmd, the following steps might help:

docker: Got permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Pos
t http://%2Fvar%2Frun%2Fdocker.sock/v1.40/containers/create: dial unix /var/run/docker.sock: connect: permission deni
ed.





5:19.03.8~3-0~ubuntu-xenial

sudo apt-get install docker-ce=5:19.03.8~3-0~ubuntu-xenial docker-ce-cli=5:19.03.8~3-0~ubuntu-xenial containerd.io


