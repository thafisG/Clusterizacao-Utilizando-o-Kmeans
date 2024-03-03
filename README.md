# Projeto de Clusterização utilizando o KMeans e o DataSet iris

Esse é um projeto para fins de curiosidade e estudo de machine learning, com o objetivo de que seja possível desenvolver um modelo capaz de agrupar grupos e com isso prever um comportamento padrão.

De que forma isso foi realizado? A partir da análise de dados do DataSet iris foi realizado normalização dos dados, após isso foi calculado o numero de cluster e definido o melhor valor de WCSS, após isso foi utilizado o algoritmo do Kmeans. Isso foi realizado com o objetivo de entender como estão divididos os grupos de flores e como são divididos. Além disso, foi realizada a análise dos centroides dos grupos e definidos os grupos através do processo de agrupamento, e utilizando dois graficos: o gráfico de cotovelo e o de disperssão de grupos.

A analise e agrupamento dos dados, foi divido em duas partes: primentamente das Petalas e logo após das Sepalas.

## Bibliotecas usadas 

- pandas
- sklearn.preprocessing import StandardScaler
- sklearn.cluster import KMeans
- plotly.express
- plotly.graph_objects 
     
