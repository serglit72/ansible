# Ansible

### Ansible playbook for Apache installation on Ubuntu 20.04 and Ubuntu 22.04  
```
install_apache_ubuntu.yml
```
### Inventory file located in the same directory:

```
inventory.txt
```

### Run the playbook 

```
ansible-playbook -i inventory.txt install_apache_ubuntu.yml 
```
### Tests:
<p>
    - Apache server is up-and-running and enabled
    - webpage has to have word **Cycle** in the content
</p>
### If test failed:

    error message: __service is not happy__ will appear






