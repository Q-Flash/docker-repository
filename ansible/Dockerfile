FROM ubuntu:latest

apt update
apt install -y software-properties-common
add-apt-repository -y --update ppa:ansible/ansible
apt install -y ansible

ENTRYPOINT ["ansible"]
