# case_airbnb

- ## a) Como foi a definição da sua estratégia de modelagem?

      Realizei uma AED nos dados, retirei algumas colunas que não continham dados, preenchi alguns dados faltantes, normalizei os dados, apliquei em dois modelos de regressão para avaliar a diferença, realizei uma validação cruzada, e para otimizar os hiperparametros realizei um randon search seguido de grid search para aumentar a assertividade do modelo.
      
      
- ## b) Como foi definida a função de custo utilizada?

      Utilizei uma série de medidas de custo sendo a principal o MAPE, para verificar a porcentagem de assertividade do modelo que ficou no final com 62% de diferença do real pro previsto.
    
- ## c) Qual foi o critério utilizado na seleção do modelo final?

      Complementando a resposta da pergunta anterior, foi uma junção de análises entre R², MAPE, MSE e MAE para definir o melhor modelo.

- ## d) Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este método?

      Utilizei Validação Cruzada com Random e Grid Search para definir os hiperparametros.
      
- ## e) Quais evidências você possui de que seu modelo é suficientemente bom?

      Dentre os testados foi o que apresentou um menor MAPE em comparação aos modelos testados.
