![logo](https://assets.zabbix.com/img/logo/zabbix_logo_500x131.png)

[![Build images (DockerHub)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build.yml/badge.svg?branch=trunk&event=push)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build.yml)
[![Build images (DockerHub, Windows)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build_windows.yml/badge.svg?branch=trunk&event=push)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build_windows.yml)

# Zabbix using docker-compose

Zabbix server with PostgreSQL database support, Zabbix web interface based on the Nginx web server and SNMP trap feature.

## Usage

``` git clone https://github.com/derssen/zabbix.git
cd zabbix
docker-compose build
docker-compose up 
```


