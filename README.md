# ansible-levelup
This project allows.

- configure ELK stack running in a docker container on a linux box
- configure zabbix server running in a docker container on a linux box
- install IIS on a Windows server
- inttall winfilebeat on a Windows server and configure IIS log shipping to elasticsearch
- install winlegbeat on a Windows server and configure event viewer log shipping to elasticsearch
- install zabbix client on a Windows server

IIS logs and Event Viewer loges can be viewed in Kibana http://<kibana_ip>:5601

Server logs and performance counters can be viewed in zabbix http://<zabbix_ip>:80

Virtual Machines are hosted in Microsoft Azure Cloud.