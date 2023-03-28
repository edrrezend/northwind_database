# Projeto banco de dados Northwind 

## Resumo do projeto

### Ambiente
Banco de dados northwind + Amazon Redshift.

#### Etapas do projeto:
1. Criar cluster no Amazon Redshift.
2. Criar banco de dados Northwind.
3. Criar estrutura do banco de dados:
3.1. Rodar northwinddl.sql utilizando o editor de consultas do Redshift.
4. Criar credencias para Copy no IAM.
5. Fazer upload dos 8 arquivos CSV para um bucket o Amazon S3.
6. Executar Copy para carregar dados(copy.sql pode ser usado como modelo.
