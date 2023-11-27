# ansbl-logrotate


Complete the following tasks:

Grab the module from GitHub: https://github.com/arillso/ansible.logrotate
Use ansible-galaxy install command to install inside the /home/thor/playbooks/roles
If you stumbled upon the issue, could not find/use git, install git in the ansible-runner first and install the role.

Configure your log rotation rules as:

daily
rotate 3
compress
…to rotate a log file that would present on location /var/log/myapp.log
