Note: User login details and managed host address needs to be changed in the playbook and the inventory file. 
password needed to run the playbook is 'redhat'
Execution steps:
Go to project folder and execute following command.
   Ansible-playbook   create_users.yml 

Description: 
In this playbook Ansible Vault is used to encrypt a file containing passwords on the local system and use the encrypted version in a playbook to create users on the managed hosts.
