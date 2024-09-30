# walmart-sales-prediction


**Descrição do projeto**

Este projeto utiliza dados de vendas do Walmart para prever as vendas semanais (Weekly_Sales) utilizando diferentes variáveis como loja, mês, temperatura, CPI (Índice de Preços ao Consumidor) e desemprego. O objetivo é identificar as variáveis que mais influenciam as vendas e construir um modelo de Machine Learning que ofereça previsões precisas. Utilizamos várias abordagens, incluindo *Logistic Regression, K-Nearest Neighbors (Radius Neighbors Regressor), Decision Tree, Huber Regressor e Random Forest*, sendo que o último apresentou os melhores resultados, com um *erro absoluto médio de 6,7%*.

**Tecnologias utilizadas**

- **Python**: Linguagem principal do projeto.
- **Pandas**: Utilizado para a manipulação e análise dos dados.
- **Seaborn** e **Matplotlib**: Bibliotecas de visualização para criação de gráficos e análise visual dos dados.
- **Scikit-learn**: Biblioteca para a construção e avaliação de modelos de Machine Learning.
- **Jupyter Notebook**: Para organizar e executar o código de maneira interativa.

**Resultados**
Os principais insights da análise incluem:

- As variáveis com maior correlação com as vendas semanais foram:
- Store (Loja)
- Month (Mês)
- Temperature (Temperatura)
- CPI (Índice de Preços ao Consumidor)
- Unemployment (Desemprego)
- Através de diferentes modelos, o Random Forest foi o que apresentou os melhores resultados, com uma margem de erro de 6,7%.

**Visualizações geradas**

- Heatmap das correlações entre variáveis
- Importância das features segundo o modelo Floresta Aleatória
- Distribuição do erro absoluto

**Contribuição**

- Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
