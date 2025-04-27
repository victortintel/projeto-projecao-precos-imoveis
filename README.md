# Projeto de Machine Learning: Previsão de Preços de Imóveis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-green)

Este projeto implementa um sistema completo de machine learning para prever preços de imóveis baseado em características da região e das propriedades.

## 📌 Visão Geral

O objetivo deste projeto é prever o preço médio de imóveis em diferentes regiões da Califórnia utilizando várias técnicas de machine learning. O projeto segue todas as etapas de um fluxo de trabalho de ciência de dados:

1. Análise Exploratória de Dados (EDA)
2. Pré-processamento e Engenharia de Features
3. Modelagem com vários algoritmos (Decision Tree, Random Forest, KNN, SVM)
4. Otimização de Hiperparâmetros
5. Avaliação e Seleção de Modelos
6. Análise de Resíduos e Importância de Features

## 📊 Conjunto de Dados

Utilizamos o conjunto de dados "California Housing" do scikit-learn, que contém informações sobre:
- Renda média da região
- Idade média das casas
- Número médio de cômodos e quartos
- População e ocupação média
- Localização geográfica (latitude e longitude)
- Preço médio das casas (target)

## 🛠️ Tecnologias Utilizadas

- Python 3.8+
- Jupyter Notebook
- Bibliotecas principais:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - Joblib (para serialização do modelo)

## 📈 Resultados Principais

O melhor modelo foi o **Random Forest**, que alcançou:
- R² de 0.81 no conjunto de teste
- RMSE de ~$50,000
- MAE de ~$35,000

As features mais importantes foram:
1. Renda média da região
2. Localização (latitude e longitude)
3. Número médio de cômodos

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/previsao-precos-imoveis.git
