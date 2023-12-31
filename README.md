# Projeto de Java Backend

Este é um projeto de backend em Java desenvolvido como parte do curso da EBAC. O projeto interage com um banco de dados PostgreSQL e realiza operações em tabelas como `tb_cliente`, `tb_produto`, `tb_produto_quantidade`, e `tb_venda`.

## Estrutura do Projeto

O projeto está organizado em vários pacotes:

- `dao`: Contém classes de acesso a dados para interagir com o banco de dados.
- `generic`: Contém classes genéricas para operações comuns de acesso a dados.
- `jdbc`: Classes relacionadas ao uso do JDBC para conexão com o banco de dados.
- `domain`: Classes de domínio que representam entidades de negócios, como `Cliente` e `Produto`.
- `exceptions`: Classes que representam exceções específicas do projeto.
- `services`: Classes de serviço que encapsulam a lógica de negócios.
- `test`: Contém testes unitários para validar o funcionamento das classes do projeto.

## Objetivo do Projeto

O objetivo principal deste projeto foi adicionar um novo campo às tabelas `tb_cliente` e `tb_produto` no banco de dados e realizar todas as modificações necessárias no código para acomodar essas alterações.

## Executando os Testes

Você pode executar os testes unitários para garantir que o projeto está funcionando corretamente. Aqui estão alguns dos testes disponíveis:

- `ClienteDAOTest`: Testes relacionados à classe `ClienteDAO`.
- `ProdutoDAOTest`: Testes relacionados à classe `ProdutoDAO`.
- `VendaDAOTest`: Testes relacionados à classe `VendaDAO`.
- `ClienteServiceTest`: Testes relacionados ao serviço de cliente.
- `ProdutoServiceTest`: Testes relacionados ao serviço de produto.

---



