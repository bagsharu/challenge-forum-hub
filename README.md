# Fórum Hub

Forum Hub é uma **API Rest** para o gerenciamento de tópicos e discussões, desenvolvida como parte do challenge promovido pela **Alura** em parceria com o programa **Oracle Next Education**.

---

## Funcionalidades

### Cadastro de Tópicos
Permite registrar novos tópicos, validando a unicidade de título e mensagem.

### Listagem de Tópicos
Lista tópicos registrados no sistema, com suporte a paginação e ordenação.

### Detalhamento de Tópico
Permite visualizar informações detalhadas de um tópico por meio de seu ID.

### Atualização e Exclusão
- Atualização de informações existentes.
- Exclusão lógica de tópicos, marcando-os como inativos.

### Autenticação JWT
Garantia de que apenas usuários autenticados possam acessar os endpoints protegidos.

---

## Tecnologias Utilizadas

- **Linguagem:** Java 17
- **Framework:** Spring Boot (versão 3.3.5)
- **Banco de Dados:** MySQL, com gerenciamento de migrações via Flyway
- **Gerenciamento de Dependências:** Maven
- **Validação e Segurança:** Spring Validation e Spring Security
- **Autenticação:** Implementada com JWT (Java Web Token)
- **Documentação:** Gerada automaticamente usando Springdoc OpenAPI

---

## Dependências

A configuração completa está disponível no arquivo pom.xml, mas aqui estão as principais dependências utilizadas:

- **Spring Boot Starter Web:** Para desenvolvimento de APIs REST.
- **Spring Boot Starter Data JPA:** Para manipulação de dados no banco de dados.
- **Spring Boot Starter Validation:** Para validações dos dados.
- **Spring Boot Starter Security:** Para configuração de autenticação e autorização.
- **Flyway:** Para migração e versionamento de banco de dados.
- **Lombok:** Para redução de código boilerplate.
- **Springdoc OpenAPI:** Para geração de documentação interativa da API.
- **MySQL Connector:** Para conexão com o banco de dados.


---
### Configuração do Banco de Dados

Certifique-se de criar um banco de dados MySQL e configurar as credenciais no arquivo `application.properties`:

É necessário configurar as variáveis locais em seu sistema operacional:

- DB_USER : Seu usuário no banco de dados
- DB_PASS : Sua senha de acesso ao banco de dados

---

## 🛠️ Sugestão de Testes com Insomnia
Recomenda-se o uso do **Insomnia** para realizar os testes dos endpoints da API, configurando as variáveis de ambiente para facilitar as requisições e utilizando o token JWT para autenticação nos endpoints protegidos.

---


### Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests com sugestões de melhorias.

