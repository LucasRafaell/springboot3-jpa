# Projeto web services com Spring Boot e JPA / Hibernate 

## Tem como objetivo:

### - Criar um projeto Spring Boot Java 

### - Implementar o modelo de domínio
  ![Domain Instance](https://github.com/LucasRafaell/springboot3-jpa/assets/99283985/f403df2f-2078-4166-a434-23f87d037a8b)
  
### - Estruturar o projeto por meio de camadas lógicas: Resource, Service e Repository
  image
  <p>Resource: são controladores da interface com o backend, recebendo requisições e respondendo-as de acordo com o comportamento do sistema.</p>
  <p>Service: contém a lógica e regras de negócio da aplicação, processa as solicitações vindas da camada de resource e executa açòes específicas, manipula os dados e coordena as interações com a camada repository, com o intuito de buscar ou armazenar informações na base de dados.</p>
  <p>Resource: responsávle comunicaçào direta com a base de dados, oferecendo uma abstração dos dados para o acesso, permitindo que a camada service manipule os dados sem se preocupar como os dados serão buscados ou armazenados.</p>
  
### - Configurar banco de dados de teste (H2)
  image
  
### - CRUD – Create, Tetrieve, Update, Delete

### - Tratamento de exceções

### - Instancia de Objetos para criar a base de dados de forma automática e em seguida povoar com uma carga de dados inicial
  image
  
### Linguagem, framework e ferramentas utilizadas
  <p>Java, Spring Boot, Apache Tomcat, Maven, H2, Postman e Postegres</p>
  image
