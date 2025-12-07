# Análise de Funil de Vendas — SQL + Excel

Este projeto traz uma análise de funil de vendas utilizando SQL para extração e consolidação dos dados e Excel para criação de um dashboard visual com as principais métricas de negócio.

O objetivo é acompanhar a jornada dos leads até a conversão em vendas, entender o desempenho por mês e destacar as marcas, lojas e dias da semana mais relevantes.

---

## 📊 Visão Geral do Dashboard

O dashboard em Excel apresenta:

- **Receita mensal (k, R$)**
- **Leads (#)** e **taxa de conversão (%)**
- **Ticket médio (k, R$)**
- **Top 5 marcas mais vendidas**
- **Top 5 lojas que mais venderam**
- **Visitas ao site por dia da semana**
- Mapa com **estados que mais venderam no mês**

![Dashboard de funil de vendas](https://raw.githubusercontent.com/alanbernardo/analise-funil-vendas-sql-excel/main/Painel%20de%20controle.png)


---

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
