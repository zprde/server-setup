# setup server for vps

## How to run

1. Install python and ansible
2. Make sure you can connect to the vps by ssh keys
3. Prepare a hosts file contains the vps ip or domain. [Reference](https://docs.ansible.com/ansible/latest/inventory_guide/index.html)
4. Run `ansible-playbook -v -i hosts site.yaml`