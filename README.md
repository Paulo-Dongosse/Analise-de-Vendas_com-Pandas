# 📊 Análise de Vendas — Projeto Completo em Python + Jupyter Notebook

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.5+-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualização-red)
![PowerBI](https://img.shields.io/badge/Extensível-para%20Power%20BI-purple)
![Licença](https://img.shields.io/badge/Licença-MIT-lightgrey)

Este projeto apresenta uma análise completa de dados de vendas utilizando **Python**, **Pandas**, **Matplotlib** e **Jupyter Notebook**, com foco em métricas essenciais para decisões estratégicas.  
O objetivo foi transformar uma base de dados bruta em **informações claras**, **gráficos prontos**, **indicadores de desempenho** e um **mini dashboard dentro do próprio notebook**.

O projeto segue uma linha semelhante ao que empresas de varejo e e-commerce aplicam no dia a dia para monitorar faturamento, lucratividade e comportamento de vendas.

---

﻿<div align="center">
<table align="center">
<tr>
<td><img src="faturamento_total.png" width="350"/></td>
<td><img src="evolucao_das_vendas_mensais.png" width="350"/></td>
</tr>
<tr>
<td><img src="faixa_etaria_receita_media.png" width="350"/></td>
<td><img src="top10.png" width="350"/></td>
<tr>
<td><img src="Lucro_por_produto.png" width="350"/></td>
</tr>
</table>

</div>
---


---

## 🎯 Objetivos do Projeto

- Processar um dataset de vendas com Python.
- Gerar métricas relevantes (faturamento, lucro, ticket médio, etc.).
- Criar gráficos profissionais usando Matplotlib.
- Construir um dashboard simples direto no Jupyter Notebook.
- Visualizar padrões e apoiar decisões estratégicas.
- Demonstrar domínio de bibliotecas de análise de dados.

---

## 🧠 O que foi feito na análise

### ✔️ 1. Carregamento e limpeza dos dados  
- Leitura da base de vendas em CSV/Excel.  
- Correção de tipos (datas, números, categorias).  
- Tratamento de valores ausentes e inconsistências.  
- Criação de colunas derivadas (lucro, margem, ano/mês, etc.).

### ✔️ 2. Exploração inicial (EDA – Exploratory Data Analysis)  
- Quantidade total de pedidos.  
- Número de lojas e produtos distintos.  
- Distribuição de vendas por período.  
- Comportamento de faturamento mensal.

### ✔️ 3. Construção das métricas principais  
As principais métricas calculadas foram:

- **Faturamento total**  
- **Lucro total**  
- **Margem por produto**  
- **Produtos mais vendidos**  
- **Top 10 produtos que mais geram lucro**  
- **Desempenho por loja**  
- **Sazonalidade mensal/anual**

### ✔️ 4. Criação dos gráficos  
Foram gerados gráficos salvos automaticamente em `.png`, incluindo:

- Faturamento por loja  
- Margem por produto  
- Top 10 produtos com maior lucro  
- Evolução das vendas mensais  

### ✔️ 5. Construção de um mini dashboard no Notebook  
Usando apenas:
```python
from IPython.display import Image, display

# Analise-de-Vendas_com-Pandas
# Analise-de-Vendas_com-Pandas
