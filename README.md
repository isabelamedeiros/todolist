##todolist

Bootcamp Java e Spring Boot realizado pela Rocketseat - Construção back-end de uma aplicação de gerenciamento de tarefas.


> Status do Projeto: Concluido

## Ferramentas e Tecnologias

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" width="40" height="40" />

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original-wordmark.svg" width="40" height="40"  />
  

## Deploy da Aplicação com render.com:

> https://todolist-ki9m.onrender.com


## Endpoints:

POST:
http://localhost:8080/users/
Exemplo de body:

{
	"username": "user",
	"name": "nome",
	"password": "senha"
}

POST:
http://localhost:8080/tasks/

Exemplo de body:
{
	"description":"Gravaçao de Tasks - Teste",
    "title":"Tarefa teste",
    "startAt":"2023-10-15T16:21:00",
    "endAt":"2023-10-15T16:21:00",
    "priority":"ALTA",
    "createdAt":"2023-10-15T16:21:00"
}