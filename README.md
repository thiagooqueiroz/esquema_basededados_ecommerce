# esquema_basededados_ecommerce
Esquema de base de dados para e-commerce
Objetivo
1 - PJ ou PF - Entidades separadas e relacionadas de acordo com ID  do cliente, onde o mesmo nao pode haver um cadastro simultaneo de CPF ou CNPJ;
2 - Modo de pagamento (cartao) - Entidade onde estara relacionada de acordo com o registro do usuario (CPF/CNPJ), relacionando dados do cartão;
3 - Entrega - Entidade relacionada de acordo com produtos em vez de pedidos, devido a um pedido haver varios produtos e os mesmos serem de fornecedores diferentes. Logo, terao entregas diferentes;
