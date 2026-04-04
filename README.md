# 📊 Análise de Funil de Vendas — SQL + Excel

Este projeto apresenta uma análise de funil de vendas utilizando **SQL para extração e consolidação dos dados** e **Excel para construção de um dashboard interativo**, com foco em geração de insights para apoio à tomada de decisão.

O objetivo é acompanhar a jornada dos leads até a conversão em vendas, entender o desempenho ao longo do tempo e identificar padrões relevantes de comportamento.

---

## 🎯 Objetivos da Análise

- Monitorar a conversão de leads em vendas  
- Analisar a evolução da receita ao longo dos meses  
- Identificar marcas e lojas com melhor desempenho  
- Avaliar padrões de acesso ao site por dia da semana  
- Apoiar decisões estratégicas com base em dados  

---

## ⚙️ Processo de Dados (ETL)

- **Extração:** consultas SQL para obtenção de dados de vendas, leads e acessos  
- **Transformação:** tratamento e organização dos dados para análise  
- **Carga:** integração dos dados no Excel para construção do dashboard  

---

## 🛠️ Ferramentas Utilizadas

- SQL  
- Excel  
- Visualização de dados (Dashboard)  

---

## 📊 Visão Geral do Dashboard

O dashboard apresenta os seguintes indicadores:

- Receita mensal (R$)  
- Quantidade de leads (#)  
- Taxa de conversão (%)  
- Ticket médio (R$)  
- Top 5 marcas mais vendidas  
- Top 5 lojas com maior volume de vendas  
- Visitas ao site por dia da semana  
- Mapa com estados com maior volume de vendas  

---

## 📈 Principais Insights

- Identificação de períodos com maior conversão de leads  
- Destaque de marcas com maior participação na receita  
- Lojas com melhor desempenho comercial  
- Padrões de acesso ao site ao longo da semana  
- Oportunidades de melhoria na jornada de conversão  

---

<img width="856" height="329" alt="image" src="https://github.com/user-attachments/assets/107be527-00bb-42ab-b5af-89d63d078e30" />
----

## 🗂 Estrutura do Repositório

```text
analise-funil-vendas-sql-excel/
│
├── analise_funnel_sql_dashboard.xlsx   # Arquivo principal com as abas Dashboard, Resultados e Queries
├── Painel de controle.png              # Print do dashboard em Excel
└── sql/                                # Consultas SQL usadas na análise
    ├── query1_receita_leads_conversao.sql
    ├── query3_marcas_mais_vendidas.sql
    ├── query4_lojas_mais_vendidas.sql
    └── query5_visitas_por_dia_semana.sql


