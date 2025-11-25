# Cash

## 1. Objetivo do trabalho

Criação de um software de gerenciamento financeiro com auxilio de IA para categorização de transações e geração de análises.

## 2. Pastas

- `backend`: Contém o servidor REST para a conversa entre os sistemas de banco de dados e o frontend;
- `frontend`: Contém a página WEB que auxiliará na inserção de dados e no uso da IA.
- `gateway-api`: Contém o servidor Gateway de microsserviços para enviar e receber dados de uma fila RabbitMQ. 
- `ia`: Contém a lógica generativa de análise e categorização de transações.

## 3. Requisitos

- Docker
- WSL (Somente Windows)

## 4. Como rodar

Inclua as informações no `.env` seguindo o template `.env.template`. (Para o contexto atual, o .env será disponibilizado) 

Vá em `backend/` e abra o arquivo `run.sh`. 
Siga as recomendações que contém dentro do arquivo.

Após isso, rode o comando `docker compose up --build`.
