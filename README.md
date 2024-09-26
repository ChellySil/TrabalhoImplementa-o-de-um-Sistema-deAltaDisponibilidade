Trabalho
Este projeto tem como objetivo desenvolver e implementar um sistema de alta disponibilidade usando Docker Compose para gerenciar múltiplos serviços, incluindo um serviço web com operações CRUD em Java Spring Boot, um banco de dados MongoDB, e um Nginx configurado como balanceador de carga. Todas as rotas da API foram documentadas utilizando Swagger


A arquitetura é composta por três componentes:

Serviço Web (feito em Spring Boot): Responsável pelas operações de CRUD em um banco de dados MongoDB. Foram criadas, incialmente, três instâncias do serviço, gerenciadas pelo docker compose
Nginx: Configurado como um balanceador de carga para distribuir de maneira uniforme as requisições entre as três instâncias do serviço web
MongoDB: Utilizado como banco de dados, configurado no Docker Compose com persistência de dados
