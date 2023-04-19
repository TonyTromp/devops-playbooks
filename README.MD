# Download config from server
#ansible-galaxy collection install ansible.posix

ansible-playbook -i inventory/hosts.ini playbooks/download_configs.yaml --extra-vars "target=qnap.home"

