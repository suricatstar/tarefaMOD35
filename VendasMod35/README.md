# VendasMod35

Sistema de gerenciamento de vendas desenvolvido em Java com JPA e JDBC.

## 📋 Descrição

Projeto modular implementando padrões DAO (Data Access Object) e Service para gerenciamento de:
- **Clientes**
- **Produtos**
- **Vendas**
- **Produtos por Quantidade**

## 🏗️ Arquitetura

### Camadas
- **Domain**: Entidades de negócio (`Cliente`, `Produto`, `Venda`, `ProdutoQuantidade`)
- **DAO**: Acesso a dados com implementações em JDBC e JPA
- **Service**: Lógica de negócio
- **Factory**: Padrão Factory para criação de objetos
- **Exceptions**: Exceções customizadas

### Padrões Implementados
- **GenericDAO**: Classe base para operações CRUD genéricas
- **Factory Pattern**: Para criar objetos de domínio
- **Service Layer**: Abstração da lógica de negócio
- **Singleton**: Gerenciamento de mapa único (SingletonMap)

## 🗄️ Banco de Dados

Configurado via JPA com arquivo `persistence.xml` para gerenciamento de entidades.

## 🧪 Testes

Suite de testes incluindo:
- DAOs (JDBC e JPA)
- Services
- Mocks para testes isolados

Execute via `AllTests.java`

## 🛠️ Tecnologias

- Java
- JPA (Java Persistence API)
- JDBC
- Unit Tests (JUnit)

---

*Desenvolvido no STS (Spring Tool Suite 4)*