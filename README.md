# Ansible-Bind-Example
Ansible playbook example for Bind server
This is a simple ansible playbook example for installing latest Bind server
on centos7/redhat. This playbook will create the named.conf with some basic settings,
then inserts zone settings according to the domainList vars, for this example there are 
three domains (add as many as you like in domainList on the playbook.yml) 
Creates and copy zone files on /var/named folder according to the domainList vars, 
with appropriate permissions.
Of course in order to be fully functional you have to enter your correct domains and
zone entries, A records, CNAMES,MX etc, with real data and ip's. You can tweek this playbook 
to much your own needs. Have fun !! 
