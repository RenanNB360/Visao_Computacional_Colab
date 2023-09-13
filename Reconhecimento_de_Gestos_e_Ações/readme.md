<h2>Reconhecimento de Gestos e Ações</h2>

Neste projeto utilizamos uma rede neural pré-treinada, pois utilizamos o Caffe Deep Learning Framework.
Primeiramente detectamos os pontos corporais de 0 a 14, depois efetuamos a ligação destes pontos e somente
depois poderemos detectar se houve alguma alteração em relação à posição inicial dos braços e pernas.

<h3>Resultado da Detecção de Gestos e Ações</h3>

![gestos](https://github.com/RenanNB360/Visao_Computacional_Colab/assets/87036785/e5289f5a-d5d3-4bdc-bd08-803f6e791ebc)

Levando em consideração que a pessoa em questão executou um movimento simples de polichinelo, conseguimos indicar 
quando o movimento está completo ao detectar que seus braços estão acima do ponto da cabeça e as pernas estão lateralmente
mais afastadas em relação ao ponto dos quadris.
