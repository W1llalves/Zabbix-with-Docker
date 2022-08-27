# Zabbix-with-Docker
Subindo uma infraestrutura Zabbix com conteiners docker


# Zabbix com Docker Compose

O docker-compose.yml foi configurado de forma que o Docker crie 4 containers: zabbix-server, zabbix-frontend, grafana e mysql. Foram utilizadas as imagens oficiais do Zabbix, do Grafana e do MySQL. 

Ao executar o comando docker-compose up, o Docker irá subir de forma automática os containers do Zabbix, do Grafana e do MySQL. Além disso, o Zabbix já estará conectado ao banco de dados MySQL e o Grafana já estará com o plugin do Zabbix instalado.

Executar o seguinte comando na pasta que esta localizado o arquivo docker-compose.yml para suber os containers:

docker-compose up -d
