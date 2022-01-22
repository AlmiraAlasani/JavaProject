# JavaProject
Library Management System

#Clone from git: https://github.com/AlmiraAlasani/JavaProject

#How to run This Project

1.Import database from library.sql
2.Open Project
3.Go to src/main/com.example.demo/demoApplication.java
4.Run Demo Application

#Endpoint

#Costumer endpoint

1.URL: http://localhost:8080/costumer Get all Costumer - METHOD = GET

Response:
[{  "id": 1,"name": "Meriton","surname": "Ademi"}, {"id": 4,"name": "Almira","surname": "Alasani" }, {"id": 5,"name": "Ali ","surname": "Amzai"}]

2.URL: http://localhost:8080/costumer/ Get Costumer by id - METHOD = GET

Response:
{"id": 4,"name": "Almira","surname": "Alasani" }

3.URL: http://localhost:8080/costumer/ Edit Costumer by id - METHOD = PUT

{
    "id": 4,
    "name": "Almira",
    "surname": "Alasani"
}


