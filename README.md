# Ecommerce - SQL - DIO challenge

![GitHub repo size](https://img.shields.io/github/repo-size/Wanderson-Fer/Ecommerce---SQL---DIO-Challenge?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/Wanderson-Fer/Ecommerce---SQL---DIO-Challenge?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Wanderson-Fer/Ecommerce---SQL---DIO-Challenge?style=for-the-badge)

## Proposta

Mapear um ER e, a partir deste, gerar o esquema SQL para a criação do BD. Realizar a inserção de valores e recuperar essas informações com queries DML pensadas para responder "perguntas".

1. Mapeamento do esquema ER para Relacional
2. Definição do script SQL para criação do esquema de banco de dados
3. Persistência de dados para testes
4. Recuperação de informações com queries SQL

## Diagrama EER

![Diagrama EER](img/EER%20Model.png)

A imagem mostra um diagrama EER de um banco de dados que envolve as seguintes entidades: produtos, fornecedores, clientes, pedidos, pagamentos e vendedores. Cada entidade tem seus atributos listados abaixo do nome da entidade. Por exemplo, a entidade produtos tem os atributos *IdProduct*, *Pname*, *Classification_kids*, *Category*, *Rating*, *Size* e *Price*.

Os relacionamentos entre as entidades são representados por linhas que ligam as entidades. Cada relacionamento tem uma cardinalidade que indica quantas instâncias de cada entidade estão envolvidas no relacionamento. Por exemplo, o relacionamento entre a entidade *product* e a entidade *productOrder* e tem a cardinalidade 1:N, o que significa que um produto pode estar em vários pedidos, mas cada pedido só contem uma vez determidado produto.

Vale ressaltar que esse diagrama teve seus relacionamentos N:M expandidos em novas entidades para representar como as tabelas estarão no Banco de Dados, afim de aumentar a fidelidade ao Esquema SQL.

## Perguntas abordadas

- Quantos clientes temos?
    
    ![Quantidade de clientes](img/QuantityClients.png)

- Quais pedidos foram feitos por quais clientes?

    ![Pedidos por Clientes](img/OrdersByClients.png)

- Quanto cada cliente gastou com frete?

    ![Soma de Frete por Cliente](img/FreightSumByClient.png)

- Quantos pedidos foram realizados?

    ![Contagem de pedidos](img/OrderCount.png)

- Qual a quantidade de pedidos 'Em processamento' em contrapartida aos 'Confirmado's?

    ![Contagem de pedidos por status](img/CountOrderByStatus.png)

- Qual a quantidade de pedidos por Categoria de produto?

    ![Pedido por categoria](img/OrderByCategory.png)

- Qual(is) a(s) forma(s) de pagamento mais usada(s)?

    ![Contagem do tipo de pagamento](img/CountTypePayment.png)

- Que tipo de pagamento cada cliente tem?

    ![Tipo de pagamento por cliente](img/TypePaymentByClient.png)

- Qual o Limite médio que cada cliente tem?

    ![Limite médio por cliente](img/AverageLimitByClient.png)

- Qual é o produto mais vendido?

    ![Quantidade de produtos vendidos](img/SoldCountByProduct.png)

- Qual o produto com menor quantidade nos estoques?

    ![Quantidade de produtos em estoque](img/QuantitySumByProduct.png)

- Qual o produto com menor quantidade em determinado estoque?

    ![Quantidade de produtos em _](img/QuantitySumInto_.png)

- Qual a categoria de produto que cada fornecedor oferece?

    ![Categoria de produto por fornecedor](img/ProductCategoryBySuplier.png)

- Quais os fornecedores de 'Eletrônico's?

    ![Fornecedores de eletrônicos](img/EletronicSupliers.png)

- Quanto foi gasto com frete?

    ![Soma do frete](img/FreightSum.png)

- Qual a receita total gerada?

    ![Soma dos preços](img/PriceSum.png)

- Qual a receita gerada por cada produto?

    ![Soma dos preços por produto](img/PriceSumByProduct.png)

## Author

### Wanderson G. Fernandes
- [Instagram](https://instagram.com/locke._.wanderson?igshid=ZDc4ODBmNjlmNQ==)
- [LinkedIn](https://www.linkedin.com/in/wanderson-guedes-3138851aa)

## 📝 Licença

Esse projeto está sob licença MIT. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
