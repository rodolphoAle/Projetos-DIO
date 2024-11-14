# Desafio de Projeto: Modelo Conceitual de Banco de Dados para Sistema de Vendas

## Descrição do Projeto Conceitual
O objetivo é modelar os principais elementos e relacionamentos do sistema, proporcionando uma estrutura que atenda às necessidades de cadastro, pagamento e entrega de produtos.
O esquema proposto inclui tabelas para armazenamento de informações de clientes, formas de pagamento e status de entrega. Esse banco de dados é projetado para um sistema que gerencia tanto clientes pessoa física (PF) quanto pessoa jurídica (PJ), garantindo que uma conta possa ser de apenas um tipo de cliente.
## Objetivo do Desafio
O desafio proposto pela expert visa aprimorar o modelo conceitual inicial, adicionando novas funcionalidades e refinando os elementos de dados. Os pontos de melhoria abordados são:
### Cliente PJ e PF:
O modelo agora inclui um relacionamento para que uma conta seja exclusivamente de pessoa física (PF) ou pessoa jurídica (PJ), garantindo a integridade de dados e uma diferenciação clara entre os tipos de clientes.
### Pagamento:
Uma nova entidade para o cadastro de múltiplas formas de pagamento associadas ao cliente, permitindo que o sistema registre e processe diversas opções, como cartão de crédito, boleto bancário, e PIX.
### Entrega: 
Foram adicionados atributos para status de entrega e código de rastreamento, oferecendo um controle detalhado do fluxo de entrega dos produtos e acompanhamento pelo cliente.
## Estrutura do Projeto
O projeto está dividido nas seguintes seções principais:
### Clientes: 
Inclui informações de cadastro dos clientes, distinguindo entre PF e PJ.
### Pagamentos: 
Tabela que permite o registro de diversas formas de pagamento.
### Entregas: 
Contém status e código de rastreamento, melhorando o acompanhamento dos pedidos.
