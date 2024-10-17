<h1 align="center" style="font-weight: bold;">To-Do List 💻</h1>

<p align="center">
    <b>Este é um sistema de gerenciamento de tarefas desenvolvido com Java e Spring Boot, projetado para permitir a criação, edição e gerenciamento de tarefas de forma eficiente e organizada.</b>
</p>

<h2 id="technologies">💻 Tecnologias</h2>

- Java
- Spring Boot
- Spring Web
- JPA
- MySQL



<h2 id="started">🚀 Iniciando o projeto</h2>
<h3>Pré Requisitos</h3>
- [Java](https://github.com/)

<h3>Clonando</h3>

```bash
git clone https://github.com/hendrickm97/java-todolist.git
```
<h3>Navegue até o diretório</h3>

```bash
cd nome-do-repositorio
```

-Executando Projeto:

```bash
mvn spring-boot:run
```
<h2 id="routes">📍 API Endpoints</h2>
​
<h3 id="get-auth-detail">GET /todos</h3>


**RESPONSE**

```json
{
  "id": 1,
  "nome": "Estudar Java",
  "descricao": "Aprender mais sobre spring boot e spring boot web",
  "realizado": false,
  "prioridade": 1
}
```


<h3 id="get-auth-detail">POST /todos</h3>

**REQUEST**

```json
{
  "nome": "Estudar Java",
  "descricao": "Aprender mais sobre spring boot e spring boot web",
  "prioridade": 1
}
```
**RESPONSE**

```json
{
  "id": 1,
  "nome": "Estudar Java",
  "descricao": "Aprender mais sobre spring boot e spring boot web",
  "realizado": false,
  "prioridade": 1
}
```
<h3 id="get-auth-detail">PUT /todos/{id}</h3>

**REQUEST**

```json
{
  "nome": "Estudar Java e Python",
  "descricao": "Aprender mais sobre spring boot, spring boot web e fastapi",
  "prioridade": 1
}
```
**RESPONSE**

```json
{
  "id": 1,
  "nome": "Estudar Java e Python",
  "descricao": "Aprender mais sobre spring boot, spring boot web e fastapi",
  "realizado": false,
  "prioridade": 1
}
```

<h3 id="get-auth-detail">DELETE /todos/{id}</h3>
Nessa rota deletamos a tarefa e retornamos a lista com as outras tarefas.

