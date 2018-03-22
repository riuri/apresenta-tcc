## Busca de Linhas Gerais

1. Selecionar direção do ponto mais próximo
2. Selecionar direção predominante
3. Conectar pontos vizinhos de linha
4. Descartar ligações em excesso

+++
### Direção do ponto mais próximo
<img alt="Pontos mais próximos" src="assets/arrows.png" width="60%"/>

Note:
- Lembrar que pode mais de 2 ligados

+++
### Classificação das direções
<img alt="Direções" src="assets/directions.png" width="40%"/>

Note:
- Cada cor representa uma direção

+++
### Exemplo de classificação
<img alt="Predominante" src="assets/predominant.png" width="50%"/>

Note:
- Predominância da 5
- Presença de outras

+++
### Direção predominante
Exemplo

|Direção $\theta_i$|Contagem|Frequência|
|:---:|:---:|:---:|
|$$i=0, 1, 2, 3, 4$$|1|4%|
|$$5$$|18|72%|
|$$6, 7$$|1|4%|
|$$8$$|0|0%|

Note:
- A 5 foi escolhida
- Muito na 5, pouco nas outras

+++
### Conectar pontos vizinhos de linha
<img alt="Retângulo de ligação" src="assets/rectangle.png" width="100%"/>

Note:
- Busca em cada metade
- Ponto mto próximo em outra direção deve ser da linha
- Ponto mto longe pode estar curvado

+++
### Descartar ligações em excesso
<img alt="Ideia do descarte" src="assets/descartar.png" width="60%"/>

Note:
- Retornar ideia de ponto ligado pode ser mais de 1

+++
### Descartar ligações em excesso
- Ponto central $B$
- Pontos $P_i,~ i \in \\{1, \dots, n\\}$
- Buscar par $(i, j)$ com $\angle{P_iBP_j}$ máximo |
- Desconectar $P_k,~ k \in \\{1, \dots, n\\},~ k \neq i, j$ |
