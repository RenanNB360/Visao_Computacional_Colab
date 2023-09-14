<h2>Segmentação de Imagem</h2>

Para este projeto utilizamos uma rede neural convolucional a Mark R-CNN onde efetuação uma segmentação por
instancia. Tivemos que recorrer uma rede neural adaptada para o TensorFlow 2, pois o Colab executa somente 
a partir da versão 2.x e no momento que a rede neural convolucional foi desenvolvida estava em vigor a versão
1.x.

<h3>Resultado da Segmentação</h3>

![seg](https://github.com/RenanNB360/Visao_Computacional_Colab/assets/87036785/89ad2aac-1ef5-4875-9506-5b10cb0312b5)

Utilizamos a base de dados do Coco com 80 categorias, tivemos bons resultados para as classes detectadas na imagem tanto 
para segmentação ou remoção do fundo.
