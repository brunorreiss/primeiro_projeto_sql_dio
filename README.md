# Projeto de Banco de Dados para E-commerce

Este é um projeto de modelagem de banco de dados para um cenário de e-commerce. O objetivo é criar um esquema lógico que represente as diferentes entidades e relacionamentos envolvidos em um sistema de e-commerce, além de escrever consultas SQL para realizar diversas operações.

## Modelo Lógico

O esquema lógico do banco de dados foi criado considerando as informações do cenário de e-commerce, incluindo a adição dos pontos refinados no desafio:

- Cliente PJ e PF
- Pagamento
- Entrega

A seguir, estão as principais tabelas do banco de dados:

- Cliente
- Conta
- Produto
- Fornecedor
- Estoque
- FormaPagamento
- Pedido
- ItemPedido
- Entrega

## Script SQL

O script SQL `create_tables.sql` contém os comandos para criar as tabelas do banco de dados, definindo as chaves primárias, estrangeiras e constraints necessárias.

## Consultas SQL

O arquivo `queries.sql` contém uma série de consultas SQL que abordam diferentes aspectos do cenário de e-commerce, incluindo recuperações simples, filtros, expressões, ordenações, condições de filtro aos grupos e junções entre tabelas.

## Como Executar

1. Execute o script `create_tables.sql` em um banco de dados compatível (ex: MySQL, PostgreSQL) para criar as tabelas.
2. Insira os dados de exemplo nas tabelas para realizar os testes das consultas.
3. Execute as consultas presentes no arquivo `queries.sql` para obter os resultados desejados.

## Perguntas de Negócio

Aqui estão algumas perguntas de negócio que podem ser respondidas usando as consultas SQL:

- Quantos pedidos foram feitos por cada cliente?
- Existe algum vendedor que também é fornecedor?
- Qual é a relação de produtos, fornecedores e estoques?
- Qual é a relação de nomes dos fornecedores e nomes dos produtos?

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para sugerir melhorias, correções ou adições ao projeto.

## Autor

[Bruno Reis]

