## @099 L3 - Francês é Fresco
### Juntar palavras

![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/099/solver.c)
![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/099/__capa.jpg)

## Motivação

Ja percebeu que quando temos que o final de uma palavra, quando é uma vogal e combina com a próxima palavra nós juntamos as duas?

Isso tem um nome legal, em frances se chama liaison. Em português eu acho que não tem um nome legal assim.

## Ação

Que tal fazer um código que faz isso? Dado uma entrada de texto (max 100 char) apenas com minúsculo e espaço faça o liaison das palavras. Há apenas um espaço entre as palavras e não existe espaço no começo ou fim da frase.

Se tiver 3 ou mais vogais juntas so junte todas amo o orvalho -> amorvalho

o gago disse e e e eu te amo -> o gago disseu te amo

### Entrada

*   Um texto. (max 100 char)

### Saída

*   O liaison das palavras.

## Exemplos

```
>>>>>>>>
a porta amassou
========
a portamassou
<<<<<<<<

>>>>>>>>
carla almeida alencar
========
carlalmeidalencar
<<<<<<<<

>>>>>>>>
a carla a ama
========
a carlama
<<<<<<<<

>>>>>>>>
o orvalho ouviu uniformemente e eu uivei
========
orvalhouviuniformementeuivei
<<<<<<<<
```

#
