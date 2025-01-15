# community.zabbix-rhel7
Ansible collection for zabbix-agent2 that works is rhel7 bases systems.


This collection is used for installing and configuring zabbix-agent2 on rhel7-like servers.


Starting with version 3.0.0 of the community.zabbix collection, the following changes occurred:

# Breaking Changes / Porting Guide
# --------------------------------

- All Roles - Remove support for Centos 7
- All Roles - Remove support for Python2
- All Roles - Removed support for Debian 10.
- All Roles - Removed support for Ubuntu 18.08 (Bionic)
- Remove support for Ansible < 2.15 and Python < 3.9
- Remove support for Zabbix 6.2
- Removed support for Zabbix 6.2
- zabbix_agent role - Remove support for `zabbix_agent_zabbix_alias`.
- zabbix_agent role - Remove support for `zabbix_get_package` variable.
- zabbix_agent role - Remove support for `zabbix_sender_package` variable.
- zabbix_agent role - Remove support for all `zabbix_agent2_*` variables.

Information obtained from the file /root/.ansible/collections/ansible_collections/community/zabbix/CHANGELOG.rst
