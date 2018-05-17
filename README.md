# Ansible Directory Layout

> Practice organizing an ansible playbook

## Usage example

```
docker build --tag mbigras/hacking .
docker run -itd --name hacking mbigras/hacking
ansible all -i hacking, -c docker -m ping
ansible-playbook -i hacking, -c docker main.yml
```
