# 🥇 Data Engineering Project – Medallion Architecture (Bronze, Silver, Gold)

## 📌 Descrição
Projeto de Engenharia de Dados baseado na **arquitetura Medallion**
(Bronze, Silver e Gold), com foco em pipelines ETL utilizando **Python e SQL**.

O objetivo é demonstrar boas práticas de ingestão, transformação,
qualidade e disponibilização de dados para análise.

---

## 🧱 Arquitetura Medallion

### 🥉 Bronze Layer
- Dados brutos (raw)
- Sem transformações
- Fonte original preservada
- Objetivo: rastreabilidade e histórico

### 🥈 Silver Layer
- Dados tratados e padronizados
- Remoção de duplicidades
- Tipagem correta
- Regras de negócio básicas

### 🥇 Gold Layer
- Dados agregados e modelados
- Prontos para análise e consumo
- Visões analíticas e métricas

Fluxo:

Source → Bronze → Silver → Gold

## 🛠️ Tecnologias Utilizadas
- Python
- SQL
- Pandas
- PostgreSQL
- Git / GitHub

