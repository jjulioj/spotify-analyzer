# 🎧 Spotify Analyzer

Projeto em desenvolvimento para análise de padrões de consumo musical utilizando um pipeline moderno com **Azure**, **Databricks**, **Kafka**, **Airflow** e **Power BI**.

## 🚀 Objetivo
Analisar tendências musicais globais (gêneros, horários, características como energia, dançabilidade, valência, etc.) a partir da API pública do Spotify, aplicando boas práticas de engenharia de dados.

## 🛠️ Tecnologias
- Python
- Spotify Web API
- Apache Kafka / Azure Event Hub
- Azure Databricks (PySpark + Delta Lake)
- Apache Airflow
- Power BI

## 📂 Estrutura do Projeto
spotify-analyzer/ 
├── notebooks/         # Notebooks Databricks 
├── scripts/           # Scripts Python (ingestão, processamento) 
├── dags/              # DAGs do Airflow 
├── configs/           # Configurações e credenciais (não versionadas) 
├── data_samples/      # Exemplos de dados coletados 
└── README.md
