# 👑 Análise de Segmentação de Clientes RFM | E-commerce 

[![Status](https://img.shields.io/badge/Status-Finalizado-success.svg)]()
[![Tecnologias](https://img.shields.io/badge/Tecnologias-Python%20%7C%20Looker%20Studio-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://opensource.org/licenses/MIT)

## 🎯 1. Resumo Executivo e Objetivo de Negócio

Este projeto foca na **Segmentação Estratégica de Clientes** de um varejo online para otimizar o investimento em marketing e combater o *churn* (abandono de clientes).

O objetivo foi transformar dados transacionais brutos em **Grupos de Valor** (Segmentos RFM), permitindo que a empresa passe de uma abordagem de marketing "um para todos" para uma estratégia focada e lucrativa.

---

## 💡 2. Problema e Metodologia (RFM)

### Problema
Em um ambiente de e-commerce competitivo, a maior parte da receita vem de um pequeno grupo de clientes. O desafio é identificar quem são esses clientes ("Campeões") e, mais crucialmente, **quais clientes estão prestes a sair** ("Hibernando") para criar campanhas de retenção antes que seja tarde.

### Metodologia: Análise RFM
Foi utilizada a metodologia **RFM** (Recência, Frequência e Valor Monetário) para pontuar cada cliente de 1 a 5, onde a combinação dessas pontuações cria os segmentos de negócio:

| Métrica | Definição | Interpretação |
| :--- | :--- | :--- |
| **R** (Recency) | Há quantos dias o cliente comprou pela última vez. | Quanto **menor** a Recência (comprou mais recentemente), **melhor**. |
| **F** (Frequency) | Quantidade total de compras realizadas. | Quanto **maior** a Frequência, **melhor**. |
| **M** (Monetary) | Valor total gasto pelo cliente. | Quanto **maior** o Valor Monetário, **melhor**. |

---

## 📊 3. Principais Resultados (Insights do Dashboard)

A análise da base de 4.338 clientes revelou a distribuição crítica de valor e risco:

| Segmento | Qtd. Clientes | Ticket Médio | Principal Insight |
| :--- | :--- | :--- | :--- |
| **04. Clientes Promissores** | 1.701 (39%) | \$1,093.31 | **Maior Grupo:** Oportunidade de aumentar a Frequência e convertê-los em Leais. |
| **07. Hibernando** | 1.505 (35%) | \$629.79 | **Maior Risco:** Clientes que compraram, mas estão sumidos. Foco Crítico na Reativação. |
| **01. Clientes Campeões** | 578 (13%) | **\$8,589.87** | **Maior Valor:** Maior Ticket Médio. Devem ser tratados como VIPs. |

### 🚨 Risco Crítico Identificado

O **35% da base** está no segmento **"Hibernando"**. Uma falha em reativar esses 1.505 clientes resultará em uma perda significativa de receita futura.

---

## 🚀 4. Recomendações de Ação (Plano de Marketing)

As recomendações são direcionadas para cada segmento, garantindo o máximo retorno sobre o investimento (ROI):

1.  **Clientes Campeões (Retenção e Valorização):** Programa de fidelidade VIP, atendimento prioritário e acesso antecipado a lançamentos.
2.  **Clientes Promissores (Conversão):** Campanhas de *upsell* e *cross-sell* (*"Quem comprou X, também gostou de Y"*), com foco em aumentar a Frequência de compra (F).
3.  **Clientes Hibernando (Reativação Urgente):** Campanhas de *win-back* (cupons de alto valor) ou e-mails de pesquisa de satisfação (*"Sentimos sua falta"*).

---

## 💻 5. Stack Tecnológico e Navegação

| Ferramenta | Uso |
| :--- | :--- |
| **Python** | ETL, limpeza de dados e aplicação do modelo RFM (Pandas e NumPy). |
| **Jupyter Notebook** | Documentação e execução da análise de dados (`.ipynb`). |
| **Looker Studio** | Criação do Dashboard interativo e final (Visualização e Insights). |
| **GitHub** | Versionamento e portfólio. |

---

## 👤 Autor

Rafael Agra

* **LinkedIn:** [https://www.linkedin.com/in/rafael-agra-201005355/]
