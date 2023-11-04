FROM python:3.9-bullseye

WORKDIR /app
EXPOSE 8080

RUN useradd -s /bin/bash trg
USER trg

RUN pip install flask

COPY hello-world.py hello-world.py

ENTRYPOINT python /app/hello-world.py
