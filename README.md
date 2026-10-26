# Sistema-Gestão-Pedidos
Sistema de Gestão de Pedidos

# 🛒 Sistema de Gestão de Pedidos

API REST desenvolvida em Java e Spring Boot para gestão de pedidos de vendas, criada como projeto prático da disciplina de Programação Web / Laboratório de Software.

## Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database** (Banco de dados em memória)
- **Validation** (Validação de dados de entrada)
- **Swagger / OpenAPI 3.0** (Documentação interativa)

## Funcionalidades da API

- `POST /pedidos` - Cria um novo pedido com validação de campos.
- `GET /pedidos` - Lista todos os pedidos cadastrados.
- `GET /pedidos/{id}` - Busca os detalhes de um pedido específico por ID.
- `PUT /pedidos/{id}` - Atualiza as informações de um pedido existente.
- `DELETE /pedidos/{id}` - Remove um pedido do sistema.

## Como Executar o Projeto Localmente

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/Eduardamacedo01/Sistema-Gest-o-Pedidos.git](https://github.com/Eduardamacedo01/Sistema-Gest-o-Pedidos.git)
