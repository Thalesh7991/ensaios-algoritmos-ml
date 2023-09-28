# Ensaio De Machine Learning

![Image1](/notebooks/Regressao/images/performance.jpg)

## Problema de Negócio

<p>A empresa Data Money acredita que a expertise no treinamento e ajuste fino dos algoritmos, feito
pelos Cientistas de Dados da empresa, é a principal motivo dos ótimos resultados que as
consultorias vem entregando aos seus clientes.</p>

## O Desafio

<p>O objetivo desse projeto será realizar ensaios com algoritmos de Classificação, Regressão e
Clusterização, para estudar a mudança do comportamento da performance, a medida que os
valores dos principais parâmetros de controle de overfitting e underfitting mudam.</p>

## Resultados Obtidos

### Clusterização

<p>Foram avaliados 2 algoritmos de Clusterização: KMEANS e Affinity Propagation</p>

#### KMEANS

**O Algortimo KMeans apresentou melhor Silhouette Score com 3 clusters**

![Image2](/notebooks/Clusterizacao/images/kmeans.png)

#### Affinity Propagation

**Com Affinity Propagation o melhor Silhouette Score encontrado foi com o parâmetro preference = -50, onde foram encontrados 7 clusters**

![Image3](/notebooks/Clusterizacao/images/affinity.png)

### Classificação

Dentre todas as métricas de Classificação o Algoritmo **KNN** foi o único que apresentou queda brusca de performance em relação aos dados de Treino, Validação e Teste.

Os demais algoritmos mantiveram um equilíbrio de performance, mostrando um **poder maior de generalização** 

![Image4](/notebooks/Classificacao/images/comparacao_classifier2.png)

### Regressão

Dentre os Algoritmos de Regressão, o que teve melhor performance em todas as métricas foi a **Random Forest Regressor**

![Image5](/notebooks/Regressao/images/comparacao_regression3.png)



