# Demonstrate minimum 15 basic docker command with explanation.
### 1) Images 
#### Lists all the docker images pulled on the system with image details such as TAG/IMAGE ID/SIZE etc.
```bash
docker images
```
![t1](https://user-images.githubusercontent.com/97040413/195176747-d87aec72-5fa4-4a95-97a3-4bcf2881c907.png)

### 2) Run  
#### Runs the docker image mentioned in the command. This command will create a docker container in which the Apache HTTP server will run.
```bash
docker run -d -p 5000:5000 img
```
![t2](https://user-images.githubusercontent.com/97040413/195178423-e61e5be8-90e1-4da6-a505-78f6989259ae.png)

### 3) Build 
#### This command is used to build an image from a specified docker file
```bash
docker build -t docker/getting-started .
```
![t3](https://user-images.githubusercontent.com/97040413/195178455-f4915c60-59af-41ab-8a2d-615476350f94.png)

### 4) Stop 
#### Stop a container with container id mentioned in the command.
```bash
docker stop b31f0973f8ec
```
![t4](https://user-images.githubusercontent.com/97040413/195178487-38a156ee-358d-4ace-aa19-83cf8ffaf33a.png)

### 5)	Pull 
#### This command is used to pull images from the docker repository(hub.docker.com)
```bash
docker pull docker/getting-started
```
![t5](https://user-images.githubusercontent.com/97040413/195178518-8238b8f1-783b-4de3-8e72-ef56e1015922.png)

### 6)	Remove container (rm) 
#### Remove the docker container with container id mentioned in the command.
```bash
docker rm 6dff21556812
``` 
![t6](https://user-images.githubusercontent.com/97040413/195178565-0a0db3fe-da64-42f6-8b07-1ce35c6e2534.png)

### 7)	Login 
#### Login into docker hub. You will be asked your docker hub credentials to log in.
```bash
docker login
```
![t7](https://user-images.githubusercontent.com/97040413/195178592-ac824697-5fac-4584-8e9a-125f5e489959.png)

### 8)	Kill 
#### Stop the docker container immediately. Docker stop command stops the container gracefully, that’s the difference between a kill and stop commands.
```bash
docker kill 6dff21556812
``` 
![t8](https://user-images.githubusercontent.com/97040413/195178610-efd95a1a-b769-4f26-a67e-58e46549471f.png)

### 9)	Exec 
#### Access the docker container and run commands inside the container. I am accessing the mongo server container in this example.
```bash
docker exec -it b31f0973f8ec bash
```
![t9](https://user-images.githubusercontent.com/97040413/195178647-bf4e7d47-689b-4ae4-97ab-cdedd0aa9342.png)


### 10)	Ps  
#### List all the docker containers running with container details.
```bash
docker ps
``` 
![t10](https://user-images.githubusercontent.com/97040413/195178688-90ab9447-eabd-4c9c-aa26-855cd5a93948.png)

### 11)	Restart 
#### Restart the docker container with container id mentioned in the command.
```bash
docker restart b31f0973f8ec
```
![t11](https://user-images.githubusercontent.com/97040413/195178709-d6285249-ddf6-41c0-9a84-ff64d5f75ebb.png)

### 12)	Remove image 
#### Remove the docker image with the docker image id mentioned in the command.
```bash
docker rmi 5083dfb3ce39
```
![t12](https://user-images.githubusercontent.com/97040413/195178732-79b48ede-79f2-41be-ab61-b41f66b48f7c.png)

### 13)	Start 
#### This command in docker starts the docker container with container id mentioned in the command.
```bash
docker start b31f0973f8ec
```
![t13](https://user-images.githubusercontent.com/97040413/195178749-e3dfb2fe-9d84-410e-b5bc-b7fde0d0bf76.png)

### 14)	Docker Network 
#### The following command in docker lists the details of all the network in the cluster.
```bash
docker network ls
```
![t14](https://user-images.githubusercontent.com/97040413/195178765-932751b4-3c7c-40e0-8bdc-42e30432cd2a.png)

### 15)	Search 
#### Search for a docker image on dockerhub with the name mentioned in the command.
```bash
docker search mongo
```
![t15](https://user-images.githubusercontent.com/97040413/195178786-a8048d2d-5bb7-4674-9de9-381e889d7d9f.png)

