# Ansible's Playbooks
Playbook to build Infra with:
- Pip
- Docker
- Sonar Docker Container & MySQL
- Jenkins Docker Container
- Nexus Docker Container

Before running the playbook
- Create hosts file with Server name inside

Ex: 
```
echo [docker_nexus]
10.88.0.142 ansible_user=ubuntu ansible_python_interpreter=/usr/bin/python3 >> /etc/ansible/hosts
```
```
echo [host_name] [HOST IP] >> /etc/ansible/hosts
```

Provisioning Tools
```
ansible-playbook site.yml
```


To log in to Tools:

- Login - admin
- Password - admin

PS: Vagrant machine could be used for tests.
