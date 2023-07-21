# Projeto web services com Spring Boot e JPA / Hibernate 

## Tem como objetivo:

### - Criar um projeto Spring Boot Java 

### - Implementar o modelo de domínio
  ![Domain Model](https://github.com/LucasRafaell/springboot3-jpa/assets/99283985/f8dc74ce-4a7e-4989-8f4c-6d23e480322e) 
  
### - Estruturar o projeto por meio de camadas lógicas: Resource, Service e Repository
  ![Logical Layers](https://github.com/LucasRafaell/springboot3-jpa/assets/99283985/ad888b52-e3fc-4378-8620-57c947412d43)
  
  <p><b>Resource</b>: são controladores da interface com o backend, recebendo requisições e respondendo-as de acordo com o comportamento do sistema.</p>
  <p><b>Service</b>: contém a lógica e regras de negócio da aplicação, processa as solicitações vindas da camada de resource e executa açòes específicas, manipula os dados e coordena as interações com a camada repository, com o intuito de buscar ou armazenar informações na base de dados.</p>
  <p><b>Repository</b>: responsávle comunicaçào direta com a base de dados, oferecendo uma abstração dos dados para o acesso, permitindo que a camada service manipule os dados sem se preocupar como os dados serão buscados ou armazenados.</p>
  
### - Configurar banco de dados de teste (H2)
  ![h2](https://github.com/LucasRafaell/springboot3-jpa/assets/99283985/be7ad659-f9b2-4949-bbb0-777e878a5895)
  
### - CRUD – Create, Retrieve, Update, Delete

### - Tratamento de exceções

### - Instancia de Objetos para criar a base de dados de forma automática e em seguida povoar com uma carga de dados inicial
   ![Domain Instance](https://github.com/LucasRafaell/springboot3-jpa/assets/99283985/f403df2f-2078-4166-a434-23f87d037a8b)
  
### Linguagem, framework e ferramentas utilizadas
<div style="display: inline_block">
  <img align="center" alt="Java" height="70" width="70"
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" />
  <img align="center" alt="Spring" height="70" width="70"
src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original-wordmark.svg" />  
  <img align="center" alt="Spring" height="70" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tomcat/tomcat-original.svg" />  
  <img align="center" alt="Spring" height="70" width="70"
  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />  
  <img align="center" alt="Spring" height="70" width="70"
  src="https://github.com/LucasRafaell/springboot3-jpa/assets/99283985/be7ad659-f9b2-4949-bbb0-777e878a5895" /> 
  
  <p>Java, Spring Boot, Apache Tomcat, Postegres, H2, Postman e Maven</p>
</div>
  
  
