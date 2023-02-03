# mvc-spring-boot--livros-estudo

##1.Objetivo
Desenvolver uma aplicação na qual possamos gerenciar uma estante virtual.
Basicamente, ela terá as seguintes funcionalidades:
Listar todos os livros;
Cadastrar livro;
Consultar um livro específico;
Editar um livro por vez;
Excluir um livro;

##2.Configuração do Spring Initializr
Project: Maven Project
Language: Java
Spring Boot: 3.0.2
Group: com.livros
Artifact: estudo
Name: estudos
Description: Gerenciamento de estante virtual com Spring Boot
Package name: com.livros.estudo
Packaging: Jar
Java: 11
Dependências: Spring Web, H2 Database, Spring Boot DevTools, Spring Data JPA.

##3.Pacotes e classes

Os pacotes e as respectivas classes são:

| Pacote                          | Classe           |
|---------------------------------|------------------|
| com.livros.estudos.entity       | Livro            |
| com.livros.estudos.repository   | LivroRepository  |
| com.livros.estudos.service      | LivroService     |
| com.livros.estudos.service.impl | LivroServiceImpl |
| com.livros.estudos.controller   | LivroController  |

-EstudosApplication:é a classe principal do projeto;
-Livro:mapeia a tabela livro do banco de dados.
-LivroRepository:extends a classe JpaRepository com os parâmetros das classes Livro e Long.
-LivroService:interface com as assinaturas dos métodos que vão manipular os dados.
-LivroServiceImpl:implementa os métodos da interface LivroService.
-LivroController:classe controladora que contém os serviços que a aplicação disponibiliza.





 
