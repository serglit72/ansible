# Ansible

### Ansible playbook for Apache installation on Ubuntu 20.04 and Ubuntu 22.04  
```shell
install_apache_ubuntu.yml
```
### Inventory file located in the same directory:

```shell
inventory.txt
```

### Run the playbook 

```shell
ansible-playbook -i inventory.txt install_apache_ubuntu.yml 
```
### Tests:
    - Apache server is up-and-running and enabled
    - webpage has to have word "Cycle" in the content
### If test failed:
    !!! error message: <color:red>'service is not happy'</color:red> will appear






