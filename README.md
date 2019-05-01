
ssh-access

Grant/Revoke SSH access to a group of instances to a new developer

Use below given command to add new user and grant SSH access
ansible-playbook -e "action=grant" ssh.yml

Use below given command to remove user, hence revoke SSH access as well
ansible-playbook -e "action=revoke" ssh.yml
