# Prever-eficiencia-de-combustivel-em-um-carro

Para prever a eficiência de combustível de um carro em kilometros por galão com base no peso do carro, temos o seguinte conjunto de dados:

kilometros em 1.000 (recurso) kilometros por galão (rótulo)
3.5 18
3,69 15
3,44 18
3,43 16
4,34 15
4,42 14
2,37 24

Utilizei a biblioteca scikit-learn em Python para realizar uma regressão linear. Abaixo estão os passos que tomei para faze-lo:

Importei as bibliotecas necessárias: importei o numpy para manipular os dados e LinearRegression de sklearn.linear_model.
Preparei os dados: Os dados de recursos (peso em 1.000 km) e o rótulo (km por galão) precisam estar em formatos que o scikit-learn entenda.
Criar e treinar o modelo: Criei uma instância do modelo LinearRegression e usei os dados para treiná-lo.
Fazer previsões: Depois de treinar o modelo,  pode usá-lo para prever a eficiência de combustível para novos pesos de carro.



