##Fundamentação Teórica
- Agricultura de Precisão
- VANTs
- Binarização de Imagens
- Transformada de Distância
- Operações morfológicas
- Espaço de cores

+++
### Agricultura de Precisão
- Divisão granulada do talhão (grid) |
- Georreferenciamento |
- Aplicação a taxa variável |
- NDVI |
- VANTs |

Note:
- Análise de solo no grid
- Máquinas com monitores
- Mapa de aplicação e produtividade

+++
### VANTs
![SX2](assets/sx2.jpg)

Note:
- Comparar com satélites

+++
### VANTs
- Sensores
- Atuadores
- Controladora
- Telemetria

Note:
- GPS, bússola, acelerômetro, sensor óptico infra ou RGB
- Servomotores, motor da hélice
- Plano de voo
- Ortomosaicagem

+++
### Binarização de Imagens
<img alt="Cavalo" src="assets/cavalo_bw.png" width="50%"/>

+++
### Binarização de Imagens
- Preto: $$v = 0$$
- Branco: $$v = 1$$ |
- Escala de cinza: $$ 0 < v < 1$$ |

+++
### Transformada de Distância
<img alt="Cavalo DT" src="assets/cavalo_dt.png" width="50%"/>

Note:
- Preto vira Preto
- Branco vira escala de cinza
- Proporcional distância da borda

+++
### Operações Morfológicas
#### Erosão
<img alt="Erosão" src="assets/erosao.png" width="50%"/>

Note:
- Elemento estruturante
- Pixel âncora
- resultado
- uso para retirar ruídos

+++
### Operações Morfológicas
#### Dilatação
<img alt="Dilatação" src="assets/dilatacao.png" width="50%"/>

Note:
- Ressaltar similaridade na operação
- uso para crescer/unir regiões
- Levantar mudança de dimensão

+++
### Operações Morfológicas
#### Abertura & Fechamento
<img alt="Abertura" src="assets/abertura.png" width="30%"/>
<img alt="Fechamento" src="assets/fechamento.png" width="30%"/>

Note:
- Abertura: suavizar protuberâncias
- Fechamento: suavizar entradas
- Não muda a dimensão, ao contrário dos outros
- Combinações de operações

+++
### Espaço de Cores
####RGB

<img alt="Cubo RGB" src="assets/rgb.png" width="60%"/>

Note:
- Ressaltar que vem do sensor óptico
- Bayer
- Lembrar que não pega todas as cores, mencionar CIE1931

+++
### Espaço de Cores
####HSV
<img alt="Cilindro HSV" src="assets/hsv.png" width="60%"/>

Note:
- Mencionar fórmulas de transformação
- Cada coordenada HSV
- Reforçar cor pelo H
