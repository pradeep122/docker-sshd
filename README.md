## SSH server inside docker

This image enables connecting via ssh to a fbase ubuntu image

## building docker

```
    sudo docker build -t deepster/docker-sshd:latest .
    sudo docker push deepster/docker-sshd:latest 
```


## running th ssh docker container

```
    sudo docker run -d deepster/docker-sshd:latest
```
