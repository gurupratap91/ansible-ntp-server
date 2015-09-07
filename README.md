# ansible-ntp-server
Move to the directory of the repository

Change the default ansible inventory file location to current directory using the command:
  export ANSIBLE_INVENTORY=./hosts

Check by pinging the hosts:
  ansible all -m ping

Run the playbook using the command:
  ansible-playbook playbook.yml
