##Busca de Linhas Gerais

1. Selecionar direção do ponto mais próximo
2. Selecionar direção predominante
3. Conectar pontos vizinhos de linha
4. Descartar ligações em excesso

+++
###Direção do ponto mais próximo
<img alt="Pontos mais próximos" src="assets/arrows.png" width="60%"/>

+++
###Classificação das direções
<img alt="Direções" src="assets/directions.png" width="40%"/>

+++
###Classificação das direções
Exemplo

<img alt="Predominante" src="assets/predominant.png" width="50%"/>

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
###Conectar pontos vizinhos de linha
<img alt="Retângulo de ligação" src="assets/rectangle.png" width="100%"/>

+++
###Descartar ligações em excesso
<img alt="Ideia do descarte" src="assets/descartar.png" width="60%"/>

+++
###Descartar ligações em excesso
- Ponto central $B$
- Pontos $P_i,~ i \in \\{1, \dots, n\\}$
- Buscar par $(i, j)$ com $\angle{P_iBP_j}$ máximo |
- Desconectar $P_k,~ k \in \\{1, \dots, n\\},~ k \neq i, j$ |
