# zabbix-dockerized

La idea de esta implementación es la de tomar el [proyecto oficial](https://github.com/zabbix/zabbix-docker) y hacerla más sencilla.

Se decidió optar por un enfoque utilizando docker-compose para hacer de esta forma más simple el update de versiones y el mantenimiento del mismo.

## Forma de uso

1. Clonar repositorio
2. Ajustar variables de entorno
3. Ejecutar `docker-compose up -d`

### Documentación:

- https://www.zabbix.com/documentation/current/en/manual/installation/containers
- https://github.com/zabbix/zabbix-docker