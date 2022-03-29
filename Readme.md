# QxcodeFup

<!--TOC_BEGIN-->
- [01. Operações](#01-operações)
    - [Conteúdo sugeridos](#conteúdo-sugeridos)
    - [Impressão formatada(casas decimais e zeros à esquerda)](#impressão-formatadacasas-decimais-e-zeros-à-esquerda)
    - [Escrevendo Expressões (sqrt, pow)](#escrevendo-expressões-sqrt-pow)
    - [Operador de módulo](#operador-de-módulo)
- [02. Seleção](#02-seleção)
    - [Conteúdo sugerido](#conteúdo-sugerido)
    - [Manipulação de Ifs e Elses e Fórmulas](#manipulação-de-ifs-e-elses-e-fórmulas)
    - [Lógica](#lógica)
    - [Biblioteca Math: ceil, floor, round, abs](#biblioteca-math-ceil-floor-round-abs)
    - [Operador de módulo](#operador-de-módulo)
    - [Operadores lógicos](#operadores-lógicos)
    - [Seleção Intervalada](#seleção-intervalada)
    - [Busca e Contagem](#busca-e-contagem)
    - [Conversão de bases](#conversão-de-bases)
- [05. Repetição](#05-repetição)
    - [Conteúdo sugerido](#conteúdo-sugerido)
    - [While e técnicas de controle (break e continue)](#while-e-técnicas-de-controle-break-e-continue)
    - [For (controle de laço)](#for-controle-de-laço)
    - [For (múltiplso controles)](#for-múltiplso-controles)
    - [Math](#math)
    - [Decomposição de Inteiros](#decomposição-de-inteiros)
- [08. Vetores I](#08-vetores-i)
- [09. Vetores II](#09-vetores-ii)
- [10. Vetores Extra](#10-vetores-extra)
- [11. Strings I](#11-strings-i)
- [12. Strings II](#12-strings-ii)
- [13. String III](#13-string-iii)
- [14. String Extra](#14-string-extra)
- [15. Matrizes I](#15-matrizes-i)
- [16. Matrizes II](#16-matrizes-ii)
- [17. Matrizes Extra](#17-matrizes-extra)
- [18. Funções e Ponteiros](#18-funções-e-ponteiros)
- [19. Recursão](#19-recursão)
- [20. Structs](#20-structs)
<!--TOC_END-->


## 01. Operações

### Conteúdo sugeridos
    - instalando o mingw e vscode
    - tipos de dados básicos: `bool, int, float, char, const char *`
    - operadores aritméticos: `+ - * / %`
    - lendo e escrevendo variáveis: scanf, printf, puts, getchar
    - uso avançado do scanf
    - maldição da leitura do char, lendo ou ignorando whitespaces
    - lendo errado a entrada, limpando o buffer
    - como funciona o buffer de entrada
    - utilizando funções da biblioteca math.h
    - debugando

### Impressão formatada(casas decimais e zeros à esquerda)
- [@000 @000 L1 - Operações básicas - Imprimindo float formatado](base/000) 

### Escrevendo Expressões (sqrt, pow)
- [@002 @002 L2 - Pintando a casa - Calculando a área do triângulo](base/002) 
- [@003 @003 L2 - Opala bebedor - Cálculo de desempenho do motor](base/003) 
- [@196 @196 L2 - Comprando TV parcelado](base/196) 
- [@004 @004 L3 - Mete bala - Distância entre dois pontos](base/004) 

### Operador de módulo
- [@195 @195 L2 - Xadrez OBI 2019 F1P1](base/195) 
- [@193 @193 L2 - Dominó - OBI 2019 F1PJ](base/193) 
- [@011 @011 L2 - Formatando data - Casas decimais e operador de módulo](base/011) 


## 02. Seleção

### Conteúdo sugerido
    - Funções
        - recebendo e retornando básicos
        - retorno de função: retorno default e returnos parciais ao invés de elses
    - Estruturas de Seleção
        - Indentação, estruturas básicas e uso de operadores lógicos de corte
        - if, else, else if
        - Operadores lógicos: `&&, ||, !`
        - Operadores relacionais: `==, !=, >, <, >=, <=`
        - Operador ternário


### Manipulação de Ifs e Elses e Fórmulas
- [@015 @015 L1 - Calculadora Numérica](base/015) 
- [@155 @155 L1 - Plantação de Morangos](base/155) 
- [@151 @151 L1 - Impedido!](base/151) 
- [@026 @026 L1 - Positivo, Nulo ou Negativo?](base/026) 
- [@031 @031 L2 - Fiquei de final](base/031) 
- [@040 @040 L2 - Está Trabalhando ou Não!](base/040) 
- [@001 @001 L2 - Sai fora Bhaskara (Cálculo de raízes)](base/001) 

### Lógica
- [@157 @157 L1 - Frota de Táxi - OBI 2005](base/157) 
- [@014 @014 L1 - Quantos são iguais? (Contando Repetidos)](base/014) 
- [@156 @156 L2 - Jogo de par ou ímpar - OBI 2016 - F1P1](base/156) 
- [@022 @022 L2 - Teleférico - OBI 2017 - Fase 1](base/022) 
- [@194 @194 L2 - Nota cortada - OBI 2019 F1P1](base/194) 

### Biblioteca Math: ceil, floor, round, abs
- [@018 @018 L2 - Arredondar](base/018) 
- [@030 @030 L2 - Mercantil V1 - Quem chega mais perto](base/030) 

### Operador de módulo
- [@024 @024 L1 - Divisão Inteira e Quebrada](base/024) 
- [@062 @062 L1 - Angulo Cartesiano](base/062) 
- [@025 @025 L1 - Ambos Divisíveis](base/025) 
- [@005 @005 L2 - Ladrão de Goiabas - Contando viagens usando módulo](base/005) 
- [@028 @028 L2 - Cadê a cabeça da cobra](base/028) 
- [@016 @016 L2 - Volta de 360 graus (Retirando os loops)](base/016)  [](#repetição)
- [@019 @019 L2 - OBI 2017 - Fase 1 - Universitário - Game 10](base/019) 
- [@034 @034 L3 - Formiga da bundona](base/034)  [](#seleção)
- [@006 @006 L3 - Zerinho ou um americano - Decifrando a fórmula](base/006) 
- [@037 @037 L3 - Jokenpo 15](base/037)  [](#seleção)

### Operadores lógicos
- [@023 @023 L2 - Jokenpo das tartarugas!](base/023) 
- [@039 @039 L2 - Mercantil V2 - Maior ou Menor](base/039) 
- [@035 @035 L2 - OBI 2017 - Fase 1 - Drone de Entrega](base/035) 
- [@020 @020 L2 - Zerinho ou Um!](base/020)  [](#seleção)

### Seleção Intervalada
- [@021 @021 L2 - Aumento de Salário](base/021)  [](#seleção)
- [@032 @032 L2 - Bolada na fuça](base/032)  [](#seleção)
- [@183 @183 L2 - Criança, Adulto, Idoso, Múmia](base/183)  [](#seleção)

### Busca e Contagem
- [@017 @017 L2 - Ovos de galinha (Procurando o Maior valor)](base/017)  [](#seleção)
- [@192 @192 L2 - A idade de Dona Mônica - OBI 2019 - F1PJ](base/192) 
- [@029 @029 L2 - Quiz do Harry Potter](base/029)  [](#seleção)
- [@036 @036 L3 - Morre o do meio](base/036)  [](#seleção)
- [@033 @033 L3 - Professor Bonzinho](base/033)  [](#seleção)

### Conversão de bases
- [@038 @038 L2 - A hora do próximo segundo](base/038)  [](#seleção)
- [@027 @027 L2 - Adedonha na Califórnia](base/027)  [](#seleção)
- [@043 @043 L3 - Dorme Tarde Acordar Cedo!](base/043)  [](#seleção)


## 05. Repetição
### Conteúdo sugerido
    - Seleção: if, else, else if
    - Controle: for, while, do while
    - Controle de laço: break, continue
    - Funções com returns parciais

### While e técnicas de controle (break e continue)
- [@053 @053 L2 - OBI 2016 - Fuga em helicóptero](base/053)  [](#repetição)
- [@047 @047 L2 - Ônibus lotado](base/047)  [](#repetição)
- [@049 @049 L2 - Sapinho 1 no Poço](base/049)  [](#repetição)
- [@059 @059 L3 - Sapinho 2 morrendo no poço](base/059)  [](#repetição)
- [@065 @065 L3 - Sapinho 3 matemático não morrendo no poço](base/065)  [](#repetição)

### For (controle de laço)
- [@013 @013 L1 - Dividindo pares de sapatos pra três](base/013)  [](#repetição)
- [@045 @045 L1 - Zero é par - Somatório de Pares!](base/045)  [](#repetição)
- [@050 @050 L2 - Castelos de Cubos](base/050)  [](#repetição)
- [@054 @054 L3 - Quebrador de Copos](base/054)  [](#repetição)

### For (múltiplso controles)
- [@046 @046 L2 - Jogo da Concentração](base/046)  [](#repetição)

### Math
- [@090 @090 L2 - Primo](base/090)  [](#vetores)
- [@189 @189 L2 - Fatores de um número](base/189)  [](#repetição)
- [@052 @052 L3 - Hoje tem sopa de coelho?](base/052)  [](#repetição)
- [@160 @160 L3 - Somatório de Fibonacci](base/160)  [](#repetição)

### Decomposição de Inteiros
- [@066 @066 L2 - Spok Palíndromo](base/066)  [](#repetição)
- [@064 @064 L3 - Conta Dígitos](base/064)  [](#repetição)


## 08. Vetores I

- Separar questões de vetores: 
    - pode usar algumas das divisões que está lá no estressado github.com/senapk/estressados

- Adaptar essas questões de vieram de repetição para vetor
- [@056 @056 L1 - Calça apertada - Mínimo](base/056)  [](#repetição)
- [@055 @055 L1 - Ultrons - Contar Elemento](base/055)  [](#repetição)
- [@058 @058 L2 - Busca Intervalada](base/058)  [](#repetição)
- [@048 @048 L2 - Cabo de Guerra Jedi](base/048)  [](#repetição)
- [@057 @057 L2 - Revolta em Portugal](base/057)  [](#repetição)
- [@136 @136 L2 - Trilhas - OBI 2005 - (Modo Easy)](base/136)  [](#repetição)
- [@051 @051 L3 - Arremesso de pedra na lua](base/051)  [](#repetição)
- [@063 @063 L3 - Blackjack 21!](base/063)  [](#repetição)

- Questões de vetores

- [@060 @060 L1 - Joelison Fernandes - Soma do maior e menor!](base/060) 
- [@061 @061 L2 - Capoeira invertendo vetor!](base/061) 
- [@078 @078 L2 - Jogo do Avesso](base/078)  [](#vetores)
- [@091 @091 L2 - MMC](base/091)  [](#vetores)
- [@101 @101 L2 - Mostrar mão de cartas](base/101)  [](#vetores)
- [@068 @068 L2 - Organizando a fila do RU](base/068)  [](#vetores)
- [@186 @186 L2 - Processando uma linha de inteiros](base/186)  [](#vetores)
- [@067 @067 L2 - Queda de dominós](base/067)  [](#vetores)
- [@072 @072 L2 - Soldados Pequenos e Grandes!](base/072)  [](#vetores)
- [@075 @075 L3 - Abastecimento de água](base/075)  [](#vetores)
- [@083 @083 L3 - Anfíbios e Batráquios - Está contido](base/083)  [](#vetores)

## 09. Vetores II

- [@082 @082 L3 - As unhas de Luiza - Vetor para inteiro](base/082)  [](#vetores)
- [@080 @080 L3 - Baruel Ruel trocando figurinhas!](base/080)  [](#vetores)
- [@073 @073 L3 - Batida Policial - Ordenando vetores](base/073)  [](#vetores)
- [@010 @010 L3 - Bolinhas viciadas(contagem de repetições)](base/010)  [](#vetores)
- [@070 @070 L3 - Cabeças vão rolar](base/070)  [](#vetores)
- [@086 @086 L3 - Coleção de Tazos - Quantos se repetem mais](base/086) 
- [@071 @071 L3 - Mário e o Assassin's Creed - Parkour](base/071)  [](#vetores)
- [@188 @188 L3 - Devolvendo o troco com vetores](base/188)  [](#vetores)
- [@085 @085 L3 - Exército - Perto da morte](base/085)  [](#vetores)
- [@100 @100 L3 - Jogando pião na rodinha](base/100)  [](#vetores)
- [@079 @079 L3 - Jogo do Avesso V2](base/079)  [](#vetores)
- [@081 @081 L3 - Loucura de Marquinhos - Decompor um inteiro](base/081)  [](#vetores)

## 10. Vetores Extra

- [@138 @138 L3 - Permutação](base/138)  [](#vetores)
- [@087 @087 L3 - Zoológico Entrando na Arca de Noé](base/087)  [](#vetores)
- [@069 @069 L3 - Zoo quantas especies!](base/069)  [](#vetores)
- [@088 @088 L3 - Se fosse a mediana eu tinha passado!](base/088)  [](#vetores)
- [@008 @008 L3 - Força Bruta (Gerando próxima combinação)](base/008)  [](#vetores)
- [@077 @077 L3 - Mercantil V3 - Muitas rodadas](base/077)  [](#vetores)
- [@074 @074 L3 - OBI 2017 - Fase 1 - Botas Trocadas](base/074)  [](#vetores)
- [@076 @076 L3 - OBI 2017 - Fase 1 - O segredo do Cofre](base/076)  [](#vetores)
- [@084 @084 L3 - Zoológico Um animal de cada tipo!](base/084)  [](#vetores)
- [@190 @190 L4 - Maiores Palíndromos](base/190)  [](#repetição)
- [@158 @158 L3 - Trilhas - OBI 2005](base/158)  [](#repetição)
- [@161 @161 L3 - Vivo ou Morto - OBI 2005](base/161)  [](#repetição)

## 11. Strings I

- [@173 @173 L1 - Eribelton e a Ascologia V1 - Somar Asc](base/173)  [](#strings)
- [@092 @092 L1 - LP da Xura - Inverter String!](base/092)  [](#strings)
- [@104 @104 L1 - Maiúsculo, Minusculo e Dígito!](base/104)  [](#strings)
- [@177 @177 L1 - Marileuza e as Alcaparras - Contar Ocorrencias!](base/177)  [](#strings)
- [@176 @176 L1 - Substring na decoração - Obter Substrings!](base/176)  [](#strings)
- [@174 @174 L1 - Valdiskey e a cifra V1!](base/174)  [](#strings)
- [@095 @095 L2 - Avestruz com Alcaparras](base/095)  [](#strings)
- [@096 @096 L2 - Contar Leds](base/096)  [](#strings)
- [@126 @126 L2 - Crushômetro](base/126)  [](#strings)
- [@109 @109 L2 - Eribelton e a Ascologia V2](base/109)  [](#strings)
- [@097 @097 L2 - Gagueira V1 - Duplicar Palavras](base/097)  [](#strings)
- [@093 @093 L2 - Gritando em Caixa Alta](base/093)  [](#strings)

## 12. Strings II

- [@180 @180 L2 - Guerra Civil no Universo Marvel](base/180)  [](#strings)
- [@089 @089 L2 - Mega Jokenpo!](base/089)  [](#strings)
- [@111 @111 L2 - Meu cachorro comeu minha tarefa](base/111)  [](#strings)
- [@125 @125 L2 - Numerão Divisível por 11](base/125)  [](#strings)
- [@110 @110 L2 - Organizando Ru - Homens e Mulheres!](base/110)  [](#strings)
- [@181 @181 L2 - Somando numeros](base/181)  [](#strings)
- [@106 @106 L2 - Valdiskley e a cifra V2!](base/106)  [](#strings)
- [@094 @094 L2 - Vogais e Consoantes](base/094)  [](#strings)
- [@163 @163 L4 - Permutação Lexograficamente Final de Fichas](base/163)  [](#string)
- [@127 @127 L3 - Amo a Amora meu Amor](base/127)  [](#strings)
- [@124 @124 L3 - Conversa de Traficantes](base/124)  [](#strings)
- [@113 @113 L3 - Eribelton e a Ascologia V3](base/113)  [](#strings)

## 13. String III

- [@099 @099 L3 - Francês é Fresco](base/099)  [](#strings)
- [@120 @120 L3 - Gansos Gamados](base/120)  [](#strings)
- [@117 @117 L3 - Identificando Ultrons V2](base/117)  [](#strings)
- [@118 @118 L3 - Aniquilando Ultrons V3](base/118)  [](#strings)
- [@108 @108 L3 - Identificando elementos](base/108)  [](#strings)
- [@178 @178 L3 - Jack Sparrow e o Beijinho](base/178)  [](#strings)
- [@098 @098 L3 - Jason e Krueguer](base/098)  [](#strings)
- [@152 @152 L3 - Letras Ordenadas](base/152)  [](#strings)
- [@119 @119 L3 - Matéria e Antimatéia](base/119)  [](#strings)
- [@114 @114 L3 - MeU WoRd QuEbRoU](base/114)  [](#strings)
- [@102 @102 L3 - Meu cachorro comeu minha tarefa V2](base/102)  [](#strings)
- [@115 @115 L3 - Máquina de Datilografar Quebrada](base/115)  [](#strings)

## 14. String Extra

- [@121 @121 L3 - Mário e o Assassins Creed](base/121)  [](#strings)
- [@122 @122 L3 - Nao se bububula - Gagueira V2!](base/122)  [](#strings)
- [@179 @179 L3 - Prof Muquirana - Busca máximo por critério](base/179)  [](#strings)
- [@112 @112 L3 - Rocicleia e o Locioreca - Anagramas!](base/112)  [](#strings)
- [@116 @116 L3 - Roda Roda Jequiti](base/116)  [](#strings)
- [@175 @175 L3 - Separando a partir de tokens](base/175)  [](#strings)
- [@103 @103 L3 - Separe Pneumatocito - Separação de Palavras!](base/103)  [](#strings)
- [@123 @123 L3 - Sorvete suor casaca chicletes - Letras em Comum!](base/123)  [](#strings)
- [@107 @107 L3 - Valdiskley e a Cifra v3!](base/107)  [](#strings)
- [@105 @105 L3 - Valdiskley e cifras históricas!](base/105)  [](#strings)
- [@162 @162 L3 - Mini-Poker - OBI2005](base/162) 
- [@041 @041 L3 - Criptografia](base/041)  [](#string)


## 15. Matrizes I

- [@130 @130 L2 - Bingo!](base/130)  [](#matrizes)
- [@012 @012 L2 - Deu a louca no Imperador!](base/012)  [](#matrizes)
- [@191 @191 L2 - Coluna de Valor Maior](base/191)  [](#matrizes)
- [@134 @134 L2 - Quadrado Mágico](base/134)  [](#matrizes)
- [@128 @128 L2 - Soma de elementos de em uma matriz](base/128)  [](#matrizes)
- [@153 @153 L3 - OBI 2015 - Fase 2 - Nível 1 - Torre](base/153)  [](#matrizes)

## 16. Matrizes II

- [@133 @133 L2 - Soldados em Posição](base/133)  [](#matrizes)
- [@131 @131 L2 - Matriz Simétrica](base/131)  [](#matrizes)
- [@150 @150 L2 - Soma de matrizes](base/150)  [](#matrizes)
- [@132 @132 L2 - Subdiagonais](base/132)  [](#matrizes)
- [@135 @135 L3 - Jogo da vida](base/135)  [](#matrizes)
- [@007 @007 L3 - Tetris (Fazendo a peça cair)](base/007)  [](#matrizes)

## 17. Matrizes Extra

- [@129 @129 L3 - Campo Minado](base/129)  [](#matrizes)
- [@159 @159 L3 - Campo de Minhocas - OBI 2005](base/159)  [](#matrizes)
- [@154 @154 L3 - OBI 2015 - Fase 2 - Nível Júnior - Código](base/154)  [](#matrizes)

## 18. Funções e Ponteiros

- [@009 @009 L2 - Imprimir vetor formatado](base/009)  [](#funções)
- [@139 @139 L4 - A Porta Matemática](base/139)  [](#funcoes)
- [@147 @147 L1 - Duelo](base/147)  [](#ponteiros)
- [@143 @143 L1 - Troca de valores de variáveis](base/143)  [](#ponteiros)
- [@144 @144 L2 - Função que retorna vários valores por referência](base/144)  [](#ponteiros)
- [@142 @142 L2 - Vetor de strings com variados tamanhos](base/142)  [](#ponteiros)

## 19. Recursão

- [@145 @145 L2 - Contando caracteres recursivamente](base/145)  [](#recursão)
- [@141 @141 L2 - Números de Fibonacci](base/141)  [](#recursão)
- [@140 @140 L3 - Contando caracteres recursivamente](base/140)  [](#recursão)
- [@146 @146 L3 - Torres de Hanoi](base/146)  [](#recursão)

## 20. Structs

- [@148 @148 L1 - Expressão](base/148)  [](#structs)
- [@149 @149 L1 - Operações](base/149)  [](#structs)
- [@184 @184 L3 - Motivando a turma de secundaristas](base/184) 
- [@187 @187 L2 - Jogo da cobrinha](base/187)  [](#structs)
- [@182 @182 L3 - Mulher mais idosa](base/182)  [](#structs)

- [@042 @042 L3 - OBI 2021 - Chefe Nervoso](base/042) 