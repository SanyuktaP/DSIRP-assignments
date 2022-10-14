### Automate Assignment below task using github action.

#### 1) Build Docker Image
![task3_build](https://user-images.githubusercontent.com/97040413/195937762-61b47df4-98e2-437b-b81b-3a085b16908b.png)



###### Run docker image build in previous step.
![task3_run](https://user-images.githubusercontent.com/97040413/195937794-8a64783d-c563-4e72-8272-636d2e77004b.png)


#### 2) Push your Docker image to Docker Hub.
###### Step1: Tag
```bash
docker tag <img_name>:<version> <username>/<img_name>
```
![docker_tag](https://user-images.githubusercontent.com/97040413/195938360-94818a08-8661-4be1-b70c-05d467a61216.png)

###### Step2: Push
```bash
docker push <username>/<img_name>
```
![docker_push](https://user-images.githubusercontent.com/97040413/195938558-ac503323-2502-4834-802a-8dac39b92982.png)
Push Docker Image to Docker hub.



#### Output: After pulling
![task3_run3](https://user-images.githubusercontent.com/97040413/195937934-1adcef45-ef36-4443-8a35-00c594a452cf.png)