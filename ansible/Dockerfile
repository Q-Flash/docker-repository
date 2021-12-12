FROM ubuntu:latest

RUN apt update
RUN apt install -y software-properties-common
RUN add-apt-repository -y --update ppa:ansible/ansible
RUN apt install -y ansible

ENTRYPOINT ["ansible"]
