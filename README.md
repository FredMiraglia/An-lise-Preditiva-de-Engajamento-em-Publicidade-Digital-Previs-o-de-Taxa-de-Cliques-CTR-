Revisão de Taxa de Cliques (CTR Prediction) com Regressão Logística
Este repositório contém o projeto de Machine Learning desenvolvido para prever o engajamento do usuário com publicidade digital. O objetivo é determinar, com alta precisão, se um usuário específico irá clicar em um anúncio com base em seu perfil e hábitos de navegação.

🎯 Objetivo do Projeto
O coração da publicidade digital é a Taxa de Cliques (CTR). Criamos um modelo para identificar padrões de comportamento que levam ao clique, permitindo que as empresas otimizem a exibição de anúncios, direcionando-os aos usuários mais propensos a interagir.

🛠️ Metodologia e Tecnologias
O projeto seguiu as seguintes etapas:

Análise Exploratória de Dados (EDA): Análise da distribuição de variáveis como Age (Idade), Daily Time Spent on Site (Tempo Gasto no Site) e Area Income (Renda da Área) em relação ao clique.

Pré-processamento de Dados: Tratamento de dados categóricos (variável Male para indicar sexo) e escalonamento de variáveis contínuas, como Daily Time Spent on Site e Daily Internet Usage, usando o StandardScaler.

Modelagem: Implementação de um classificador de Regressão Logística (LogisticRegression).

Avaliação: Treinamento e avaliação do modelo em um conjunto de teste balanceado.

🚀 Resultados de Desempenho
O modelo demonstrou um desempenho robusto e de alta qualidade:
Métrica,Valor,Interpretação
Acurácia,0.97,97% das previsões do modelo foram corretas.
F1-Score,0.97,Excelente equilíbrio entre Precisão e Recall.
Recall (Classe 'Clicou'),0.96,O modelo identificou corretamente 96% de todos os cliques reais.
Erros Críticos (Falsos Negativos),6,Apenas 6 oportunidades de clique lucrativas foram perdidas em 300 casos testados.
