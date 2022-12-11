
# Speedtest Template for Zabbix

Get server and client information on Speedtest.


## Installation

Install using terminal, tested on Debian and Oracle Linux:

You need speedtest-cli installed on the host:

#### Debian Based:
```bash
  sudo apt install speedtest-cli
```

#### RHEL/Oracle Linux Based:
```bash
  sudo yum install speedtest-cli
```

Just download the .conf file in the UserParameters Folder, in this case is the default folder created on Zabbix Agent 2 installation from repos:


```bash
  sudo wget https://raw.githubusercontent.com/emcgarcia101/zbxtemplates/main/speedtest/speedtest.data.conf -P /etc/zabbix/zabbix_agent2.d/
```

Import the template on Zabbix Server and assing to a host and have fun :)

#### Create on Zabbix Server 6 LTS
