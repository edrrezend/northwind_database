## (ENGLISH)

# Northwind Database Creation and Exploration Project

### Environment:
Northwind database + S3 + Redshift + IAM.

## Project Steps:
1. Create a cluster on Amazon Redshift.
2. Create the Northwind database.
3. Create the database structure by running northwinddl.sql using the Redshift query editor.
4. Create credentials for Copy in IAM.
5. Upload the 8 CSV files to an Amazon S3 bucket.
6. Execute Copy to load data (copy.sql can be used as a template).

#### Note:
The numbers in red may have different values

![image](https://user-images.githubusercontent.com/124625776/228105376-62baae65-9967-4ee0-960c-fcf6c06de0b4.png)

#### Diagram:
![image](https://user-images.githubusercontent.com/124625776/228107867-ff39a924-79e1-43a6-a7f3-fee5c4f03e7b.png)

7. Explore the data 

## Activities performed:
1. Queries to analyze if there were many sales with values below the price. Also analyze the quantity of sales ordered by the difference.
2. Query to analyze the quantity of sales by the seller "Robert" in relation to the other sellers in the year 2022.
3. Query to analyze the top 10 most expensive products.
4. Query to analyze the sales progress of the year 2021 in relation to 2020. Analyze the difference in sales by supplier for these last 2 years.
5. Query to analyze the top selling categories per year (2020, 2021, and 2022), but only listing the top 5 for each year.

## Possible solutions:
The solutions are in the "atividade[n].txt" files.

## (PORTUGUÊS)

# Projeto de criação e exploração de banco de dados Northwind 

### Ambiente
Banco de dados northwind + S3 + Redshift + IAM.

## Etapas do projeto:
1. Criar cluster no Amazon Redshift.
2. Criar banco de dados Northwind.
3. Criar estrutura do banco de dados rodando northwinddl.sql utilizando o editor de consultas do Redshift.
4. Criar credencias para Copy no IAM.
5. Fazer upload dos 8 arquivos CSV para um bucket o Amazon S3.
6. Executar Copy para carregar dados (copy.sql pode ser usado como modelo).

#### Observação:
Os números em vermelho podem possuir valores diferentes
![image](https://user-images.githubusercontent.com/124625776/228105376-62baae65-9967-4ee0-960c-fcf6c06de0b4.png)

#### Diagrama
![image](https://user-images.githubusercontent.com/124625776/228107867-ff39a924-79e1-43a6-a7f3-fee5c4f03e7b.png)

7. Explorar os dados

## Atividades realizadas:
1. Consultas para analisar se houve muitas vendas com valores abaixo do preço. Também analisar a quantidade de vendas ordenadas pela diferença.
2. Consulta para analisar a quantidade de vendas do vendedor "Robert" em relação aos outros vendedores no ano de 2022.
3. Consulta para analisar quais os 10 produtos mais caros.
4. Consulta para analisar o progresso das vendas do ano de 2021 em relação a 2020. Analisar a diferença de vendas por fornecedor, das vendas desses últimos 2 anos.
5. Consulta para analisar as categorias mais vendidas por ano (2020, 2021 e 2022), porém só listando as 5 maiores de cada ano.

## Possíveis soluções:
As soluçôes se encontram nos arquivos "atividade[n].txt".
