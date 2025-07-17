# ForumHub

ForumHub é uma API para criar e gerenciar tópicos em um fórum, como o Fórum da Alura.

## O que o projeto faz?

- Usuários cadastrados podem criar tópicos com título, mensagem e curso.
- Cada tópico pertence a um usuário.
- Apenas o autor do tópico pode editar ou apagar ele.
- O sistema usa login com senha e token JWT para garantir segurança.
- Dá para listar, criar, editar e deletar tópicos.

## Tecnologias usadas

- Java 17  
- Spring Boot 3  
- Spring Security com JWT  
- Banco de dados MySQL  
- Swagger para documentação  

## Como rodar

1. Clone o projeto:

2. git clone https://github.com/seu-usuario/forumhub.git
cd forumhub


2. Crie o banco de dados `forum_hub` no MySQL.

3. Configure o arquivo `application.properties` com seu usuário e senha do MySQL.

4. Rode a aplicação:

./mvnw spring-boot:run


5. Teste os endpoints com o Insomnia, Postman ou navegador.

## Como usar

- Faça login para receber um token JWT.
- Use esse token para criar, editar ou apagar tópicos.
- Consulte a documentação em `http://localhost:8080/swagger-ui.html`.

## Contribuindo

Quer ajudar? Faça um fork, crie uma branch, faça suas mudanças, e abra um pull request.

---

Projeto feito para o desafio do programa Oracle Next Education da Alura.

---


