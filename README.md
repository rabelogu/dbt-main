# Modern Data Stack Project


## O objetivo desse projeto é criar um pipeline completo, utilizando ferramentas atuais de mercado como Snowflake, DBT e PowerBI.

### Requirements:

O pipeline foi desenvolvido utilizando plataformas cloud, sendo assim é necessario contas de acesso nos seguintes ambiente:

- Snowflake
- DBT

Além disso é necessário um desktop com acesso ao snowflake configurado. para acesso da plataforma PowerBI Desktop

### WAREHOUSE:

#### View's de origem:
   ##### STG_TPCH_SF1__CUSTOMER

![GET](images/customer.png)

   ##### STG_TPCH_SF1__NATION

![GET](images/nation.png)

   ##### STG_TPCH_SF1__REGION

![GET](images/region.png)

##### Tabela dimensão para load

   ##### DIM_CUSTOMER


![GET](images/dim01.png)


### Transformação:
 
     dim_customer.sql

![GET](images/flow.png)
    
    Logs:


![GET](images/execute.png)

### Usando PowerBI e Snowflake para visualização dos dados

   ### Adicionando a conexão

![GET](images/PBI1.png)

![GET](images/PBI2.png)

![GET](images/PBI3.png)

![GET](images/PBI4.png)

   ### Transformando os dados e modelando o dashboard

![GET](images/PBI5.png)

