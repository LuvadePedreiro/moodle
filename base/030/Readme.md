## @030 L2 - Mercantil V1 - Quem chega mais perto

[](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/030/solver.c)
![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/030/__capa.jpg)

## Descrição

Pedro e João foram no Silvio Santos. O programa era aquele que o Silvio mostrava um produto do mercantil, ambos os participantes chutavam o preço e a pessoa que chegasse mais próximo do preço real ganhava.

O objetivo do seu programa é informar quem ganhou a disputa. Você receberá o valor do produto e o valor do chute de cada jogador. O jogador que chegar mais perto ganha.

Se ambos ficarem à mesma distancia do valor real, então houve empate.

[DS]

### Entrada
* linha 1: o valor do produto.(valor inteiro entre 1 e 100)
* linha 2: o chute do Primeiro
* linha 3: o chute de Segundo

### Saída
* "primeiro" se o chute do Primeiro for o mais próximo do valor do produto
* "segundo" se o chute do Segundo for o mais próximo do valor do produto
* "empate" caso ambos ficarem à mesma distancia

## Exemplos

```
>>>>>>>>
1
2
3
========
primeiro
<<<<<<<<

>>>>>>>>
3
5
4
========
segundo
<<<<<<<<

>>>>>>>>
10
11
9
========
empate
<<<<<<<<

>>>>>>>>
20
21
22
========
primeiro
<<<<<<<<

>>>>>>>>
20
21
21
========
empate
<<<<<<<<
```

## Ajuda

* Ao ser realizado a diferença entre o chute de um jogador e o valor do produto, o resultado pode ser negativo. Para eliminar esse resultado negativo existe a função `abs`.
* A função `abs` retorna o valor absoluto de um número, ou seja, o valor do número sem sinal.

Observação

* Para ser utilizada a função `abs`, ela deve ser importada. Segue as formas de importação em algumas linguagens e como utilizar:

```c
#include <math.h> //c

abs(-3) //retorna 3
```
```c++
#include <cmath> //c++

abs(-3) //retorna 3
```
```python
#python
abs(-3) #retorna 3
```
```javascript
//javascript 
Math.abs(-3) //retorna 3
```


