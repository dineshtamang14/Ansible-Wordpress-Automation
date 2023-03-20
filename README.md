# To Ansible Lab

### To install Ansible of latest version
```sh
pip3 install ansible
```

### To install ansible docker extension
```sh
ansible-galaxy collection install community.docker
```

### To check all the vms connections
```sh
ansible all -m ping
```

### To Run Ansible Playbook
```sh
ansible-playbook <playbook-file.yaml>
```

### To Check installed docker version on all nodes
```sh
ansible nodes -a "docker --version"
```

