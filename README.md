# ansible_playbook
This repository contains Ansible Playbooks that 
   1. Install the HTTPD server.
   2. Install and configure certificate.
   3. Clone certificates into configured directory.
  
Steps to run these files
   1. Need to call the main.yml file from the jenkins job [command in Jenkins_Call.sh].
  
    1.1. If the Ansible is installed in the same machine as jenkins you can directly run the command [command in Jenkins_Call.sh].
      
                       or else
                       
    1.2. You need to execute the cmd over ssh [From Ansible master ssh path]. 
  
