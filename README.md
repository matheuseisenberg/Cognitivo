# Cognitivo
Teste Cognitivo

O problema se refere aos dados de vinhos portugueses, que possuem variantes de vinho branco e tinto. Foi desenvolvido um modelo para estimar a qualidade dos vinhos.

A estratégia foi explorar os dados e fazer um método de classificação para os vinhos. 
As variáveis utilizadas foram as características dos vinhos e a variável target foi a nota (qualidade) do vinho.
Foi realizada a análise dos dados, tanto a verificação de dados missing quanto a correlação das variáveis e diferença de correlação entre os vinhos tinto e branco.
Para a modelagem, foi utilizado as técnicas de Random Forest e Stochastic Gradiente Decent (SGD).
Após os treinos dos modelos e testes, o F-score foi de 74% para o modelo de Rando Forest e de 61% para o SGD e a acurácia de 76% e 62% respesctivamente.
A data partition dividiu a base em 20% para teste e 80% para treinamento. O modelo de Random Forest teve um desempenho melhor ao modelo de SGD.
