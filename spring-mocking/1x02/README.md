# 📌 Projeto: Spring Mocking com Mockito

Este projeto faz parte do exercício da Task 0 e tem como objetivo **criar um serviço de gerenciamento de usuários** e **testar suas funcionalidades utilizando Mockito** para simular a camada de persistência.

---

## 📂 Estrutura do Projeto
spring-mocking/1x02/ ├── pom.xml ├── README.md ├── src │   ├── main │   │   └── java │   │       └── com/example/demo │   │           ├── model/Usuario.java │   │           ├── repository/UsuarioRepository.java │   │           └── service/UsuarioService.java │   └── test │       └── java │           └── com/example/demo/service/UsuarioServiceTest.java

---

## 🧩 Componentes

- **Usuario (model)**  
  Representa um usuário no sistema com atributos 'id', 'nome' e 'email'.

- **UsuarioRepository (repository)**  
  Interface que define operações de acesso a dados ('findById', 'save').

- **UsuarioService (service)**  
  Implementa a lógica de negócios para manipulação de usuários.  
  - 'buscarUsuarioPorId(Long id)' → retorna usuário ou lança exceção.  
  - 'salvarUsuario(Usuario usuario)' → salva e retorna o usuário.

- **UsuarioServiceTest (test)**  
  Testa a classe 'UsuarioService' utilizando **Mockito**.  
  - 'deveRetornarUsuarioQuandoIdExistir()'  
  - 'deveLancarExcecaoQuandoUsuarioNaoExistir()'  
  - 'deveSalvarUsuarioComSucesso()'

---

## ⚙️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3.1.0**
- **JUnit 5**
- **Mockito 5**

---

## ▶️ Como Executar os Testes

1. Certifique-se de ter o **Maven** instalado.
2. Na raiz do projeto ('spring-mocking/1x02/'), execute:

'''bash
mvn test
