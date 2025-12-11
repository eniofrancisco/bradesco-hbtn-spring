# Projeto Spring Mocking - ProdutoService

Este projeto demonstra como utilizar **Mockito** em conjunto com o **Spring Boot** para criar testes unitários que simulam o comportamento de dependências.  
O exemplo implementa um serviço simples de produtos () que depende de um repositório ().

## Estrutura do Projeto
spring-mocking/1x01/ ├── src/ │   ├── main/ │   │   ├── java/com/example/demo/model/Produto.java │   │   ├── java/com/example/demo/repository/ProdutoRepository.java │   │   └── java/com/example/demo/service/ProdutoService.java │   └── test/ │       └── java/com/example/demo/service/ProdutoServiceTest.java └── pom.xml


## Tecnologias Utilizadas
- **Java 17**
- **Spring Boot 3.4.12**
- **Spring Data JPA**
- **H2 Database** (runtime)
- **JUnit 5**
- **Mockito**

## Funcionalidade
O serviço  possui o método:

'''java
public Produto buscarPorId(Long id)

## Repositório

GitHub repository: bradesco-hbtn-spring
Directory: spring-mocking/1x01
