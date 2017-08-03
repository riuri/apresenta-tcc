##Localização de Plantas
1. Segmentação
2. Encontrar pontos
    2. Centroides
    3. Área-ponto

+++
###Segmentação
Transformação em HSV

<img alt="Cilindro HSV" src="assets/hsv.png" width="60%"/>

Note:
- H é a cor, V é pelas ervas

+++
###Binarização
Threshold por Otsu

<img alt="Segmentada" src="assets/pre.png" width="30%"/>

Note:
OTSU

+++
### Segmentação
#### Erosão
<img alt="Erosão" src="assets/erosao.png" width="50%"/>

+++
###Segmentação
<img alt="Segmentada" src="assets/pre.png" width="30%"/>
<img alt="Erodida" src="assets/ero.png" width="30%"/>

+++
### Segmentação
#### Dilatação
<img alt="Dilatação" src="assets/dilatacao.png" width="50%"/>

+++
###Segmentação
<img alt="Segmentada" src="assets/pre.png" width="30%"/>
<img alt="Erodida" src="assets/ero.png" width="30%"/>
<img alt="Dilatada" src="assets/dil.png" width="30%"/>

+++
###Encontrar pontos por Centroide
<img alt="Por centroide" src="assets/centroid.png" width="60%" />

Note:
- Crescimento de região
- Sem sobreposição foliar

+++
###Encontrar pontos por Área-ponto
<img alt="Fluxograma Área-ponto" src="assets/sobrepoe.png" width="80%"/>

+++
###Encontrar pontos por Área-ponto
<img alt="Fluxograma Área-ponto" src="assets/flow_areaponto.png" width="30%" style="border:none"/>

Note:
- inserir maiores círculos possíveis
- encher de círculos até se tornar irrelevante

+++
###Encontrar pontos por Área-ponto
Transformada de Distância

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
