# MNIST from Scratch
<h2>A explicação deste código está em meu blog, confira: <a href="https://medium.com/@lorenzovarallo0/mnist-from-scratch-3335ca7b309b#8d94-4e851f4035af">MNIST From Scratch</a></h2>


![alt text](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

Algoritmo de Deep Learning utilizando apenas pacotes matemáticos de Python, utilizando o dataset MNIST de classificação de números, feito em Jupyter Notebook.

Criei esse projeto para entender mais profundamente os mecanismos de Deep Learning, sem utilizar de pacotes especializados, que não dão a certa intuição do que realmente está acontecendo, então resolvi olhar embaixo do capô :)

Esse programa eu fiz de modo que você pode escolher intuitivamente como será a estrutura interna, assim como os parametros utilizados:
```
model = MNISTalgorithm([784, 'relu', 200, 'sigmoid', 80, 'softmax', 10], epochs=10, alpha=0.1, batch_size=100)
```
É possivel acrescentar quantas camadas quiser, quantos neurônios em cada camada, e qual ativação entre elas, desde que a primeira e ultima camada tenham 784 e 10 neuronios respectivamente. As ativações podem ser Sigmoid ou Relu, mas a ultima ativação deve ser Softmax.

Este projeto pode ser muito útil para quem deseja entender melhor os mecanismos de Deep Learning, podendo: 
- Simular situações de Underfit/Overfit.
- Entender melhor o impacto de Learning Rate e Regularizador.
- Entender a diferença da utilização de SGD, Gradient descent, ou Batch Gradient descent.
- Entender a diferença na implementação de Relu ou Sigmoid.

É possivel atingir 98% de precisão no teste utilizando mais Epochs.

**Qualquer contribuição ao codigo é bem vinda!**
