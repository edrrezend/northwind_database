# Projeto de criação e exploração de banco de dados Northwind 

### Ambiente
Banco de dados northwind + S3 + Redshift.

## Etapas do projeto:
1. Criar cluster no Amazon Redshift.
2. Criar banco de dados Northwind.
3. Criar estrutura do banco de dados:
3.1. Rodar northwinddl.sql utilizando o editor de consultas do Redshift.
4. Criar credencias para Copy no IAM.
5. Fazer upload dos 8 arquivos CSV para um bucket o Amazon S3.
6. Executar Copy para carregar dados (copy.sql pode ser usado como modelo).

#### Observação:
Os números em vermelho podem possuir valores diferentes
![image](https://user-images.githubusercontent.com/124625776/228105376-62baae65-9967-4ee0-960c-fcf6c06de0b4.png)

#### Schema
![image](https://user-images.githubusercontent.com/124625776/228107867-ff39a924-79e1-43a6-a7f3-fee5c4f03e7b.png)

7. Explorar os dados

## Atividades realizadas:
1. Consultas para analisar se houve muitas vendas com valores abaixo do preço.

## Possíveis soluções:
As soluçôes se encontram nos arquivos "atividade.txt".
