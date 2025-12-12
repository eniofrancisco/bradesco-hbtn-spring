# 📦 Spring MVC - Catálogo de Produtos

Este projeto é uma aplicação **Spring Boot MVC** simples para gerenciar um catálogo de produtos.  
Ele expõe uma API REST que permite **listar, adicionar, atualizar e deletar produtos**.

---

## 🚀 Endpoints da API

### 1. Listar Produtos
**GET** 'http://localhost:8080/api/produtos'

### 2. Adicionar Produto
**POST** 'http://localhost:8080/api/produtos'
Content-Type: application/json
'''json
{
  "nome": "Celular",
  "preco": 1999.99
}
