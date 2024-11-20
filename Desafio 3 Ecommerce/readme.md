# Desafio de Modelagem de Banco de Dados e Implementação de Queries


## Descrição do Projeto Conceitual

Este repositório contém a modelagem do banco de dados de um sistema de e-commerce. O desafio consistiu em criar as tabelas necessárias para armazenar informações de clientes, produtos, pedidos, pagamentos e outros elementos do sistema, além de implementar a persistência de dados e consultas SQL para análise dos dados.

## Estrutura do Banco de Dados
O banco de dados foi modelado de forma a atender aos requisitos de um sistema de e-commerce. As principais tabelas do sistema incluem:

### person: 
Armazena as informações pessoais de clientes, fornecedores e vendedores.
### clients: 
Relaciona os clientes com suas informações de endereço e dados pessoais.
### supplier: 
Relaciona os fornecedores com as informações de pessoa.
### sellers: 
Relaciona os vendedores com as informações de pessoa.
### payments: 
Armazena os dados de pagamento realizados pelos clientes.
### product: 
Contém informações sobre os produtos disponíveis no sistema, como categoria, descrição e avaliação.
### stock: 
Armazena os dados de estoque dos produtos.
### productInStock: 
Relaciona os produtos com os estoques onde estão armazenados.
### orders: 
Contém as informações dos pedidos feitos pelos clientes.
### orderByProduct: 
Relaciona os produtos aos pedidos, incluindo a quantidade de cada produto no pedido.
### productBySellers: 
Relaciona os vendedores aos produtos que estão oferecendo.
## Persistência de Dados
Após a criação das tabelas no banco de dados, foram inseridos dados fictícios para realizar testes de integração entre as tabelas e garantir que as relações e constraints funcionem corretamente. Esses dados incluem informações de clientes, pedidos, pagamentos, produtos, estoques e vendas.

## Consultas SQL
Para análise e recuperação dos dados do sistema, foram criadas algumas consultas SQL. Abaixo estão alguns exemplos de consultas implementadas
