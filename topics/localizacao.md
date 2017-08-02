##Localização de Plantas
1. Segmentação
2. Encontrar pontos
    2. Centroides
    3. Área-ponto

+++
###Segmentação
- Transformação em HSV |
    - Utilização dos canais H e V |
- Erosão, seguida de dilatação |
- Intersecção das regiões |

Note:
- H é a cor, V observado pelas ervas
- Erosão para filtar
- Dilatação para juntar regiões separadas
- Intersecção pq critérios excludentes

+++
###Encontrar pontos por Centroide
<img alt="Por centroide" src="assets/centroid.png" width="60%" />

Note:
- Crescimento de região
- Sem sobreposição foliar

+++
###Encontrar pontos por Área-ponto
<img alt="Fluxograma Área-ponto" src="assets/flow_areaponto.png" width="30%" style="border:none"/>

Note:
- inserir maiores círculos possíveis
- encher de círculos até se tornar irrelevante

+++
###Encontrar pontos por Área-ponto
<img alt="Transformada Área-ponto" src="assets/areaponto_dt.png" width="100%" />

Note:
- Ponto de máximo

+++
###Encontrar pontos por Área-ponto
<img alt="Área-ponto" src="assets/areaponto.png" width="100%"/>

Note:
- 6 pixels
- Círculos e pontos
- Representatividade
- Independência caso mais de uma região
