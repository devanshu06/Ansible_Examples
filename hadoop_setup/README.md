# Setting up a Hadoop Cluster using Ansible Playbooks
### About the files
- <b>main_play.yml</b> - Playbook used to execute a list of playbooks (Master.yml, Slave.yml)
- <b>hosts</b> - Sample inventory file. Contains the details of each host under each group (namenodes, datanodes)
- <b>Master.yml</b> - Playbook to install hadoop and Configure the namenode.
- <b>Slave.yml</b> - Playbook to install hadoop and Configure the datanode.
- <b>ansible.cfg</b> - Configuration file of ansible to tell ansible about the IP inventory.
- <b>hdfs-site.xml.j2</b> - Jinja2 template file for the hdfs-site.xml file of the namenode & datanode(s).
- <b>core-site.xml.j2</b> - Jinja2 template file for the core-site.xml file of the namenode & datanode(s).
