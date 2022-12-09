# Spring-Framework-Demo
Introductory to spring framework

## Demo Descriptions
This is a demo application which is built with java and springboot. The objective is to develop a <strong>CRUD</strong> RESTful API. The API is of an object Person which consists of attributes id and name. The API is able to GET, POST, PUT and DELETE. The appplication is a demonstration of java and the ability to work with the spring framework. It focuses on the fundamentals of API development and dependency injection. It is beginner friendly and simple to understand.

## Specifications
The API is able to utilise an in memory database which is composed by an arrayList and a real database. The database of choice was PostgreSQL which is setup and run locally. A container, docker, which holds the database image is used. During creation of the API one can test the endpoints with Postman. This application mainly focuses on the backend and has no user interface to interact with.

##Endpoints:
<ul>
<li>GET /api/v1/person : Gets all the database entries </li>
<li>GET /api/v1/person/{id} : Gets a specific person by id parsed</li>
<li>POST /api/v1/person : Inserts a person into the database </li>
<li>PUT /apiv1/person/{id} : Updates an existing record of the id parsed</li>
<li>DELETE /api/v1/person/{id} : Deletes an existing record of the id parsed</li>
</ul>
