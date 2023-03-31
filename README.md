![logo](https://assets.zabbix.com/img/logo/zabbix_logo_500x131.png)

[![Build images (DockerHub)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build.yml/badge.svg?branch=trunk&event=push)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build.yml)
[![Build images (DockerHub, Windows)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build_windows.yml/badge.svg?branch=trunk&event=push)](https://github.com/zabbix/zabbix-docker/actions/workflows/images_build_windows.yml)
[![Version](https://badge.fury.io/gh/alexanderzobnin%2Fgrafana-zabbix.svg)](https://github.com/alexanderzobnin/grafana-zabbix/releases)

# Zabbix using docker-compose

Zabbix server with PostgreSQL database support, Zabbix web interface based on the Nginx web server and SNMP trap feature.

## Usage

``` 
git clone https://github.com/derssen/zabbix.git
cd zabbix
docker-compose build
docker-compose up 
```



### Docker Compose

There is provided Docker Compose files for each set of base Operating System and Database engine.

Templates support several [Compose  profiles](https://docs.docker.com/compose/profiles/). Minimal set of services is brought up by default, to start additional components e.g. Zabbix Agent use profile 'full' or 'all'. Additionally, it is possible to start only required components.

## Community Resources, Feedback, and Support

- Found a bug? Want a new feature? Feel free to open an [issue](https://github.com/derssen/zabbix/issues/new).
- Have a question? You also can open issue, but for questions, it would be better to use [Grafana Community](https://t.me/DTomilov) telegram.
- Need additional support? Contact me for details [dtomilov.dev@gmail.com](mailto:dtomilov.dev@gmail.com)

---
:copyright: 2015-2023 Den Tomilov dtomilov.dev@gmail.com

