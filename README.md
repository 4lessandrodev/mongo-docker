# Objetivo 
#### Criar uma imagem mongo e disponibilizar um client para acesso no navegador 

##### Requisitos:

- Você precisa ter o docker desktop instalado 

`https://docs.docker.com/get-docker/`

- Também deve ter o docker-compose instalado (Para Linux, para os demais O.S o mesmo é instalado com o passo anterior) 

`https://docs.docker.com/compose/install/#install-compose`

##### Passos 

- `$ git clone https://github.com/ALESSANDROLMENEZES/mongo-docker.git`

- `$ cd mongo-docker`

- `$ docker-compose up -d`

Pronto seu mongo está rodando na porta 27017 
Você pode acessar o client pelo link http://localhost:8081

#### Opcionalmente 

Para ter acesso ao banco de dados você pode utilizar o robot 3t

https://robomongo.org/

- Conexão: localhost:27017 
- user: root 
- senha: root

##### Para interagir com o container via terminal 

`docker exec -it mongo_mongo_1 bash`

[mongo_mongo_1] é o nome do container

Para confirmar o nome do container em sua máquina basta execurar o comando 

`docker ps`

O nome encontra-se na ultima coluna [NAMES]

Para sair do modo de interação pode executar o comando 

`exit`

