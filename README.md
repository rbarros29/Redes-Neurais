# Trabalho de Redes Neurais
Alunos: 
Gabriel Gontijo
RA - 121118394
Rafael Barros
RA - 121116933
<h1>Relatório Final</h1>

<h3>Pesquisa Teórica</h3>

O aprendizado supervisionado é um tipo de aprendizado de máquina onde o
modelo é treinado com um conjunto de dados rotulados, ou seja, cada exemplo de
entrada é acompanhado de uma saída correta. Durante o treinamento, o modelo
aprende a mapear entradas para as saídas corretas, ajustando seus parâmetros
com base no erro observado (diferença entre a previsão e a saída real). O
aprendizado supervisionado e o não supervisionado diferem principalmente pela
presença ou ausência de rótulos nos dados de treinamento.

Uma rede neural artificial é composta por vários elementos chamados neurônios,
organizados em camadas. Sua estrutura básica é dividida em três partes principais:
camada de entrada, camadas ocultas e camada de saída. A Camada de entrada
recebe os dados brutos que são processados pela rede neural. Enquanto a camada
oculta executa os cálculos intermediários que permitem à rede aprender padrões e
características dos dados. A camada de saída produz a previsão ou a saída final da
rede neural com base nos dados processados pelas camadas ocultas.

<h3>Código Fonte</h3>

https://colab.research.google.com/drive/1cLm6OfumR2yY7TN_tJAlcS6d-2SaydjC?usp=sharing

<h3>Análise dos resultados</h3>

O objetivo da rede neural era classificar imagens usando o dataset MNIST.

A rede é composta por 3 camadas principais: a camada de entrada, que recebe os
dados a serem processados; a camada oculta, que executa cálculos intermediários
e permitem a rede aprender padrões complexos dos dados; a camada de saída, que
produz a saída final da rede neural com base no processamento das camadas
ocultas.

O modelo é treinado por 5 épocas, e após o treinamento, o modelo é avaliado e a
acurácia é impressa. Foi utilizada a biblioteca Matplotlib para plotar a acurácia do
treinamento e da validação ao longo de cada época.

O gráfico a seguir mostra a diminuição do erro tanto no conjunto de treinamento quanto no
conjunto de validação ao longo das épocas.

![image](https://github.com/user-attachments/assets/18cf177d-35d9-4121-9e0a-f85c410c3d47)

<h3>Conclusões e possíveis melhorias</h3>

A rede neural alcançou uma baixa perda final: 0.12 no conjunto de treinamento e
0.17 no conjunto de teste. Essa diferença entre os conjuntos sugere que o modelo
generaliza bem e não sofreu overfitting. A rede conseguiu uma boa performance em
comparação com algoritmos de regressão logística, mas ainda fica atrás de redes
neurais convolucionais.



