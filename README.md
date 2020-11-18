# Container Docker aplicações PHP

Objetivo deste repositório é disponibilizar um ambiente com Apache 2, PHP 7.3, Mysql 8.0 e PHPMyAdmin

São 3 containers docker, sendo um para o apache, outro para o mysql e ainda outro para o PHPMyAdmin.

Todos podem ser acessados por http://localhost

Apache roda na porta 8001
PHPMyAdmin roda na porta 8000
Mysql roda na porta 3306

Caso tenha algum destes serviços em execução lembra de encerra-los antes de subir os containers.

Comando para iniciar os container:

sudo docker-compose up -d (O comando roda os container em background deixando o console liberado.)

caso faça alguma alteração em algum arquivo de configuração lembrar de acrescentar a opção --build junto
com o comando sudo docker-compose up -d --build



