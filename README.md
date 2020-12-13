
# About the project (how was done) [EN]

   ### Step 1 (Preparation):
   i receive the Yelp dataset as a challenge with a Json file with more than 5 million rows and 6 Gb. Thinking about the best strategy to reduce the amount of memory that this file demanded i decided to filter the columns that i needed to use and choose Python as the best way to do so.
 
   ### Step 2 (On Jupyter Notebook):
   Let's talk about the python script, starting from the libraries:
   First of all, i worked with some of the most common used libraries in the data science area such as pandas, numpy, os and, of course, json. 
   In the first command block i create a list for each of the columns that i needed, then i open the file with a loop right after him to take only 'business_id' and 'stars' data and store them in the lists.
   Following this idea, i put the lists in a dataframe, changed the type of them and finally wrote a CSV file containing this dataframe in a really lightweight way.
   
   ### Step 3 (On Talend):
   With this CSV file containing only the demanded columns, i just needed to aggregate the rows with 'tAggregateRow' function and put the average operation in the 'stars' column, doing the same thing as we could do in SQL Server with the group by function. After this operation, i just put an output to my local SQL Server.
   
   
# Sobre o Projeto (Como foi feito) [PT]

   ### 1º Passo (Preparação):
   Eu recebi o dataset da Yelp como desafio, com um arquivo JSON de mais de 5 milhões de linhas e 6 GBs. Pensando na melhor estratégia pra reduzir a quantidade de memória que o arquivo pediria, eu decidi filtrar as colunas que eu precisaria usar e escolhi o Python como a melhor forma de fazer isso.
 
   ### 2º Passo (No Jupyter Notebook):
   Falando sobre o script do Python, começando com as bibliotecas:
   Primeiramente, eu trabalhei com as bibliotecas mais usadas na area de Data Science, como o pandas, numpy, os e, claro, a json.
   No primeiro bloco de comandos eu criei uma lista para cada coluna que eu precisava, depois disso abri o arquivo seguido por um laço/loop pra pegar apenas os dados das duas colunas e armazenar nas listas criadas.
   Seguindo essa ideia, eu coloquei as duas listas em um dataframe, mudei o tipo delas e finalmente escrevi um arquivo CSV contando com o mesmo dataframe de uma forma muito mais leve.
   
   ### 3º Passo (No Talend):
   Com esse arquivo CSV contendo só as colunas demandadas pra o desafio, eu só precisaria agregar as linhas com a função 'tAggregateRow' e colocando a operação de média na coluna de estrelas, fazendo a mesma coisa que eu poderia fazer no SQL Server com a função Group By. Depois dessa operação, só adicionei uma saída com dos dados no meu servidor local do SQL Server.
