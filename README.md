# Projeto de Modelagem Preditiva em R

![R](https://img.shields.io/badge/R-Linguagem-276DC3?style=flat-square&logo=r)
![Tidymodels](https://img.shields.io/badge/Tidymodels-Framework-FF3366?style=flat-square&logo=r)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-FF8000?style=flat-square&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Modelos-102230?style=flat-square&logo=opsgenie)
![Data Science](https://img.shields.io/badge/Data%20Science-Análise-4B8BBE?style=flat-square&logo=anaconda)

---

## Descrição
Este repositório apresenta um conjunto de exemplos práticos em **R** para construção, avaliação e comparação de modelos de **Machine Learning** aplicados à previsão de valores de automóveis.  
Cada exemplo mostra um estágio diferente do fluxo de trabalho em ciência de dados, desde a preparação inicial dos dados até a utilização de modelos ajustados em novos cenários.

---

## Funcionalidades
- Preparação de dados para modelagem supervisionada.  
- Construção de modelos com **árvores de decisão**.  
- Implementação de técnicas de ensemble como **Bagging** e **Random Forest**.  
- Aplicação da técnica de **Boosting** com XGBoost.  
- Comparação de modelos a partir de métricas (RMSE, MAE, R²).  
- Salvamento do modelo final em `.rds` e uso em **novos dados**.  
- Código comentado e estruturado para fins didáticos.  

---

## Estrutura do Projeto

### Exemplo 1 – Preparação e Árvores de Decisão
- Introdução ao dataset.  
- Criação e avaliação de um modelo baseado em **árvore de decisão simples**.  
- Cálculo das métricas de desempenho.  

### Exemplo 2 – Bagging (Bootstrap Aggregating)
- Construção de modelo de **bagging** para reduzir variância.  
- Uso de validação cruzada para avaliar a performance.  

### Exemplo 3 – Random Forest
- Criação do modelo de **Random Forest**.  
- Comparação com Bagging e Árvores de Decisão.  
- Interpretação das métricas.  

### Exemplo 4 – Boosting com XGBoost
- Implementação do modelo de **Boosting** (XGBoost).  
- Testes com diferentes hiperparâmetros (número de árvores, taxa de aprendizado).  
- Seleção do modelo com melhor performance.  

### Exemplo 5 – Comparação de Modelos e Novos Dados
- Comparação direta entre Decision Tree, Bagging, Random Forest e XGBoost.  
- Escolha do melhor modelo.  
- Salvamento em arquivo `.rds`.  
- Aplicação do modelo final em **novos automóveis** (sedã, minivan, SUV).  

---

Este material serve como guia prático para estudantes e profissionais que desejam entender na prática como aplicar diferentes técnicas de **machine learning supervisionado** em R.

