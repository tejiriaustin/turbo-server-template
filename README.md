# turbo-server-template
A Template for building a server using clean architecture, integrating payment processors and graceful shutdown enabled


### Built With
Golang(https://go.dev/)

### Prerequisites
#### Using Docker
Install docker by running the script
``` 
sudo apt-get remove docker docker-engine docker.io containerd runc
```

Then running the command

```
 sudo apt-get install docker-ce=<VERSION_STRING> docker-ce-cli=<VERSION_STRING> containerd.io
```

Or just visit the official websites

https://docs.docker.com/engine/install/


### Installation
1. clone the repository`
```
git clone git@github.com:inawoo/service-blog
```

2. Then run the command 
```
make run
```
OR
```
docker run
```
