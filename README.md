[JAVA_BADGE]:https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white
[SPRING_BADGE]: https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white
[POSTGRES_BADGE]: https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white


<h1 style="font-weight: bold;">API CRUD 💻</h1>


![spring][SPRING_BADGE]
![java][JAVA_BADGE]
![postgres][POSTGRES_BADGE]

<p>
 <a href="#started">Instruções de Instalação</a> • 
  <a href="#routes">API Endpoints </a> 
</p>

<p>
  <b>O projeto é uma aplicação backend que implementa um sistema CRUD (acrônimo para Create, Read, Update e Delete). Ele faz uso da linguagem Java, o framework Java Spring, banco de dados Postgres e o software de requisições Insomnia. O projeto foi construido para a implementação prática desses conceitos nos endpoints.</b>
</p>

<h2 id="started">Instruções de Instalação</h2>

<h3>Pré-requisitos:</h3>

- Uma IDE habilitada para compilar código Java.
- Um banco de dados local (no projeto foi utilizado o Postgres).
- Um software de capaz de fazer as requisições http.

<h3>Clonando</h3>

No terminal digite:

```bash
git clone https://github.com/BrendaBraganca/API-REST-SPRING
```

<h3>Variaveis de Ambiente</h2>
Em application.properties adapte o seguinte trecho:

```yaml
spring.datasource.url=jdbc:postgresql://localhost:5432/product
spring.datasource.username=your-user-name
spring.datasource.password=your-password

```

<h3>Inicializando o projeto</h3>

1. Execute o programa na sua IDE.
2. Observe em qual porta o seu programa está sendo executado (provavelmente na porta 8080)
3. Lembre-se de adicionar a rota '/product'quando for disparar as requisições


<h2 id="routes">📍 API Endpoints</h2>
​
| route               | description                                          
|----------------------|-----------------------------------------------------
| <kbd>GET /product</kbd>     | retorna todos os produtos cadastrados no banco de dados.
| <kbd>POST /product</kbd>     | adiciona um produto ao nosso banco de dados.
| <kbd>PUT /product</kbd>     | atualiza o campo de um produto selecionado no banco de dados.
| <kbd>DELETE /product</kbd>     | deleta o  produto selecionado no nosso banco de dados.


<h3>Banco de Dados</h3>

O banco de dados utilizado foi o Postgres e a interface utilizada para melhor acompanhar os comando utilizados na aplicaçao foi o Postico.
-  <a href="https://www.youtube.com/watch?v=PShGF_udSpk&t=420s&pp=ygUdaG93IHRvIGluc3RhbGwgcG9zdGdyZXNxbCBtYWM%3D">How to Install PostgreSQL</a>
-  <a href="https://www.youtube.com/watch?v=7ROh8Mel6Cs&t=181s&pp=ygUaaG93IHRvIGluc3RhbGwgcG9zdGljbyBtYWM%3D">How to Install Postico</a>