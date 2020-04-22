# zabbix-proxy-pgsql
Zabbix proxy 4.4.7 with postgresql database\
Usage:
```bash
git clone https://github.com/komivlad/zabbix-proxy-pgsql
cd zabbix-proxy-pgsql
docker-compose up -d --build
```
You can use prebuilded image from docker hub\
`komivlad/zabbix-proxy-pgsql:latest`


Replace in `docker-compose.yaml` file string\
`build: ./build/zabbix-proxy`\
with\
`image: komivlad/zabbix-proxy-pgsql:latest`

Run docker-compose\
`docker-compose up -d`
