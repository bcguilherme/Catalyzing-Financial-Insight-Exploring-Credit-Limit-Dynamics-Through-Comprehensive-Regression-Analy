# basedecreditoregrelinear

análise de Crédito - Regressão Linear
Este repositório contém um notebook Jupyter que realiza uma análise de regressão linear no conjunto de dados "Limite de Crédito". O objetivo é prever o limite do cheque especial com base em várias características dos clientes.

Conteúdo do Notebook
Importação de Bibliotecas

Importou as bibliotecas necessárias, incluindo pandas, numpy, seaborn e scikit-learn.
Carregamento dos Dados

Carregou os dados do arquivo "Cópia de Limite_Credito_Dummy.xlsx" usando a biblioteca pandas.
Pré-processamento

Utilizou o LabelEncoder para transformar as colunas 'Escolaridade', 'Gênero' e 'Região' em valores numéricos.
Usou o MinMaxScaler para normalizar os dados do DataFrame.
Análise Exploratória

Gerou histogramas para visualizar a distribuição da variável alvo 'LimitedoChequeEspecial'.
Calculou estatísticas descritivas para o DataFrame.
Modelagem de Regressão

Utilizou a biblioteca statsmodels para realizar regressão linear em diferentes configurações de variáveis independentes.
Imprimiu os resultados da regressão para cada modelo ajustado.
Modelo de Regressão Linear com scikit-learn

Separou os dados em conjuntos de treino e teste.
Ajustou um modelo de regressão linear usando o conjunto de treino.
Avaliou o desempenho do modelo nos conjuntos de treino e teste utilizando métricas como MAE, MSE e RMSE.
Resultados
Foram ajustados vários modelos de regressão linear utilizando diferentes conjuntos de variáveis independentes. As métricas de desempenho do modelo foram calculadas e avaliadas para verificar quais variáveis têm maior impacto na previsão do limite do cheque especial.

Como Executar
Instale as bibliotecas listadas no arquivo de requisitos (requirements.txt).
Abra o notebook Jupyter.
Execute cada célula do notebook em ordem para reproduzir as análises e resultados.
