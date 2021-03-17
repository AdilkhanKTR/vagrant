# Install Vagrant & Docker

# Docker instalation steps:

```
1. sudo yum install -y yum-utils

2. sudo yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo

3. sudo yum install docker-ce docker-ce-cli containerd.io

4. sudo systemctl start docker

5. sudo docker run hello-world
```
