## @106 L2 - Valdiskley e a cifra V2!


![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/106/__capa.jpg)

## Motivação

Valdiskley é muito nerd e depois de estudar criptografia ele bolou um plano infalível para conquistar o amor da sua vida. Seu plano é o seguinte:  
Ele vai escrever várias cartinhas criptografadas pra ela e só vai dizer a senha pra ela descriptografar as cartinhas de amor se ela aceitar namorar com ele.

## Ação

Acompanhe o desenrolar da história de amor de Valdiskey por Valentina em 3 capítulos.

No capítulo 1 você precisa ser capaz de realizar a operação de cifragem básica com dois caracteres.

No capítulo 2 você vai escrever o algoritmo que permite a Valentina usar a chave para descobrir o conteúdo das cartinhas de amor.

No capítulo 3 você vai usar um algoritmo de força bruta para "quebrar" a criptografia do pedido de casamento.

Na operação entre dois caracteres podemos imaginar uma lista circular onde o 'a' reinicia depois do 'z'. Você pode pensar que 'a' vale 0, 'b' vale 1 e assim por diante.

```
a + a = a 
a + b = b   
b + a = b 
b + b = c 
c + c = e 
c + b = d 
d + e = h
...

z + a = z
z + b = a
```

Na descriptografia utilizamos a operação inversa.

```
c - a = c
c - b = b
c - c = a
c - d = z
c - e = y  
```
### Entrada

*   Um caractere minusculo.
*   Linha: a operação '-' ou '+'.
*   Linha: Um segundo caractere minúsculo.

### Saída

*   O resultado da operação de criptografia ou descriptografia.  

## Exemplos

```
>>>>>>>>
a
+
a
========
a
<<<<<<<<

>>>>>>>>
b
+
d
========
e
<<<<<<<<

>>>>>>>>
z
+
c
========
b
<<<<<<<<

>>>>>>>>
f
-
d
========
c
<<<<<<<<

>>>>>>>>
b
-
c
========
z
<<<<<<<<

>>>>>>>>
b
+
b
========
c
<<<<<<<<
```

#
