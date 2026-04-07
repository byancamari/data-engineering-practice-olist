# Desafio Técnico: Pipeline de Dados Olist 

Este repositório contém a solução para o desafio de engenharia de dados, estruturado em arquitetura Medalhão (Bronze, Silver e Gold) utilizando Databricks e PySpark.

## 🛠️ Estrutura do Projeto
- **Camada Bronze:** Ingestão dos dados brutos em formato Delta com adição de metadados.
- **Camada Silver:** Limpeza, tipagem, tratamento de duplicados e modelagem dimensional (Fatos e Dimensões).
- **Camada Gold:** Criação de Data Marts para visão comercial e qualidade, respondendo a KPIs de negócio.

## ⚙️ Orquestração
O pipeline foi automatizado utilizando **Databricks Workflows**, configurado para execução diária às **13:00 (Horário de Brasília)**.

## 📊 Entregáveis
- Notebooks em formato `.ipynb`.
- Arquivo `.yaml` de configuração do Job.
- Prints de comprovação da execução.
