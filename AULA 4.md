# AULA 4

### Notebook 01
Cada unidade das redes neuronais são extremamente simples, a capacidade deles de processamento é dado pelo conjunto das unidades.

Neuronios tem inputs, que podem vir de fora, e os neuronios somam os inputs pelos pesos atribuidos e processa através de uma função e faz o output, que irá para outros neuronios ou o fim da rede.

A rede é definida pelos pesos, que são nossos parametros.

Caso a rede esteja errada, nós temos que mudar os pesos para mudar a resposta.

As funções de ativação não podem ser lineares.

### Notebook 02

As probabilidades de saida das redes neuronais tem de ser igual a 1. 
    > Exemplo: se tiver 0,7% de chance de ser um gato, 0,2% de ser um cachorro e 0,1% de ser um crocodilo, a somatório das probabilidades é 1 e o output é gato.

Softmax só é usado fora da rede, não dentro da rede, pois serve para interpretar os outputs da rede.

### Notebook 03

A funçao de erro recebe dois argumentos, o target e o output.

O uso pode ser simples como elevar tudo ao quadrado, o nome disso é Mean Squared Error.
    > soma a diferença entre o output e o target e eleva ao quadrado.

Cross Entropy é a mais usada, que multiplica o target pelo logaritimo do output.

### Notebook 04

O que é feito para treinar a rede: vamos passar *n samples* (normalmente multiplos de 2), ao fim dessas samples vamos atualizar os pesos. 

    > Exemplo: O dataset pode ter milhões de imagens e então é dividido por batches (n samples), e atualizará os pesos a cada batch.

Taxa de aprendizagem: Não da pra usar valores muito pequenos pois vai demorar muito tempo e pode não fechar e com uma taxa de aprendizagem muito alta vai ficar em erro.

### Notebook 05

Tensor é uma variavel com n dimensões.

Autograd calcula a derivada. É isso que torna estas plataformas tão poderosas.


