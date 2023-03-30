# Universidade de Vassouras Campus Maricá
![logoFacul](https://user-images.githubusercontent.com/109771351/228919209-3b0e8d9c-bb31-425d-9e80-dd53180bcd6f.png)
# Curso de Engenharia de Software
![engSoftware](https://user-images.githubusercontent.com/109771351/228922918-bc9b864f-57bf-443d-a45c-7b127f923eef.jpeg)


## Projeto 5 - Descrição do Problema:

O problema consiste em encontrar a posição de cada elemento em um conjunto e imprimir as coordenadas em ordem ascendente, bem como calcular o somatório de todos os elementos que possuem o mesmo valor e apresentar esses valores. Além disso, o objetivo é plotar a notação Big O do resultado.

### Matriz dada 6x6 :

    1 1 1 0 0 0
    0 1 0 0 0 0
    1 1 1 0 0 0
    0 0 2 4 4 0
    0 0 0 2 0 0
    0 0 1 2 4 0

## Tecnicas Utilizadas para a Resolução do Problema:

As técnicas utilizadas no código incluem o uso de estruturas de controle de fluxo condicionais (if/elif/else) para verificar se o valor em cada posição da lista é igual a 1, 2 ou 4. Caso seja igual, a posição é adicionada a uma lista correspondente (ocorrencia1, ocorrencia2 ou ocorrencia4) e o contador correspondente é incrementado.

O código também utiliza a biblioteca matplotlib para plotar um gráfico da complexidade de tempo do algoritmo, que neste caso é constante, uma vez que o tempo de execução não varia em função do tamanho da entrada.

O gráfico é gerado com valores fixos para o eixo x (representando o tamanho da entrada) e para o eixo y (representando o tempo de execução constante), permitindo visualizar de forma gráfica que o tempo de execução do algoritmo não varia com o tamanho da entrada.
*******************
## Para Facilitar a Compreenção o Codigo foi Separado em 3 Partes: 
******************
### Parte  1/3

![explicaçao1](https://user-images.githubusercontent.com/109771351/228927904-64e8d11c-e412-4170-a6c8-59731547fb47.jpg)

Essa primeira parte do código cria uma lista chamada lista1 com uma sequência de números inteiros. 
Em seguida, três listas vazias são criadas: ocorrencia1, ocorrencia2 e ocorrencia4.
A partir do for loop que se segue, cada elemento da lista lista1 é percorrido e, caso seja igual a 1, 2 ou 4, sua posição na lista é adicionada à respectiva lista (ocorrencia1, ocorrencia2 ou ocorrencia4). Caso contrário, o loop segue para o próximo elemento.

*******************
### Parte  2/3

![explicaçao2](https://user-images.githubusercontent.com/109771351/228927952-59eeaeba-3edd-4f65-9965-e5eb88834979.jpg)

Essa Segunda Parte do código é responsável por imprimir as informações obtidas a partir da lista de entrada lista1 e das listas de ocorrências ocorrencia1, ocorrencia2 e ocorrencia4.
A primeira linha imprime uma mensagem de boas-vindas e identifica o projeto.
As três linhas seguintes imprimem as posições em que a ocorrência do número 1, 2 e 4 foram encontradas, respectivamente. As informações são obtidas a partir das listas ocorrencia1, ocorrencia2 e ocorrencia4, que foram preenchidas durante a execução do laço for.
Em seguida, é impressa a quantidade de ocorrências de cada número e a soma das ocorrências de cada número multiplicado pelo próprio número. Essas informações são obtidas a partir das funções len e operações aritméticas simples.
Por fim, é utilizado o caractere de repetição * para imprimir uma linha pontilhada que serve como separador visual para facilitar a leitura e identificação dos resultados obtidos.
*******************
### Parte  3/3

![explicaçao3](https://user-images.githubusercontent.com/109771351/228927976-c7990e6c-624e-49d9-b378-7c9c8310f926.jpg)

E por fim esta parte do código usa a biblioteca matplotlib.pyplot para gerar um gráfico simples que ilustra a relação entre o tamanho da entrada e o tempo de execução do algoritmo.
Os valores para o eixo x são definidos como uma lista que contém os números inteiros de 1 a 36 (nesse exemplo). Esses valores representam o tamanho da entrada do algoritmo em estudo.
Os valores para o eixo y são definidos como uma lista que contém o número 1 repetido 36 vezes. Isso representa uma complexidade de tempo constante, indicando que o tempo de execução do algoritmo não muda à medida que o tamanho da entrada aumenta.
A função plt.plot() é usada para traçar um gráfico de linha simples com os valores de x_values no eixo x e y_values no eixo y.
As funções plt.xlabel() e plt.ylabel() são usadas para adicionar rótulos descritivos aos eixos x e y, respectivamente.
Finalmente, a função plt.show() é chamada para exibir o gráfico na tela.
*******************
### Materia: Estrutura de Dados - Turma B - 3º período.
### Integrantes do Grupo: Paulo victor Melo,Luan Santos,Marcos Reis,João Pedro e Denis.
### Professor: Marcio Garrido
