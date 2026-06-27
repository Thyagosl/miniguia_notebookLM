# Análise de Dados Integrada: Power BI, Python, Excel e SQL
---

## 📌 Índice
- [Visão Geral do Projeto](#-visão-geral-do-projeto)
- [Tecnologias e Ferramentas](#-tecnologias-e-ferramentas)
- [Arquitetura e Pipeline de Dados](#-arquitetura-e-pipeline-de-dados)
- [Etapas do Projeto](#-etapas-do-projeto)
- [Insights Adicionais (NotebookLM)](https://notebooklm.google.com/notebook/2c4a9d06-a4e8-4882-b7a8-7bf3a35ecceb)
- [Autor](Thyago Lima)

---

## 🚀 Visão Geral do Projeto
Este projeto foi criado com o objetivo de criar um segundo cérebro baseado nos conhecimentos de Análise de dados do Massachusetts Institute of Technology (MIT).
---

## 🛠️ Tecnologias e Ferramentas

* **SQL:** Extração, filtragem e agregação dos dados brutos a partir do banco de dados.
* **Python (Pandas/NumPy/Seaborn):** Limpeza de dados (ETL), tratamento de valores nulos e análise exploratória descritiva (EDA).
* **Excel:** Criação de tabelas dinâmicas e validações rápidas de regras de negócio.
* **Power BI:** Modelagem de dados (Star Schema), criação de métricas em DAX e desenvolvimento de um dashboard executivo interativo.

---

## 📐 Arquitetura e Pipeline de Dados

[Banco de Dados SQL] ──> [Extração/Query]
│
▼
[Python / Pandas] ──> (Limpeza e Tratamento)
│
▼
[Excel / CSV]     ──> (Validação e Auditoria)
│
▼
[Power BI]        ──> (Modelagem DAX e Dashboard)

## 📋 Etapas do Projeto

### 1. SQL (Extração de Dados)
* Criação de queries para consolidar tabelas de fatos e dimensões.
* Uso de comandos como `JOIN`, `GROUP BY` e `HAVING` para otimizar a volumetria dos dados extraídos.
* *Arquivo de referência:* `queries/extracao_dados.sql`

### 2. Python (Análise Exploratória & Limpeza)
* Identificação e tratamento de outliers e dados duplicados.
* Análise de correlação entre variáveis de negócio.
* *Arquivo de referência:* `notebooks/analise_exploratoria.ipynb`

### 3. Excel (Análise Rápida)
* Estruturação de relatórios preliminares em tabelas dinâmicas para validação com stakeholders.

### 4. Power BI (Visualização de Dados)
* Construção do modelo de dados relacional.
* Desenvolvimento de medidas em DAX (Ex: YoY %, Acumulado Anual, Média Móvel).
* Layout funcional focado em UX (User Experience) para tomada de decisão.

---

## 🧠 Insights Adicionais (NotebookLM)
Como suporte ao projeto, foi criada uma base de conhecimento utilizando o **NotebookLM**, permitindo a geração de resumos automatizados, correlações avançadas de conceitos e insights de negócios baseados nas fontes de dados textuais e métricas extraídas ao longo do projeto.
---

## 🧑‍💻 Autor

Desenvolvido por Thyago Lima 👉 Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/thyagosl/)

