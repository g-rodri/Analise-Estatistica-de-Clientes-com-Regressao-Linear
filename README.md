Objetivo do Projeto

O objetivo deste projeto é analisar o tempo de permanência dos clientes em um serviço (Days_Since_Subscription) e verificar se existe relação estatisticamente significativa com o tempo médio de login (Avg_Login_Time).

Para isso, são aplicados conceitos fundamentais de estatística e modelagem matemática, permitindo avaliar padrões, probabilidades e a força da relação entre as variáveis analisadas.

________________________________________
Tecnologias e Bibliotecas Utilizadas

Python

Pandas — manipulação de dados

NumPy — operações numéricas

SciPy — probabilidade e distribuição normal

StatsModels — regressão linear (OLS)

Seaborn — visualização de dados

________________________________________

🧩 Estrutura do Projeto
1. Carregamento dos Dados

Importação das bibliotecas estatísticas.

Leitura da base de dados a partir de um arquivo Excel.

Visualização inicial das primeiras linhas do dataset.

2. Estatística Descritiva

Cálculo da mediana da variável Days_Since_Subscription.

Cálculo da média e do desvio padrão do tempo de assinatura.

Análise do comportamento geral dos clientes ao longo do tempo.

3. Cálculo de Probabilidades

Aplicação da Distribuição Normal.

Cálculo da probabilidade de um cliente ter menos de 1534 dias de assinatura.

Definição de um intervalo de ±2 desvios padrão em torno da média.

Interpretação estatística dos eventos como:

raro

provável

quase certo

4. Modelagem por Regressão Linear

Criação de um dataset contendo:

Variável dependente (Y): Days_Since_Subscription

Variável independente (X): Avg_Login_Time

Ajuste de um modelo de Regressão Linear Simples (OLS).

Geração do resumo estatístico do modelo (coeficientes, p-value, R²).

5. Visualizações

O projeto gera gráficos para apoiar a análise:

📈 Reta de regressão entre tempo médio de login e tempo de assinatura

📦 Boxplot para análise de dispersão dos dados

Avaliação visual da fraca relação entre as variáveis

_______________________________________________

Principais Resultados

A média do tempo de assinatura gira em torno de 4 anos, indicando uma base de clientes relativamente fiel.

A probabilidade calculada mostra que a maioria dos clientes se encontra dentro do intervalo esperado pela distribuição normal.

A regressão linear apresentou:

Coeficiente ≈ 0.345 para Avg_Login_Time

R² ≈ 0.009, indicando que o tempo médio de login explica apenas 0,9% da variação no tempo de assinatura.

Conclusão: não existe relação estatisticamente relevante entre tempo de login e tempo de permanência do cliente.

___________________________
Dataset (ainda vou fazer o upload)
