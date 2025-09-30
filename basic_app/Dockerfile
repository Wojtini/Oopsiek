FROM python:3.13.7-alpine3.22

WORKDIR /app

COPY . .

RUN ["pip", "install", "-r", "requirements.txt"]

ENTRYPOINT ["python", "/app/main.py"]
