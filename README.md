# Task12_arth

12.1 Use Ansible playbook to Configure Reverse
Proxy i.e. Haproxy and update it's configuration
file automatically on each time new Managed node

(Configured With Apache Webserver) join the inventory.

12.2 Configure the same setup as 12.1 over AWS

Step 1 :- Launch the Instance for websever and Haproxy 


Step 2 :- Check the hosts file 

Command : vi hosts

Step 3 :-  Check Connectivity 

Command :  ansible all -m ping

Step 4 :- Check the syntax of ansible playbook 
Command : ansible-playbook --syntax Task12.yml

Step 5 :- Run the ansible-playbook 
Command : ansible-playbook Task12.yml

Step 6 :- Check wether the all the system properly of not by using the IP address
