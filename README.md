# Define-sysctl-parameters-using-Ansible
This playbook defines sysctl parameters in: /etc/sysctl.d/<component name>.conf using role "define_sysctl_parameters"<br/>
./group_vars/all - definition of sysctl parameters<br/>
./roles/define_sysctl_parameters/tasks - task in role, used for definition sysctl parameters<br/>
./inventory - servers IP<br/>
./start_palybook.sh - shell script to start playbook<br/>
./start_palybook_with_debugging.sh - shell script to start playbook with debugging<br/>
