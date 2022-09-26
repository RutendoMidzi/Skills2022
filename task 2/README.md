#Task 2 -- Ansible

>Task name:

Manage WebServers through Ansible.

>Task description:

Write the Ansible script to install and test the web server with ping command in a single playbook. Choose either Apache or Nginx server based on your own preference.

● Name the playbook WEB SERVER INSTALLATION AND TESTING.

● TWO tasks must be successful to get a grade (Installation and Testing).

● Take screenshots indicating the success of your actions and save script files and related docs. 

>Task preparation

Enable the SSH server.

Open the ansible directory in VS Code.

Edit the Ansible inventory file 


Open the ansible-apache and add a line in the ‘host’ file.



Edit the ansible.cfg file

The ansible.cfg file tells Ansible where to find the inventory file and sets certain default parameters.

Ping the web server to check for connection. 


Check if Ansible can communicate with the webserver







>Task implementation 

Creating Ansible Playbook to Automate Web Server Installation

Create a file named ‘test_apache_playbook.yaml’


Run the Ansible playbook


For Ansible to install apache, create a new file in the ansible-apache directory and write:


Run the Ansible to install Apache


Verify if Apache has been installed.


Run the ip address on the browser to get to the Apache home page.





