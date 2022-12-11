You need speedtest-cli installed on the host:

Debian Based:
sudo apt install speedtest-cli

RHEL/Oracle Linux:
yum install speedtest-cli

Just download the .conf file in the UserParameters Folder, in this case is the default folder created on Zabbix Agent 2 installation from repos:

sudo wget https://raw.githubusercontent.com/emcgarcia101/zbxtemplates/main/speedtest/speedtest.data.conf -P /etc/zabbix/zabbix_agent2.d/

Import the template on Zabbix Server and assing to a host and have fun :)

Create on Zabbix Server 6 LTS.
