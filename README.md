# Databricks — Projeto de Aprendizado

Este repositório faz parte dos meus estudos de **Engenharia de Dados**.

Estou aprendendo a utilizar o **Databricks** e, para praticar, estou desenvolvendo um pequeno projeto utilizando dados reais e o conceito de arquitetura **Medallion (Bronze, Silver e Gold)**.

## Objetivo

Praticar:

- Databricks
- PySpark
- SQL
- Delta Lake
- Unity Catalog
- Git e GitHub
- Processamento e transformação de dados

## Projeto

Neste projeto estou trabalhando inicialmente com dados de voos da **VRA (Voo Regular Ativo)**.

Os dados são carregados para a camada **Bronze**, mantendo os dados o mais próximo possível da origem.

A ideia é evoluir o projeto gradualmente para as camadas:

```text
Dados brutos
    ↓
  Bronze
    ↓
  Silver
    ↓
   Gold
