# marketing-regression-analysis
Análise de investimentos em marketing com regressão linear.

Modelo de Regressão para Marketing
Descrição
Este projeto tem como objetivo construir um modelo de regressão linear para prever o retorno de vendas a partir de investimentos em publicidade em três canais: YouTube, Facebook e jornal. O modelo foi desenvolvido utilizando um dataset de campanhas de marketing e aborda as etapas de análise descritiva, análise exploratória, modelagem e predição.

Etapas do Projeto
1. Análise Descritiva
Exploramos o dataset usando funções como info() e describe() para entender a distribuição e tipos de dados.
Identificamos possíveis inconsistências e outliers que pudessem afetar o modelo.
2. Análise Exploratória
Geramos gráficos de dispersão utilizando o seaborn para visualizar a relação entre os investimentos e as vendas.
Realizamos uma análise de correlação entre as variáveis para identificar os fatores mais relevantes para as vendas.
3. Modelagem
Utilizamos o scikit-learn para construir um modelo de regressão linear.
Dividimos os dados em conjuntos de treino e teste, e treinamos o modelo com os dados de treino.

4. Predição e Avaliação
Usamos o coeficiente de determinação (R²) para avaliar a precisão do modelo.
Realizamos previsões para estimar o impacto dos investimentos nas vendas futuras.

Bibliotecas Utilizadas
pandas
seaborn
matplotlib
scikit-learn
plotly

Como Executar o Projeto
Faça o download do dataset MKT.csv.
Execute o código em um ambiente Python, como Google Colab ou Jupyter Notebook.
Avalie os resultados e gráficos gerados para obter insights sobre o impacto dos investimentos de marketing.
Resultados
O modelo construído demonstrou uma correlação significativa entre os investimentos em YouTube e Facebook com as vendas, enquanto o investimento em jornal mostrou-se menos impactante.

