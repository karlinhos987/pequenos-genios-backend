# 🏫 &nbsp;[PEQUENOS GÊNIOS](https://pequenosgenios-backend.herokuapp.com/swagger-ui/index.html#/)

- 📚 &nbsp; Desafio final do 1º **DEV FOR TECH by ACATE** desenvolvido pela Gama Academy: <a href="https://drive.google.com/file/d/1sG0nCl7868g2TRcnQ5rYnyhQ9YctgKAx/view?usp=sharing" target="_blank">detalhamento sobre o projeto</a>.
- 🛠 &nbsp; Desenvolvido por **Carlos Roberto de Oliveira Junior**.

 ---

*Ferramentas de Desenvolvimento Utilizadas*

![Eclipse](https://img.shields.io/badge/-Eclipse-333333?style=flat&logo=Eclipse&logoColor=white)
![Intellij IDEA](https://img.shields.io/badge/IntelliJ_IDEA-333333?style=flat&logo=intellij-idea&logoColor=IntelliJ_IDEA)

*Utilitários*

![Postman](https://img.shields.io/badge/-Postman-333333?style=flat&logo=postman)

*DevOps*

![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-333333?style=flat&logo=github)
![Heroku](https://img.shields.io/badge/Heroku-333333?style=flat&logo=heroku&logoColor=Heroku)

*Linguagens e Frameworks*

![Java](https://img.shields.io/badge/Java-333333?style=flat&logo=java&logoColor=Java)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-333333?style=flat&logo=postgresql&logoColor=PostgreSQL)
![SpringBoot](https://img.shields.io/badge/-SpringBoot-333333?style=flat&logo=SpringBoot)

Na aplicação foram incluídos: 
- Swagger.
- Lombok.
- Spring Security utilizando JSON Web Token e Refresh Token.
  
---

### 🖥️ Servidor de Desenvolvimento

Para clonar o repositório do git:

1. git remote add origin git remote add origin https://github.com/karlinhos987/pequenos-genios-backend.git
2. git branch -M main
3. git push -u origin main

API REST:

- Arquivo de configuração da aplicação e banco:
    - pg-back\src\main\resources\application.properties
    - pg-back\src\main\resources\application.dev.properties
    - pg-back\src\main\resources\application.prod.properties
    - pg-back\src\main\resources\application.test.properties

- Atualizar dependências do Maven
  
    1. mvn clean package
    2. mvn install

- Executar o Spring Boot App:

    1. pg-back\src\main\java\com\pequenosgenios\pg\PgApplication.java
    2. Run As
    3. Spring Boot App


- Swagger UI:
    - http://localhost:8080/swagger-ui/index.html#/
---
