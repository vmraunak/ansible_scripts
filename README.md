- [Zabbix Agent Installation script](https://github.com/vmraunak/ansible_scripts/blob/main/zabbix_agent_install.yml) : `ansible-playbook -i "<host-ip>," zabbix_agent_install.yml -e "zabbix_server=<ip> zabbix_hostname=<host-name>" -u <user-name> -K`
- [Zabbix Config](https://github.com/vmraunak/ansible_scripts/blob/main/zabbix_conf.yml) : `ansible-playbook -i "<host-ip>," zabbix_conf.yml -e "zabbix_server=<ip> zabbix_hostname=<host-name>" -u <user-name> -K`

- [Docker Installation](https://github.com/vmraunak/ansible_scripts/blob/main/docker_install.yml) : `ansible-playbook -i '<ip>,' docker_install.yml -u <user-name> -K`
