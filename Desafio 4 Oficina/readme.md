# Sistema de Gerenciamento de Oficina Mecânica


## Descrição do Projeto Conceitual

Este repositório contém a modelagem do banco de dados de um sistema de gerenciamento de oficina mecânica. O desafio consistiu em criar as tabelas necessárias para armazenar informações de clientes, 
veículos, mecânicos, ordens de serviço, peças e serviços, além de implementar a persistência de dados e consultas SQL para análise e recuperação de informações.

## Estrutura do Banco de Dados
O banco de dados foi modelado de forma a atender aos requisitos de um sistema. As principais tabelas do sistema incluem:

### person: 
Armazena as informações básicas de pessoas relacionadas ao sistema, como nome e endereço.
### cliente: 
Armazena informações complementares dos clientes, como telefone e email. Relaciona-se à tabela
### veiculo: 
Registra os veículos dos clientes, com dados como modelo, placa e cor. Está associado à tabela cliente.
### mecanico: 
Armazena informações dos mecânicos da oficina, incluindo suas especialidades. Relaciona-se à tabela person.
### Equipe: 
Registra as equipes da oficina, que podem ser formadas por um ou mais mecânicos.
### Equipe_com_Mecanico: 
Faz a relação entre equipes e mecânicos, indicando quais mecânicos pertencem a cada equipe.
### Servico: 
Contém as informações dos serviços oferecidos pela oficina, como descrição, valor e tempo estimado.
### productInStock: 
Relaciona os produtos com os estoques onde estão armazenados.
### Peca: 
Armazena as peças disponíveis para os serviços, incluindo nome e preço.
### Ordem_de_servico: 
Registra todas as ordens de serviço emitidas pela oficina, com detalhes como descrição, status, datas de emissão e conclusão, valor total, veículo associado e equipe responsável.
### Ordem_de_servico_tem_servico: 
Relaciona ordens de serviço com os serviços realizados:
## Persistência de Dados
Após a criação das tabelas no banco de dados, foram inseridos dados fictícios para realizar testes de integração entre as tabelas e garantir que as relações e constraints funcionem corretamente. Esses dados incluem informações de clientes, pedidos, pagamentos, produtos, estoques e vendas.

## Consultas SQL
Para análise e recuperação dos dados do sistema, foram criadas algumas consultas SQL. Abaixo estão alguns exemplos de consultas implementadas
