# 📣 ForumHub - API REST do Fórum Alura

ForumHub é uma API REST desenvolvida como parte do desafio final do programa **Oracle Next Education - Back-End**, oferecido pela **Alura em parceria com a Oracle**.  
O objetivo do projeto é simular uma aplicação de fórum, semelhante ao Fórum da própria Alura, permitindo **a criação, visualização, edição e exclusão de tópicos** por usuários autenticados.

Este projeto tem foco em segurança, regras de negócio reais e boas práticas com Java e Spring Boot. Foi desenvolvido com autenticação via **JWT**, validações robustas e documentação via **Swagger**.

---

## 🧠 Desafio proposto

O desafio consiste em construir um **sistema de fórum com autenticação**, respeitando as seguintes regras de negócio:

- Apenas usuários cadastrados podem criar novos tópicos.
- Cada tópico pertence a um usuário.
- Tópicos devem conter: título, mensagem, curso e data de criação (gerada automaticamente).
- Apenas o autor pode editar ou deletar seu próprio tópico.
- Operações como listagem, detalhamento, criação, atualização e exclusão de tópicos devem ser protegidas.
- O sistema deve seguir princípios de segurança como autenticação e autorização via tokens Bearer JWT.

---

## 🚀 Tecnologias utilizadas

- Java 17  
- Spring Boot 3  
- Spring Security  
- JWT (Json Web Token)  
- Hibernate / JPA  
- Jakarta Bean Validation  
- Swagger / OpenAPI  
- MySQL  
- Insomnia / Postman (para testes de requisições HTTP)  

---

## ⚙️ Como executar o projeto

### Pré-requisitos:

- Java 17 instalado  
- MySQL rodando localmente  
- IDE de sua preferência (IntelliJ, VSCode, Eclipse)  
- Maven configurado


🛠 Funcionalidades implementadas
✅ Cadastro e login de usuários
✅ Criação, edição, listagem e exclusão de tópicos
✅ Associação entre usuários, cursos e tópicos
✅ Proteção de endpoints com Spring Security + JWT
✅ Documentação interativa com Swagger

💬 Sobre a experiência
Este projeto foi desafiador e ao mesmo tempo gratificante. Aprendi na prática como aplicar os conceitos de segurança em APIs, autenticação JWT, validação de dados, relacionamentos entre entidades e a importância de documentar bem uma aplicação sem interface gráfica.

Além disso, entendi o valor de boas práticas no desenvolvimento back-end e a força da comunidade técnica, tanto no Discord da Alura quanto colaborando com colegas.

🤝 Contribuições
Quer colaborar com esse projeto?

Faça um fork

Crie uma branch: git checkout -b minha-contribuicao

Faça suas alterações

Faça commit: git commit -m 'Minha contribuição'

Envie para o GitHub: git push origin minha-contribuicao

Crie um Pull Request

📝 Licença
Este projeto está sob licença MIT. Consulte o arquivo LICENSE para mais detalhes.

🧑‍💻 Autor
Desenvolvido como parte do desafio final da formação back-end da Alura | Programa Oracle Next Education

Instrutor responsável: Eric Monné
Desenvolvedora: Seu Nome Aqui

go
Copiar
Editar







