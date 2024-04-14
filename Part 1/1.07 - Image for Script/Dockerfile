FROM ubuntu:22.04

COPY script.sh .

RUN apt update && apt install curl -y && chmod +x script.sh

CMD ./script.sh
