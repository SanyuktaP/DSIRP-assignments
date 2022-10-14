#### Task 3

### Project link: https://github.com/SanyuktaP/fastapi-hello-world-docker

##### Create a hello world fastapi application.

![appfile](https://user-images.githubusercontent.com/97040413/195937665-e2355e3f-8864-452b-b93e-caba7961a9c5.png)
```bash
import uvicorn
from fastapi import FastAPI

app=FastAPI()

@app.get("/")
def home():
    return {"message": "Hello World!"}
```


##### Create a Dockerfile for your fastapi hello world application.
![dockerfile](https://user-images.githubusercontent.com/97040413/195937712-96278ed4-b67a-4c85-a447-ef823a9ac4da.png)
```bash
FROM python:3.7
RUN pip install fastapi uvicorn
EXPOSE 80
COPY . /app
WORKDIR /app
CMD ["uvicorn","app:app","--host","0.0.0.0","--port","80"]
#CMD ["uvicorn","app:app","--reload"]
```



##### Build Docker image using Docker file.
![task3_build](https://user-images.githubusercontent.com/97040413/195937762-61b47df4-98e2-437b-b81b-3a085b16908b.png)



##### Run docker image build in previous step.
![task3_run](https://user-images.githubusercontent.com/97040413/195937794-8a64783d-c563-4e72-8272-636d2e77004b.png)


##### Push your Docker image to Docker Hub.
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

###### Push your Docker image to Docker Hub.

![docker_hub](https://user-images.githubusercontent.com/97040413/195937846-6861c5d5-aabc-4c2c-af81-f8672632e811.png)


#### Output: After pulling
![task3_run3](https://user-images.githubusercontent.com/97040413/195937934-1adcef45-ef36-4443-8a35-00c594a452cf.png)
