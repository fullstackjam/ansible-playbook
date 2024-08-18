# Homelab-ansible
ansible-playbook -i inventory/inventory.ini playbooks/nfs.yaml -e "nfs_server=192.168.2.202"

ansible-playbook --inventory inventories/prod.yml boot.yaml
