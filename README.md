# Projeto de Análise e Classificação de Cancelamento de Serviço do Cliente(Churn)
## Visão Geral
Este projeto se concentra na análise de dados e na construção de um modelo de classificação para prever o cancelamento de serviço por parte dos clientes. Começamos com a limpeza dos dados, a exploração das características disponíveis e a divisão do conjunto de dados para treinamento e teste. Em seguida, treinamos vários modelos de classificação e avaliamos seu desempenho usando métricas relevantes.
## Como visualizar o projeto 
Clique no arquivo chamado `churn.ipynb`
## Etapas Realizadas

### 1. Limpeza e Preparação de Dados:
* Tratamento de valores ausentes.
* Conversão de variáveis categóricas em numéricas.

### 2. Exploração de Dados:
* Identificação das características disponíveis.
* Análise da distribuição das classes.

### 3. Treinamento de Modelos:
* Diversos modelos foram utilizados, incluindo Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, SVM e XGBoost.

### 4. Avaliação de Desempenho:
* Utilização de métricas como acurácia, precisão, recall, F1-score e área sob a curva ROC.
### 5. Lidando com Dados Desbalanceados:

* Observação de desempenho insatisfatório em modelos treinados nos dados desbalanceados, especialmente no recall.

### 6. Técnica de Undersampling:
* Redução da quantidade de dados da classe majoritária para lidar com desequilíbrio nos dados.
* Melhoria significativa no desempenho dos modelos, especialmente no recall.

### 7. Modelo com Melhor Desempenho:
* O modelo de Logistic Regression com undersampling mostrou um recall de 0,81.
* Destacou-se na identificação correta da maioria dos casos positivos.

### 8. Otimização de Hiperparâmetros:
* Utilização da técnica de otimização bayesiana para ajuste dos hiperparâmetros.
* Confirmação do desempenho superior do modelo final otimizado.
## Conclusão
Este projeto enfatiza a importância de lidar com dados desbalanceados ao construir modelos de classificação. A técnica de undersampling foi eficaz para melhorar o desempenho do modelo, especialmente na identificação de casos positivos. Além disso, a otimização dos hiperparâmetros permitiu uma melhoria adicional no desempenho do modelo final.
