##Busca de Linhas Gerais

1. Selecionar direção do ponto mais próximo
2. Selecionar direção predominante
3. Conectar pontos vizinhos de linha
4. Descartar ligações em excesso

+++

###Direção do ponto mais próximo

<img alt="Pontos mais próximos" src="assets/arrows.png" width="60%"/>

+++

###Direção predominante
<img alt="Direções" src="assets/directions.png" width="40%"/>

+++
###Direção predominante
Exemplo

<img alt="Predominante" src="assets/predominant.png" width="60%"/>

+++
###Direção predominante
Exemplo

|Direção $\theta_i$|Contagem|Frequência|
|:---:|:---:|:---:|
|$$i=0, 1, 2, 3, 4$$|1|4%|
|$$5$$|18|72%|
|$$6, 7$$|1|4%|
|$$8$$|0|0%|

+++
###Direção predominante
Exemplo

<canvas data-chart="radar">
Direção, 0, 1, 2, 3, 4, 5, 6, 7, 8
Contagem, 1, 1, 1, 1, 1, 18, 1, 1, 0
</canvas>


+++

###Conectar pontos vizinhos de linha

<img alt="Retângulo de ligação" src="assets/rectangle.png" width="100%"/>

+++

###Descartar ligações em excesso

<img alt="Ideia do descarte" src="assets/descartar.png" width="60%"/>

+++
###Descartar ligações em excesso

- Ponto central $B$
- Pontos $P_i,\quad i \in \\{1, \dots, n\\}$
- Buscar par $(i, j)$ com $\angle{P_iBP_j}$ máximo |
- Desconectar $P_k,\quad k \in {1, \dots, n},\quad k \neq i, j$ |
