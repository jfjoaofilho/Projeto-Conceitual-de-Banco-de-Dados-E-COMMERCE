# Projeto Conceitual de Banco de Dados – E-COMMERCE

## Descrição:
O Projeto Conceitual de Banco de Dados para um E-commerce tem como objetivo modelar os dados necessários para o funcionamento de uma plataforma de vendas online, garantindo a organização, consistência e integridade das informações. O modelo foi desenvolvido com base no Modelo Entidade-Relacionamento Estendido (EER), contemplando as principais entidades e relacionamentos do domínio do problema, de forma a atender às necessidades do negócio.
(Imagem - ERR_E-COMMERCE)

## Entidades Principais
### Narrativa: Produto
- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);
- Cada produto possui um fornecedor;
- Um ou mais produtos podem compor um pedido.
### Narrativa: Cliente
- O cliente pode se cadastrar no site com seu CPF ou CNPJ;
- O endereço do cliente irá determinar o valor do frete;
- Um cliente pode comprar mais de um pedido. Este tem um pedido de carência para devolução do produto.
### Narrativa: Pedido
- O pedido são criados por clientes e possuem informações de compra, endereço e status da entrega;
- Um produto ou mais compoem o pedido;
- O pedido pode ser cancelado.

Este projeto conceitual é a base para a criação do esquema lógico e implementação física do banco de dados, sendo essencial para o sucesso da plataforma de e-commerce.
