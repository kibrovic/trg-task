FROM python:3.9-bullseye

WORKDIR /app
EXPOSE 8080


RUN pip install flask

RUN useradd -s /bin/bash trg
USER trg

COPY hello-world.py hello-world.py

ENTRYPOINT python /app/hello-world.py
