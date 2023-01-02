# Descrição deste projeto

Este é um código em Python que usa a biblioteca TensorFlow para treinar um modelo de aprendizado de máquina para classificação de imagens de roupas. 
O conjunto de dados Fashion MNIST é carregado e dividido em um conjunto de treinamento e um conjunto de teste. O conjunto de treinamento é então pré-processado para redimensionar e converter as imagens em um formato de ponto flutuante. 
Uma padronização é aplicada aos conjuntos de treinamento e teste, para garantir que os dados estejam em uma escala semelhante.

Um modelo Sequencial é criado com três camadas densas, com ativações ReLU nas primeiras duas camadas e uma ativação Softmax na terceira camada. 
O modelo é compilado com a perda de entropia cruzada categórica esparsa como medida de perda e otimizador SGD. Um monitor de parada antecipada é adicionado para evitar overfitting. 
O modelo é então treinado por meio de um ajuste nas imagens de treinamento e alvos, usando um tamanho de lote de 10 e um número máximo de épocas de 500. 
Gráficos de perda e precisão são plotados a partir do histórico do treinamento do modelo. 
Por fim, o modelo é avaliado no conjunto de teste e as métricas de perda e precisão são exibidas.
