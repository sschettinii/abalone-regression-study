# Predição da idade de Abalones via Aprendizado Supervisionado

### Este projeto foi desenvolvido como um exercício prático da disciplina de Machine Learning na UEL e foca na predição da idade de moluscos do tipo abalone através de suas características físicas. A idade desses animais é tradicionalmente determinada pela contagem de anéis na concha, um processo manual e demorado. Aqui, testamos modelos estatísticos para automatizar essa estimativa.

### Durante o desenvolvimento, trabalhei na criação de novos atributos, como o volume da concha, e utilizei técnicas de seleção de variáveis (SFS) para identificar quais dados realmente impactavam no desempenho do modelo. O trabalho compara a performance da Regressão Linear com o KNN Regressor.

### Nos testes realizados, o modelo KNN com seleção de atributos e sem normalização foi o que entregou os melhores resultados, alcançando um R² aproximado de 0,55. Isso aconteceu principalmente pela capacidade do algoritmo de lidar com padrões não lineares que a regressão simples não conseguiu captar totalmente.

### Para rodar este notebook, você precisará das bibliotecas básicas de ciência de dados como pandas, scikit-learn e seaborn instaladas no seu ambiente Python.

### Abalone Dataset: https://www.kaggle.com/datasets/rodolfomendes/abalone-dataset