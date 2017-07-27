# Identificação de linhas de plantio em imagens aéreas de lavouras
Iuri Rezende Souza

Orientador: Prof. Dr. Mauricio Cunha Escarpinati

---

##Fundamentação Teórica

- Agricultura de Precisão
- VANTs
- Binarização de Imagens
- Transformada de Distância
- Operações morfológicas
- Espaço de cores

+++

### Agricultura de Precisão

- Divisão granulada do talhão
- Georreferenciamento
- Aplicação a taxa variável
- NDVI
- VANTs

+++

### VANTs

![SX2](assets/sx2.jpg)

+++

### VANTs

- Sensores
- Atuadores
- Controladora

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

+++

### Operações Morfológicas
#### Erosão

<img alt="Erosão" src="assets/erosao.png" width="50%"/>

+++

### Operações Morfológicas
#### Dilatação

<img alt="Dilatação" src="assets/dilatacao.png" width="50%"/>

+++

### Operações Morfológicas
#### Abertura & Fechamento

<img alt="Abertura" src="assets/abertura.png" width="30%"/>
<img alt="Fechamento" src="assets/fechamento.png" width="30%"/>

+++

### Espaço de Cores

RGB

<img alt="Cubo RGB" src="assets/rgb.png" width="50%"/>

+++

### Espaço de Cores

HSV

<img alt="Cilindro HSV" src="assets/hsv.png" width="50%"/>

---

##Trabalhos Correlatos

---

## 3 Etapas do Algoritmo:

1. Localização de Plantas
2. Busca de Linhas Gerais
3. Melhorar Linhas Encontradas

---

##Localização de Plantas

---

##Busca de Linhas Gerais

+++

<canvas data-chart="radar">
Direção, 0, 1, 2, 3, 4, 5, 6, 7, 8
Contagem, 1, 1, 1, 1, 1, 18, 1, 1, 0
</canvas>

---

##Melhorar Linhas Encontradas

---

##Resultados e Discussões

---

##Conclusão e Trabalhos Futuros
