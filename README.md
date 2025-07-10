# 📊 Desafio TelecomX - Análise de Dados

Este repositório contém a análise de dados de churn de clientes para a empresa de telecomunicações fictícia, TelecomX. O objetivo deste projeto é identificar os principais fatores que levam os clientes a cancelar seus serviços e, a partir disso, fornecer insights que possam ajudar a empresa a desenvolver estratégias para retenção de clientes.

---

## 🔍 Objetivo

Realizar uma análise exploratória de dados com foco em identificar inconsistências, padrões e possíveis insights para apoiar decisões estratégicas.

---

## 🧱 Estrutura do Projeto

O projeto está dividido em três principais etapas:

### 📌 1. Extração (Extract)
- Carregamento de dados a partir de uma URL externa (`TelecomX_Data.json`).
- Conversão para um DataFrame pandas.

### 🔧 2. Transformação (Transform)
- Normalização de dados aninhados.
- Padronização de colunas.
- Tratamento de valores nulos e inconsistências.

### 📊 3. Análise Exploratória (EDA)
- Visualização de métricas principais com `matplotlib` e `seaborn`.
- Identificação de padrões relacionados ao cancelamento de serviços (*Churn*).
- Cruzamento de variáveis como tipo de serviço, método de pagamento, tempo de contrato e cobranças.

---

📊 Análise e Resultados

A análise exploratória dos dados revelou os seguintes insights sobre o churn de clientes:

* Taxa de Churn: A taxa geral de churn de clientes é de 26,5%.

* Gênero: Não há uma diferença significativa no churn entre clientes do sexo masculino e feminino.

* Cliente Idoso: Clientes idosos têm uma maior propensão a cancelar os serviços.

* Dependentes: Clientes sem dependentes são mais propensos a cancelar.

* Serviços de Telefonia:

    * Clientes com múltiplas linhas telefônicas têm uma taxa de churn ligeiramente maior.

    * Clientes sem serviço de telefonia (que possuem apenas serviço de internet) têm uma taxa de churn menor.

* Serviços de Internet:

    * Clientes com serviço de fibra ótica apresentam a maior taxa de churn.

    * Clientes sem segurança online têm uma taxa de churn significativamente maior.
---

📈 Visualizações

O notebook contém diversos gráficos que ilustram os resultados da análise, incluindo:

* Gráfico de barras e de pizza da distribuição da evasão de clientes.

* Gráficos de barras e de pizza da evasão por gênero, cliente idoso, dependentes, múltiplas linhas telefônicas e segurança online.


## 📁 Arquivos

- `challenge_telecomx.ipynb`: Notebook principal com todo o processo de análise.
- `TelecomX_Data.json`: Arquivo JSON de dados brutos.
- `TelecomX_dicionario.md`: Arquivo Markdown com explicações sobre cada coluna.
---

## 🛠️ Tecnologias Utilizadas

- Python 3
- pandas
- matplotlib
- seaborn
- requests

---

