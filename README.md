# Produtos API

Esta é uma API REST simples criada com Spring Boot para gerenciar produtos. A API permite realizar operações básicas de CRUD (Create, Read, Update, Delete) em produtos.

## Funcionalidades

- **Obter um produto por ID**: `GET /produtos/{id}`
- **Listar produtos por nome**: `GET /produtos?nome={nome}`
- **Criar um novo produto**: `POST /produtos`
- **Atualizar um produto existente**: `PUT /produtos/{id}`
- **Deletar um produto por ID**: `DELETE /produtos/{id}`

## Requisitos

- Java 21
- Maven 3.8 ou superior

## Configuração do Banco de Dados

Este projeto utiliza o banco de dados **H2** em modo embedded. Não é necessária nenhuma configuração adicional. As credenciais padrão estão definidas em `application.yaml`:
