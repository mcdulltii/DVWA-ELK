# DVWA-ELK

# Features
- Packetbeat
- Filebeat
- Metricbeat
- Heartbeat
- Suricata

# Config files
*.yml files are stored within dvwa/ and dvwamysql/
MYSQL Database configured using commands as of below
```sql
mysql -pPassw0rd!
CREATE USER 'dvwa'@'%' IDENTIFIED BY 'Passw0rd!';
CREATE DATABASE dvwa;
GRANT ALL PRIVILEGES ON dvwa.* TO 'dvwa'@'%';
```

# Logging system
- Elasticsearch
- Logstash (Unused)
- Kibana
