Docker-swarm-ansible
========================
This project setup the docker swarm using ansible (Ubuntu 16.04).

# Install
anxible-galaxy install nickjj.docker
git clone https://github.com/ChinaShrimp/docker-swarm-ansible.git

# Run
modify file ansible_hosts based on your cluster configurations.
```
ansible-playbook site.yml
``` 

Reference:
https://nickjanetakis.com/blog/automate-installing-docker-and-docker-compose-with-ansible
