# Portfolio
Ongoing and completed projects
# Ordem de execução de tarefas na limpeza de dados utilizando python
Entender o objetivo da análise;
Estudar o dicionário de dados;
Importar os pacotes;
Carregar o dataset;
Fazer análise exploratória no dataframe: df.shape / df.info;
Analisar colunas de variáveis numéricas ausentes: quantos registros existem e qual o percentual em relação ao volume total de dados
Decidir como fazer a imputação dos valores ausentes em variáveis numéricas (pode ser dropada a coluna - se o percentual em relação ao volume total de dados for > 30% -, dropada a linha ou utilizar relações estatísticas como média, moda e mediana, escolher a técnica que menos modifique a variável);
Analisar colunas de variáveis categórias ausentes:  quantos registros existem e qual o percentual em relação ao volume total de dados;
Decidir como fazer a imputação dos valores ausentes em variáveis categóricas (pode ser dropada a coluna - se o percentual em relação ao volume total de dados for > 30% -, dropada a linha ou utilizar relação estatística como a moda escolher a técnica que menos modifique a variável).
# Observações
Lembrar que não se deve aplicar técnicas em variáveis alvo/de resposta, é melhor dropar os registros, pois seria estranho imputar. Gera muita interferência no resultado;
Sempre conferir se há só valores ausentes ou se também há ausência de informações. Utilizar describe para ver se há ausência de informações e interpretar as informações que surgirem. Posso fazer o replace da variável e transformá-la em valor ausente;
Sempre consultar as variáveis a cada análise.
# Ordem de execução de tarefas na análise de dados utilizando python
Utilizar count em uma análise univariada para visualizar sem gráficos (posso utilizar plot se quiser ver em gráfico, mas eu não gostei muito);
Utilizar scatter plot em uma análise multivariada para visualizar em gráficos de dispersão;
Analisar a correlação entre todas as variáveis numéricas para saber se existe correlação entre essa base de dados;
Relacionar as variáveis numéricas para calcular a média existente entre elas;
Relacionar as variáveis numéricas para calcular a mediana existente entre elas;
Visualizar o boxplot para conferir os cálculos de média e mediana;
Fazer mapa de correlação com as variáveis relacionadas;
Analisar índices de WOE e IV em variáveis categóricas;
Criar um relatório com base na análise de dados. 
# Estrutura de um relatório
Retomar o objetivo
Como foi feita a limpeza dos dados, qual a justificativa pras técnicas utilizadas;
Como foi feita a análise de dados, qual a justificativa das técnicas utilizadas;
Explicar a conclusão final.
# Observações
Sempre ter imagens explicativas no relatório;
Sempre trabalhar boas práticas de storytelling no relatório.
