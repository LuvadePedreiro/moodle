## @035 L2 - Drone de Entrega - OBI 2017 - Fase 1

[](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/035/solver.c)
![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/035/__capa.jpg)

## Motivação

A loja do Pará, especializada em vendas pela internet, está desenvolvendo drones para entrega de caixas com as compras dos clientes. Cada caixa tem a forma de um paralelepípedo reto retângulo (ou seja, no formato de um tijolo).

O drone entregará uma caixa de cada vez, e colocará a caixa diretamente dentro da casa do cliente, através de uma janela. Todas as janelas dos clientes têm o formato retangular e estão sempre totalmente abertas. O drone tem um aplicativo de visão computacional que calcula exatamente as dimensões H e L da janela. O drone consegue colocar a caixa através da janela somente quando uma das faces da caixa está paralela à janela, mas consegue virar e rotacionar a caixa antes de passá-la pela janela.

O aplicativo de controle do drone está quase pronto, mas falta um pequeno detalhe: um programa que, dadas as dimensões da maior janela do cliente e as dimensões da caixa que deve ser entregue, determine se o drone vai ser capaz de entregar a compra (pela janela) ou se a compra terá que ser entregue por meios normais.

### Entrada

- A entrada é composta por cinco linhas, cada uma contendo um número inteiro. A três primeiras linhas contêm os valores A, B, C, indicando as três dimensões da caixa, em centímetros. As duas últimas linhas contêm os valores H e L, indicando a altura e a largura da janela, em centímetros.

### Saída

- Seu programa deve escrever uma única linha, contendo apenas a letra S se a caixa passa pela janela e apenas a letra N em caso contrário.

## Restrições

* 1 ≤ A, B, C ≤ 100
* 1 ≤ H, L ≤ 100

## Exemplos

```
>>>>>>>>
30
50
80
80
60
========
S
<<<<<<<<

>>>>>>>>
75
100
50
100
30
========
N
<<<<<<<<

>>>>>>>>
20
22
5
20
10
========
S
<<<<<<<<

```

## Dica

Você pode testar as 6 possibilidades de combinação pra ver se em alguma delas o pacote passa pela janela.
