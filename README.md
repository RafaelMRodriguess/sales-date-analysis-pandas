# Análise de Vendas com Pandas

Projeto simples de análise de dados feito com Python e Pandas.

O objetivo foi praticar importação, limpeza, tratamento e análise de uma base fictícia de vendas online.

## Sobre o Projeto

Neste projeto, foi utilizada uma base de dados de vendas com informações sobre clientes, produtos, categorias, cidades, formas de pagamento, status da venda e avaliações.

A análise foi feita em um notebook Jupyter/Google Colab, utilizando a biblioteca Pandas.

## O que foi praticado

- Importação de arquivo CSV
- Verificação de dados nulos
- Tratamento de valores ausentes
- Conversão de datas
- Padronização de textos
- Criação de novas colunas
- Filtros com `query()`
- Agrupamentos com `groupby()`
- Uso de `agg()`
- Ordenação com `sort_values()`
- Criação de rankings
- Exportação de filtros para arquivos CSV

## Colunas da Base de Dados

A base possui colunas como:

- `data_venda`
- `cliente`
- `produto`
- `categoria`
- `cidade`
- `estado`
- `quantidade`
- `preco_unitario`
- `forma_pagamento`
- `status`
- `avaliacao`

## Principais Tratamentos Realizados

Foram feitos tratamentos como:

- Conversão da coluna `data_venda` para o formato de data
- Limpeza e conversão da coluna `preco_unitario`
- Padronização de textos nas colunas
- Verificação de valores nulos
- Criação da coluna `faturamento`


## Filtros Criados

Foram criados filtros para analisar partes específicas da base.

Eles são gerados pelo notebook e salvos na pasta:

```text
resultados/filtros/
```

## Análises Realizadas

Algumas análises feitas no projeto:

- Faturamento total por categoria
- Faturamento por cliente
- Quantidade vendida por produto
- Média de venda por forma de pagamento
- Maior venda por cidade
- Total de vendas por mês
- Top 5 clientes que mais compraram
- Top 5 produtos mais vendidos
- Categorias com maior faturamento
- Cidades com maior volume de vendas

## Estrutura do Projeto

```text
sales-date-analysis-pandas/
├── data/
│   └── vendas_online.csv
├── resultados/
│   └── filtros/
│       └── .gitkeep
├── Vendas_online_pandas.ipynb
└── README.md
```

## Observação sobre os Resultados

A pasta `resultados/filtros/` foi criada para armazenar os arquivos CSV gerados pelos filtros.

Os arquivos filtrados podem ser criados automaticamente ao executar o notebook.

## Tecnologias Utilizadas

- Python
- Pandas
- Jupyter Notebook
- Google Colab
- CSV
- GitHub

## Como Executar

Clone o repositório:

```bash
git clone https://github.com/RafaelMRodriguess/sales-date-analysis-pandas.git
```

Acesse a pasta do projeto:

```bash
cd sales-date-analysis-pandas
```

Abra o notebook:

```bash
jupyter notebook Vendas_online_pandas.ipynb
```

Ou abra o arquivo diretamente no Google Colab.

## Autor

- Rafael Machado Rodrigues.
