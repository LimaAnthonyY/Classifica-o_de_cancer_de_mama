# Classificação de Câncer de Mama com Redes Neurais

Este repositório contém um projeto de *machine learning* que utiliza redes neurais para a classificação de tumores de mama como malignos ou benignos, com base no **Breast Cancer Wisconsin (Diagnostic) Data Set** disponível no [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

## Objetivo

O objetivo deste trabalho é desenvolver um modelo de aprendizado de máquina eficaz, utilizando uma Rede Neural Multilayer Perceptron (MLP), para auxiliar na detecção precoce de câncer de mama. O modelo prevê se o tumor é maligno ou benigno, com base em características extraídas de exames.

## Etapas do Projeto

1. **Exploração e Análise de Dados**: Análise exploratória do *dataset* para entender as variáveis e suas correlações.
2. **Pré-processamento**: Limpeza, normalização e divisão dos dados em conjuntos de treino e teste.
3. **Construção do Modelo**: Implementação de uma rede neural com MLP, utilizando *GridSearchCV* para otimização dos hiperparâmetros.
4. **Avaliação**: Avaliação do desempenho do modelo por meio de métricas como acurácia e matriz de confusão.
5. **Visualizações**: Gráficos para a distribuição dos erros e matriz de confusão normalizada.

## Tecnologias Utilizadas

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Resultados

Os melhores parâmetros encontrados durante a otimização, bem como as métricas de acurácia do modelo, são apresentados ao final, junto com visualizações para ajudar a compreender o desempenho da rede neural.
