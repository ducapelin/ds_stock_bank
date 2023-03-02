# Análise do Segmento Banco no Mercado de Ações
* Utilizando dados do YFinance foi realizada uma análise do mercado dos bancos de 2014 até 2022
* Foi realizado no Jupyter Notebook utilizando bibliotecas como Pandas, Numpy, Seaborn, Matplotlib para realização da análise
* Feita análises como o comparativo dos preços, maior retorno em um dia, ação com maior volatilidade.

## Recursos Utilizados
**Bibliotecas:** Pandas, Numpy, Matplotlib, Seaborn, Plotly  
**Obter Dados:** yfinance (Yahoo Finances)

## Obtenção e Limpeza dos Dados
Para a obtenção dos dados, eu importei a biblioteca do Yahoo Finances (yfinance) e criei um data frame para cada banco desejado, utilizando o código dele e a data de '01/01/2014' até '28/02/2023'  

Para a limpeza e organização dos dados, eu criei uma lista com todos os códigos dos bancos em que importei os dados, na ordem em que foram importados, e realizei um concatenar dos arquivos importados com a lista com os códigos, para assim ter todos os dados em apenas um data frame, sendo ele multiIndex  

## Análise dos Dados
Dentre as análises principais feitas, foi feita uma comparação do valor dos 4 bancos com maior volume de compra e venda:

![My Image](https://github.com/ducapelin/ds_stock_bank/blob/main/comp2.png)  
  
Outra análise que fiz foi o desvio padrão dos valores dessas ações, sabendo assim qual ação teve a maior variação dos valores e qual teve a menor variação dos valores, sendo possível entender melhor esse valor em um gráfico feito comparando a ação com maior variação e a ação com menor variação:

![My Image2](https://github.com/ducapelin/ds_stock_bank/blob/main/DESVIO.png)

Para a análise dos dados além das análises sobre os preços mais altos e mais baixos de cada ação, eu criei um novo data frame chamado retorno, nele foi possível analisar os maiores e menores retornos em um dia de cada ação dos bancos, e qual a data em que isso ocorreu:

![My Image](https://github.com/ducapelin/ds_stock_bank/blob/main/RETORNO.PNG) 
