Modelagem de Dados Restaurante

Objetivo: Modelar um banco de dados para um restaurante 

Requisitos: 

    - O restaurante recebe pedidos de um cliente.
    - O cliente realiza um pedido ao restaurante.
    - O entregador realiza a entrega de um pedido.
    - O cliente deve morar apenas em uma cidade.
    - O cliente so pode morar em um Estado.
    - cada pedido deve possuir apenas uma forma de pagamento.
    - cada pedido deve ser feito por apenas um cliente.
    - cada cliente pode realizar varios pedidos.
    - o pedido deve ser entregue por apenas um entregador.
    - um entregador pode realizar várias entregas.
    - cada pedido deve ser feito a apenas um restaurante
    - um restaurante pode receber varios pedidos. 

    - Cada pedido deve conter :
        - Os item do pedido;
        - quantidade de itens;
        - O cliente que realizou o pedido; 
        - A data, mes, ano e hora do pedido; 
        - O endereco de entrega do pedido ;
        - O entregador que realizou a entrega; 
        - A forma de pagamento do pedido ;
        - O valor do pedido ;
        - status do pedido;
        - valor frete;
        - restaurante onde foi realizado o pedido;


    - Cada cliente deve conter:
        - CPF
        - Nome 
        - Sobrenome
        - Endereco 
        - Bairro
        - Cidade
        - Estado 
        - Numero 
        - Telefone
        - Celular
        - Email

    O entregador deve possuir os mesmos campos do cliente, além de:
        - RG
        - Veículo
        - Conta Bancária
    
    Os itens serao compostos de:
        - Descricao 
        - Categoria - opcional

    O restaurante possui os seguintes campos:
        - Descricao 
        - Endereco 
        - Numero
        - Cidade
        - Bairro 
        - Estado 

    A cidade deve conter:
        - Descricao 
    
    O Estado deve conter:
        - descricao 
        - UF 

    A forma de pagamento deve possuir:
        - descricao

    