## @108 L3 - Identificando elementos


![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/108/__capa.jpg)

## Ação

Dada uma frase(max 100 char) com palavras(letras minusculas), números, espaço e ponto, identifique os elementos como str, int ou float.

Analise cada palavra\[max 10 char na palavra\].

Regras:

Float tem o ponto.  
Int contem não tem ponto.  
Int e float podem ser negativos.  
Se existir pelo menos um alfabético então é string.

### Entrada

*   Uma frase(max 100 char) com palavras(letras minusculas), números, espaço e ponto

### Saída

*   o tipo de cada palavra( str, float ou int) separado por espaço.  

## Exemplos  

```
>>>>>>>> 01
tenho 15 4nos 1.75 altur4 -15 conto p0rr4 -4.04
========
str int str float str int str str float
<<<<<<<<


>>>>>>>> 02
a proxima eleição presidencial no Brasil ocorrerá em 2 de outubro de 2018
========
str str str str str str str str int str str str int
<<<<<<<<
```

<!--
>>>>>>>> 03
aa 1 -2.0
========
str int float
<<<<<<<<


>>>>>>>> 04
02a -x1 -4.b54 p0
========
str str str str
<<<<<<<<


>>>>>>>> 05
-pato -40 -5.4
========
str int float
<<<<<<<<


>>>>>>>> 06
02 -1 -4.54 p0
========
int int float str
<<<<<<<<
-->
