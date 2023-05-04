<h1>Predição de vendas utilizando o dataset da Rossman</h1>

Este projeto tem como objetivo utilizar técnicas de Machine Learning para fazer a predição de vendas de uma cadeia de farmácias, a partir do dataset disponibilizado pelo grupo Rossman. O projeto é desenvolvido em Python e utiliza diversas bibliotecas como Pandas, Numpy, Matplotlib, Seaborn e Boruta para pré-processamento e visualização dos dados, além de modelos de regressão como LinearRegression, Lasso, RandomForestRegressor e XGBRegressor para a predição.

<h3>Instalação e Requisitos</h3>
Antes de começar, é necessário que o Python esteja instalado na sua máquina. Para instalar as bibliotecas utilizadas, execute o seguinte comando no terminal:

<i>pip install -r requirements.txt</i>

<h3>Análise exploratória dos dados</h3>
Foi realizada uma análise exploratória detalhada dos dados disponíveis, que permitiu entender melhor o negócio e formular hipóteses a serem verificadas. As bibliotecas utilizadas para essa etapa foram Pandas, Numpy, Matplotlib e Seaborn.

<h3>Pré-processamento dos dados</h3>
Para o pré-processamento dos dados, foi utilizada a biblioteca Boruta, que selecionou as features mais relevantes para a predição. Além disso, foram feitas transformações em algumas variáveis categóricas e preenchimento de dados faltantes.

<h3>Modelagem</h3>
Foram testados diversos modelos de regressão para a predição, entre eles LinearRegression, Lasso, RandomForestRegressor e XGBRegressor. A validação cruzada foi utilizada para avaliar o desempenho dos modelos e a métrica utilizada para escolher o melhor modelo foi o erro quadrático médio (MSE).
