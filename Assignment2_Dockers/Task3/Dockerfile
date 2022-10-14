FROM python:3.7
RUN pip install fastapi uvicorn
COPY . /app
WORKDIR /app
CMD ["uvicorn","app:app","--host","127.0.0.1","--port","8080"]