## AULA 3
### Segmentação de Imagem

Segmentação de imagem é dividir a imagem em subregioes.

A união das regiões é a imagem inteira.

Duas regiões não partilham nada.

A primeira derivada é constante em zonas em que a imagem é constante.

A segunda derivada nos ajuda a perceber se trata-se de uma rampa. A indicaçao de que é uma rampa é porque tem uma sequencia de zeros entre um ponto e outro.

A grande diferença entre o step e a rampa é que no step a diferença entre o valor negativo e o valor positivo tem muito menos zeros. No caso apresentado em aula ele não possui nenhum zero e, portanto, a mudança é abrupta.

Para detectar linhas podemos usar o laplaciano para encontrar os contornos e depois a binarização para detectar linhas.

Derivadas amplificam o ruído.

Para atenuar os ruídos, utilizar filtros passa baixo.

Canny edge detection, detecta contornos com bastante clareza.

Thresholding: é uma binarização da imagem.