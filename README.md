# Projeto de Análise e Predição de Avaliações de Livros do Goodreads

Este projeto visa realizar uma análise exploratória dos dados de livros do Goodreads e desenvolver um modelo preditivo para identificar a probabilidade de um livro ter uma boa avaliação. O projeto é dividido em cinco etapas principais, detalhadas abaixo.

## 1. Carregamento e Limpeza do Dataset
- **Importação dos Dados**: Os dados do dataset do Goodreads foram carregados no Google Colab para manipulação e análise.
- **Limpeza Básica**: Foram realizados tratamentos de dados essenciais, como remoção de valores ausentes e duplicatas, para garantir a integridade dos dados e melhorar a qualidade da análise.

## 2. Análise Exploratória dos Dados
- **Visualizações Básicas**: Diversas visualizações foram criadas para entender melhor as distribuições dos dados, incluindo:
  - Distribuição das classificações dos livros.
  - Gêneros mais populares entre os livros.
  - Autores com maior número de avaliações.
- **Estatísticas Descritivas**: Realizamos análises para identificar os livros mais e menos bem avaliados, considerando a média de avaliações e o número total de resenhas.

## 3. Preparação dos Dados para Modelagem / Pipeline de Pré Processamento (Feature não obrigatória)
- **Seleção e Preparação de Features**: Identificamos as variáveis mais relevantes para o modelo, como gênero, número de avaliações e média de avaliações.
- **Codificação de Variáveis Categóricas**: Variáveis categóricas foram convertidas para um formato que o modelo pudesse interpretar, como a binarização dos gêneros dos livros, para que cada gênero fosse representado por uma coluna binária.

## 4. Treinamento de um Modelo Preditivo
- **Modelo de Classificação**: Implementamos um modelo de classificação para prever a probabilidade de um livro receber uma boa avaliação (média de avaliações acima de um limite definido).
- **Separação de Conjuntos de Dados**: Os dados foram divididos em conjuntos de treino e teste, com 80% para treinamento e 20% para teste, garantindo a validação do modelo.

## 5. Avaliação do Modelo
- **Métricas de Avaliação**: Para verificar o desempenho do modelo, utilizamos métricas como:
  - **Acurácia**: Mede a proporção de previsões corretas.
  - **Precisão**: Avalia a proporção de previsões positivas corretas em relação a todas as previsões positivas.
  - **Recall**: Mede a proporção de casos positivos identificados corretamente pelo modelo.
  
Essas métricas nos permitiram avaliar a efetividade do modelo em prever boas avaliações de maneira equilibrada.

## 6. Visualização Extra (Feature não obrigatória)
  - **Distribuição assimétrica**: Visualização do problema enfrentado na hora de treinar o modelo preditivo.
---

Este projeto combina técnicas de análise exploratória, pré-processamento de dados e aprendizado de máquina para fornecer insights valiosos sobre o comportamento de avaliações de livros e um modelo preditivo eficiente.
