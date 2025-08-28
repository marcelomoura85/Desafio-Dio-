🛒 Descrição do Projeto
Este repositório contém o modelo conceitual de banco de dados desenvolvido como parte de um desafio de projeto para um sistema de e-commerce. O objetivo é representar, de forma clara e escalável, os principais componentes envolvidos na operação de uma loja virtual, incluindo clientes, pedidos, produtos, pagamentos e entregas.

🎯 Objetivo
Modelar um esquema entidade-relacionamento (ER) que atenda aos seguintes requisitos:
- Dois tipos de clientes: Pessoa Física e Pessoa Jurídica, com atributos específicos para cada tipo.
- Registro de pedidos realizados por clientes, contendo múltiplos itens e associados a produtos.
- Suporte a múltiplas formas de pagamento por pedido, incluindo pagamento com dois cartões de crédito, Pix, boleto, entre outros.
- Registro de entregas associadas aos pedidos, com informações como transportadora, código de rastreio, tipo de frete e status da entrega.

🧩 Estrutura do Modelo
O modelo foi construído com base em boas práticas de modelagem de dados, utilizando especialização (herança) para representar os tipos de cliente e entidades associativas para flexibilizar os métodos de pagamento. A estrutura contempla:
- Entidade Cliente com especializações PessoaFisica e PessoaJuridica.
- Entidades Pedido e Produto para representar o fluxo de compra.
- Entidade Pagamento associada a múltiplas FormaPagamento, com especializações como CartaoCredito, Pix e Boleto.
- Entidade Entrega vinculada ao pedido, com rastreabilidade e controle de status.

📁 Conteúdo do Repositório
- README.md: Descrição do projeto e contexto.
- modelo_conceitual.png: Diagrama ER ilustrando o esquema
- https://github.com/marcelomoura85/Desafio-Dio-/blob/main/E-commerce.png


