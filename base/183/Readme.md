## @183 L2 - Criança ou Múmia


![](https://raw.githubusercontent.com/qxcodefup/moodle/master/base/183/__capa.jpg)

Leia o nome da pessoa e um inteiro que representa a idade de uma pessoa e escreva:

*   crianca se menor que 12 (não use o ç),
*   jovem se menor que 18,
*   adulto se menor que 65,
*   idoso se menor que 1000,
*   mumia caso contrario (não ponha o acento).

OBS: por simplificações, não faça flexão de gênero (idoso, idosa, adulto, adulta), não use acento, nem ç, nem maiúscula. 


### Exemplos

```
>>>>>>>>
mario
4
========
mario eh crianca
<<<<<<<<

>>>>>>>>
jose
65
========
jose eh idoso
<<<<<<<<
```

### Dica
Utilize a técnica do seleção intervalada e termine com um else sem condição.

```c
if(x < 12)  
    ...  
else if(x < 18)  
    ...
else if(x < 65)  
    ...
else
    ...
```

