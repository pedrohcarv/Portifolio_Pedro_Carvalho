Esse é o meu protfólio em Data Science, aqui está o que eu ando trabalhando ultimamente.


## Projeto 1: Analise de dados - Ligações para o 911
O projeto serve para trazer insights atrávez de análises das chamadas para o 911.

   * Traz entendimento sobre a manipulação de DataFrames.
   * Exploração dos dados atráves de gráficos para entender visuamente o que está acontecendo.

Por conclusão chegamos que Emergencias Médicas são as que tem mais chados do 911 nos EUA, uma conclusão bem sólida encontrada foi que Janeio tem muito mais casos que o mês de Dezembro.

 ![](/imagens/EMS_count.png) 
 
 ![](/imagens/EMS_months.png)
 
 Atráves de um HeatMap temos uma visão facilitada para entender quais os momentos que mais é necessario ter profissionais prontos para atender os chamados.
 
 ![](/imagens/heatmap.png)
 
## Projeto 2: Regressão Linear - Decisão de Desenvolvimento
O projeto é para uma empresa que está em dúvida se deve priorizar o desenvolvimento do seu site ou do seu aplicativo.

  * Utilização de Machine Learning com ScikitLearn
  * Aplicação de conceitos em Regressão Linear
  
 Atráves de jointplots foi feito uma verificação visual para ver qual dos dois seria mais lucrativo, o site ou o aplicativo.
 
  ![](/imagens/joint1_lin.png) ![](/imagens/joint2_lin.png)
 
 Com essa simples visualização podemos já ter uma ideia que o aplicativo será mais lucrativo, mas iremos confirmar isso com uma regressão linear.
 
 ![](/imagens/coefs_lin.png)
 
 Com a tabela dos coeficentes que criamos podemos verificar que os esforços devem ser gastos no aplicativo por que os clientes que ficam no aplicativo gastam mais do 
 que os clientes que ficam no site, por que as pessoas que usam o aplicativo tem um gasto previsto de 38.50 dolares por minuto que estão no aplicativo, já as do site tem um 
 gasto de 0.60 dolares por minuto.
 
 Mas temos também que verificar o quão confiavel é o nosso modelo e abaixo temos essa verificação, temos um gráfico que mostra que os valores preditos condizem muito com os valores de teste
 
  ![](/imagens/scatter_lin.png)
 
## Projeto 3: Regressão Logística - Campanha de Anúncio
O projeto tem como foco achar públicos alvo para uma campanha de anúncio.

   * Utilização de Machine Learning com ScikitLearn
   * Aplicação de conceitos em Regressão Logística
    
  Foi verificado qual coluna seria utilizada na regressão atráves deste pairplot:
    
    
  ![](/imagens/pairplot_log.png)
    
    
  Após as verificações para ver qual dos parâmetros presesentes no DataFrame usamos a Idade, Sexo e Renda da Área e como variável alvo, utilizamos o Clique no Anúncio.
  
  Abaixo consta a Tabela de Classificação e a Matriz de Confusão 
  
  
  ![](/imagens/cr_log.png)          ![](/imagens/cm_log.png)
  
  
  ### O Notebook Jupyter de todos os projetos estão completos no github na pasta ![jupyters](https://github.com/pedrohcarv/Portifolio_Pedro_Carvalho/tree/main/jupyters)
