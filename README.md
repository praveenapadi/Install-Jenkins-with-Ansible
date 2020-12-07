# Install-Jenkins-with-Ansible
Install Jenkins with Ansible Playbook

# Description:
This is a simple playbook to install Jenkins with Ansible on CentOS. 

# Files Used:
mainplay.yml: This is the main playbook which needs to be executed. Role install-jenkins is called from this playbook

inv.ini: This is thye inventory file. Define your hosts here

roles: Created using ansible-galaxy. Use command ansible-galaxy init <role name>
  
  tasks/main.yml: This yaml file installs and starts jenkins. The binaries are used online. Offline version will upload soon.
  


