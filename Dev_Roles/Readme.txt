Note: User login details and managed host address needs to be changed in the playbook and the inventory file. 
Execution steps:
Go to project folder and execute following command.
   Ansible-playbook   use-vhost-role.yml 

Description: 
The playbook has two roles vhost and myfirewall. Vhost role depends on myfirewall. The project achieves following configurations.

•	Installs the httpd package
•	Starts and enables the httpd service
•	Downloads the HTML content into the virtual host’s DocumentRoot directory
•	Installs the template configuration file that configures the web server
•	Installs the firewalld package
•	Starts and enables the firewalld service
•	Opens a firewall service port.
