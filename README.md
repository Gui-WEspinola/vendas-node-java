## Sobre a aplicação

Trata-se de um desenvolvimento de um sistema para fins de estudos, visando a prática de comunicação entre microsserviços e utilização de tecnologias de mensageria.

A ideia até o momento é fazer aplicações que contenham diferentes linguagens de programação e bancos de dados distintos, comunicando-se de maneira assíncrona.

Dessa forma, estamos construindo um sistema de vendas, utilizando autenticação de usuários, bancos de dados relacional e não relacional, 

No presente momento, a API está sendo desenvolvida para utilizar as seguintes tecnologias:

* JavaScript utilizando Express.js
* Node.js
* Java 17 com Spring
* PostgreSQL
* MongoDB
* Serviços de mensageria com RabbitMQ
* Docker-compose
* Autenticação com JWT

---

### Como executar a aplicação (em construção)

Todas as informações para acesso da aplicação estão no arquivo `docker-compose.yml` de maneira provisória. Posteriormente a serem alterados para variáveis de ambiente.

Inicialmente, após clonar o repositório em sua máquina e com docker em funcionamento, é necessário inicializar o docker-compose:

    docker-compose up --build

Feito isso, todos os sistemas já devem estar em funcionamento em sua máquina. Todos os detalhes sobre os contêineres estão contidos no arquivo `docker-compose.yml`.