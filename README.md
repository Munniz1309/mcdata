# Descrição

Este projeto utiliza algoritmos de regressão para prever valores financeiros da McDonald's Corporation com base em seus demonstrativos financeiros históricos. O projeto emprega modelos de RandomForestRegressor e LinearRegression para realizar previsões e calcular métricas de desempenho como MAE, MSE, RMSE e R².

# Visão Geral
O conjunto de dados contém várias características financeiras da McDonald's, incluindo receitas, lucros, margens operacionais e ativos. O objetivo deste projeto é aplicar algoritmos de regressão para prever esses valores financeiros com base nos dados históricos fornecidos.

# Principais Colunas dos Dados:
- Market cap ($B): Capitalização de mercado da McDonald's em bilhões de dólares.
- Revenue ($B): Receita total em bilhões de dólares.
- Earnings ($B): Lucros da empresa em bilhões de dólares.
- P/E ratio: Relação preço/lucro.
- P/S ratio: Relação preço/vendas.
- P/B ratio: Relação preço/valor contábil.
- Operating Margin (%): Margem operacional em porcentagem.
- EPS ($): Lucro por ação em dólares.
- Cash on Hand ($B): Caixa disponível em bilhões de dólares.
- Dividend Yield (%): Rendimento de dividendos em porcentagem.
- Net assets ($B): Ativos líquidos em bilhões de dólares.
- Total assets ($B): Ativos totais em bilhões de dólares.
- Total debt ($B): Dívida total em bilhões de dólares.
- Total liabilities ($B): Passivos totais em bilhões de dólares.

# Tecnologias Utilizadas

- Pandas: Manipulação e análise de dados.
- Numpy: Operações numéricas.
- Scikit-learn: Conjunto de ferramentas de aprendizado de máquina, incluindo modelos de regressão e métricas de avaliação.
- Matplotlib: Visualização de dados.
- Seaborn: Visualização estatística dos dados.

# Resultados
Os modelos de regressão fornecem previsões precisas dos valores financeiros, com o RandomForestRegressor apresentando um R² de 0.620 e o LinearRegression um R² de 0.985.
