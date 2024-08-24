FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y software-properties-common && \
    add-apt-repository ppa:deadsnakes/ppa && \
    apt-get update && \
    apt-get install -y python3

WORKDIR /home/komarov/Projects/DockerProjects/DockerCollabnix/labs19
COPY hello.py a.py ./

CMD ["python3", "hello.py"]
