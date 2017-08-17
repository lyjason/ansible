# ansible-for-zabbix
use ansible playbook to deployment zabbix


#2017年8月17日
更新了role方法的结构，pb.yml是老版本

----
**description  for tags:**
  name: rpm
  dcp: installation zabbix rpm 
  
  name: cache
  dcp: yum makecache
  
  name: agent/get/sender
  dcp: installation zabbix component
  
  name: file
  dcp: change zabbix_agentd.conf
