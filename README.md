Regressão Múltipla

Extensão natural da regressão linear simples: ao invés de uma variável de entrada, aqui o modelo lida com múltiplas features ao mesmo tempo para fazer a previsão.

A ideia é entender como o algoritmo pondera cada variável independente e como isso afeta o resultado final. Mesmo conceito de antes, só que com mais dimensões pra gerenciar.

# No Notebook

Análise exploratória e seleção de features relevantes
Pré-processamento com tratamento de variáveis categóricas e normalização
Treinamento com LinearRegression do scikit-learn usando múltiplas entradas
Avaliação do modelo via R², MSE e análise dos coeficientes de cada feature
Visualizações para entender o peso de cada variável na predição

# Regressão múltipla vs simples

Na regressão simples, a equação é y = a*x + b. Na múltipla, vira y = a1*x1 + a2*x2 + ... + an*xn + b. O modelo aprende um coeficiente pra cada feature e analisar esses coeficientes diz muito sobre quais variáveis realmente influenciam o resultado.
