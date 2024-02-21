FROM python:3.12.2-bookworm

WORKDIR /app

COPY /src/requirements.txt .

RUN apt-get update && \
    apt-get -y upgrade && \
    pip install -r /app/requirements.txt
