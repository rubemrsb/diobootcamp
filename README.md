# diobootcamp

Temos um ou mais produtos que possui um ou mais fornecedores com cnpj como  chave primária e nome como atributo simples;
Um produto ou mais pode ser vendido por diferentes terceiros também cadastrados com cnpj como chave primária e tendo razão social e endereço como atributos simples;
Os produtos também estão ligados a um ou mais estoques, tendo a quantidade como atrbiuto dessa ligação, assim como na transação de venda com terceiros e pedidos;
Já no item Cliente, foi utilizada uma generalização o cliente com os atributos gerais (cadastro, endereço e e-mail) e foram criadas duas subclasses para clientes com Cnpj e CPF, como foi requisitado;
O pedido que tem relação com o cliente possui em seus atributos, data (para efeito de garantia), status (aprovado ou cancelado), Frete (valor de acordo com o endereço do cliente), Status da entrega (atrasado, finalizado, dentro do prazo), código de rastreio e a chave estrageira o cliente (CPF ou CNPJ).
Além de estar ligado ao produto em uma relação de muitos para muitos, onde pode haver varios produtos em um pedido, como um produto pode estar em diferentes pedidos.
