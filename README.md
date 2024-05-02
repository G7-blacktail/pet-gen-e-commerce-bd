# Diagrama para pedidos de um Petshop

Neste projeto eu criei um Diagrama Entidade relacionamento para conceituar o banco de dados de um e-commerce voltado para produtos de pet-shop.

No diagrama relacional fiz a seguinte implementação:

Criei uma entidade relacionando o cliente, a forma de pagamento e o pedido chamado cleinte_has_formas de pagamento para refletir a escolha do cliente (como deseja pagar ao pedido). Para definir se o cliente é cnpj ou cpf usei algo simples que geralmente estou usando em projetos práticos em minha impressa para definir isto: que é um atributo nr_documento deixando a filtragem para o backend definir se é um cnpj ou cpf (esta prática me foi passada por um desenvolvedor sênior).

Para entrega defini que ela tem a relação com pedido de 1 : 1, colocando o código, status e a FK do Id_pedido, deixando o valor do frete dentro da entidade pedido.

Nas demais entidades apenas coloquei atributos que achei necessário para um cenário real, porém sem ir muito a fundo abstraindo o que achei essenssial no momento.
