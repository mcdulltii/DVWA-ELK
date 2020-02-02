# DVWA-ELK

# Features
- Packetbeat
- Filebeat
- Metricbeat
- Heartbeat
- Suricata

# Setting up system
```python
chmod +x ./setup.sh
./setup.sh
```
<Run SQL commands from [Config files](https://github.com/mcdulltii/dvwa-elk#config-files)>
```python
chmod +x ./start.sh
./start.sh
```

# Logging system
- Elasticsearch
- Logstash (Unused)
- Kibana

# Config files
*.yml files are stored within dvwa/ and dvwamysql/

MYSQL Database configured for dvwa-elk_dvwamysql_1 as of below:
```sql
mysql -pPassw0rd!
CREATE USER 'dvwa'@'%' IDENTIFIED BY 'Passw0rd!';
CREATE DATABASE dvwa;
GRANT ALL PRIVILEGES ON dvwa.* TO 'dvwa'@'%';
```
