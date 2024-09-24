# Gerenciador de Séries
Uma aplicação simples para gerenciar séries. Permite criar, listar, atualizar e deletar séries de uma base de dados.

## Tecnologias Utilizadas
- Node.js
- Express
- MongoDB
- Mongoose

## Funcionalidades 
- **Criar Série**: Adiciona uma nova série ao banco de dados.
- **Listar Séries**: Retorna todas as séries armazenadas.
- **Atualizar Série**: Modifica os dados de uma série existente.
- **Deletar Série**: Remove uma série do banco de dados.

## Pré Requisitos
Antes de rodar a apliação, certifique-se de ter:
- Node.js instalado
- MongoDB em execução

## Endpoints de API 
* GET /series - Retorna todas as séries.
* POST /series - Cria uma nova série.
* PUT /series/:id - Atualiza uma série existente.
* DELETE /series/:id - Deleta uma série pelo ID.

