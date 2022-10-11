#Demonstrate minimum 15 basic docker command with explanation.
### 1) Images 
#### Lists all the docker images pulled on the system with image details such as TAG/IMAGE ID/SIZE etc.
```bash
docker images
```

### 2) Run  
#### Runs the docker image mentioned in the command. This command will create a docker container in which the Apache HTTP server will run.
```bash
docker run -d -p 5000:5000 img
```

### 3) Build 
#### This command is used to build an image from a specified docker file
```bash
docker build -t docker/getting-started .
```

### 4) Stop 
#### Stop a container with container id mentioned in the command.
```bash
docker stop b31f0973f8ec
```

### 5)	Pull 
#### This command is used to pull images from the docker repository(hub.docker.com)
```bash
docker pull docker/getting-started
```

### 6)	Remove container (rm) 
#### Remove the docker container with container id mentioned in the command.
```bash
docker rm 6dff21556812
``` 

### 7)	Login 
#### Login into docker hub. You will be asked your docker hub credentials to log in.
```bash
docker login
```

### 8)	Kill 
#### Stop the docker container immediately. Docker stop command stops the container gracefully, that’s the difference between a kill and stop commands.
```bash
docker kill 6dff21556812
``` 

### 9)	Exec 
#### Access the docker container and run commands inside the container. I am accessing the mongo server container in this example.
```bash
docker exec -it b31f0973f8ec bash
``` 

### 10)	Ps  
#### List all the docker containers running with container details.
```bash
docker ps
``` 

### 11)	Restart 
#### Restart the docker container with container id mentioned in the command.
```bash
docker restart b31f0973f8ec
```

### 12)	Remove image 
#### Remove the docker image with the docker image id mentioned in the command.
```bash
docker rmi 5083dfb3ce39
```

### 13)	Start 
#### This command in docker starts the docker container with container id mentioned in the command.
```bash
docker start b31f0973f8ec
```

### 14)	Docker Network 
#### The following command in docker lists the details of all the network in the cluster.
```bash
docker network ls
```

### 15)	Search 
#### Search for a docker image on dockerhub with the name mentioned in the command.
```bash
docker search mongo
```

