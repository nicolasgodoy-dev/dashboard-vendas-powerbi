# Dashboard de Vendas no Power BI

Projeto de estudo: um dashboard de vendas feito no Power BI, a partir de uma base de dados de aula (dados fictícios). Fiz este projeto acompanhando o vídeo do canal [Ricardo Andrade | Carreira em Dados](https://www.youtube.com/@euricardoandrade1):

🎥 [Vídeo usado como guia](https://www.youtube.com/watch?v=mbwCYU-b1U8)

## Objetivo

Praticar o caminho completo de uma análise de dados: organizar as tabelas, criar cálculos, montar os gráficos e deixar o painel interativo e com visual profissional.

## O que o dashboard mostra

- **Indicadores (cartões):** Faturamento Total, Quantidade Vendida e Ticket Médio
- **Gráfico de linha:** evolução do faturamento ao longo do tempo
- **Gráficos de colunas:** vendas por categoria, por região e por vendedor
- **Filtros (segmentações de dados):** vendedor, categoria, região, produto e período

## Dados

A base está em `Base_Vendas_Aula_PowerBI.xlsx`, com quatro tabelas:

| Tabela | Conteúdo |
|---|---|
| Vendas | Registros de venda: data, cliente, produto, vendedor, quantidade e preço unitário |
| Clientes | Nome, cidade, estado e segmento |
| Produtos | Nome, categoria e custo |
| Vendedores | Nome e região |

A tabela de Vendas fica no centro e se relaciona com as outras três.

> Os dados são fictícios e servem apenas para estudo.

## O que aprendi

- Organizar os dados em tabelas relacionadas (tabela de vendas no centro, ligada a clientes, produtos e vendedores)
- Criar medidas com **DAX** (Faturamento Total, Quantidade Vendida e Ticket Médio)
- Escolher o gráfico certo para cada pergunta (cartões, linha e colunas)
- Deixar o painel interativo com segmentações de dados
- Cuidar do visual, com um fundo escuro personalizado para um acabamento profissional

## Ferramentas

- Power BI Desktop
- Excel (base de dados)

## Como abrir o projeto

1. Baixe o arquivo `ProjetoPowerBI.pbix` e abra no Power BI Desktop.
2. Se o Power BI pedir, aponte a fonte de dados para o arquivo `Base_Vendas_Aula_PowerBI.xlsx` (em **Transformar dados → Configurações da fonte de dados**).

## Estrutura do repositório

```
├── ProjetoPowerBI.pbix
├── Base_Vendas_Aula_PowerBI.xlsx
└── README.md
```

## Autor

**Nicolas Eduardo de Godoy**
Estudante de Tecnologia da Informação (UNIVESP) · GitHub: [nicolasgodoy-dev](https://github.com/nicolasgodoy-dev)