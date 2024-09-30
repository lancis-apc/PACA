# Puertos y transporte marítimo

<!-- Ruta de la documentación:
PACA\diagno\aptitud\web\PACA\docs\source -->

[Presentación](https://www.dropbox.com/scl/fi/wsqpqchrqn3ahn2663hdz/pp_talleres_oempcs_trans_mar.pdf?rlkey=duzogbnqcd0j0fc74vww0ysmg&st=pp70rbbn&dl=0)

## Meta

Desarrollo del comercio nacional e internacional mediante el transporte de mercancías en tráfico de altura (internacional), de cabotaje (entre puertos de México) y de corta distancia (regional) y brindando servicios de los sectores industriales para detonar la economía del país, así como el transporte de pasajeros, conforme a la vocación de los puertos del Sistema Portuario Nacional y considerando los planes de expansión de puertos y rutas de transporte.

Incrementar la competitividad, a través de la mejora de la movilidad, la eficiencia energética, el desarrollo de infraestructura sostenible y el manejo de residuos, minimizar la contaminación, avanzar en la descarbonización de los puertos e implementar estrategias de mitigación y adaptación.


[Lista de participantes](https://www.dropbox.com/scl/fi/5txz7dcl2k3ja3pyrcx2r/lista_asistencia.docx?rlkey=5tyf4tc9r1mvwyaz3gosg2stf&st=3xz481r9&dl=0)

<!-- **Si bien durante los talleres se evaluó la aptitud de cinco tipos de fuentes que incluyen hidrocarburos líquidos, gas natural, solar, eólica y biomasa, con base en los Art. 37 y 38 del Reglamento de la Ley General del Equilibrio Ecológico y la Protección al Ambiente en Materia de Ordenamiento Ecológico el mapa de aptitud que se utilizará como insumo para la actualización del POETY es el de energías renovables que se muestra en la sección 2.**

## 1. Energía

Fuentes de energía a escala.

### 1.1 Modelo de decisión

![](/recursos/energia/energia_industrial_v3.png)

### 1.2 Fuentes

#### 1.2.1 Hidrocarburos líquidos

Consumo y almacenamiento de hidrocarburos líquidos. Plantas que utilizan diesel o combustóleo para generar energía. Terminales de almacenamiento y reparto.

Atributos | Definición
-- | --
Carreteras | Distancia a carreteras.
Localidades | Distancia a asentamientos humanos.

##### 1.2.1.1 Carreteras

Distancia a carreteras.

**Insumos**

Capa | Distancia a carreteras
-- | --
Fuente | Red Nacional de Caminos (RNC) Red vial - INEGI
Año | 2019
Escala | Sin dato
Unidades | Kilómetros

**Parámetros de la función de valor**

![]()  

**Función de valor de carreteras**

![]()



#### 1.2.3 Solar

Instalaciones industriales que aprovechan la irradiación solar como fuente de energía.

Atributos | Definición
-- | --
Distancia a red eléctrica | Distancia a líneas de transmisión y subestaciones.
Cobertura | Tipo de vegetación.
Tenencia de la tierra | Áreas ejidales (comunitaria o parcelada) y no ejidales.



##### 1.2.3.2 Cobertura

Tipo de vegetación.

**Insumos**

Campo | Uso del suelo y vegetación
-- | --
Fuente | [1] Conjunto de datos vectoriales de la carta de Uso del suelo y vegetación. Serie VI. Conjunto Nacional INEGI y [2] Mapa de uso del suelo y vegetación de la zona costera asociada a los manglares, Región Península de Yucatán CONABIO
Año | [1] 2017; [2] 2021
Campo | [1] descripcio; [2] Descrip
Escala | [1] 1:250,000; [2] 1:50,000
Unidades | Adimensional

**Parámetros de la función de valor**

ID | Categoría | Importancia | FV
-- | -- | -- | --
2 | Agricultura de riego | Máxima | 1.00
3 | Agricultura de temporal | Máxima | 1.00
5 | Bosque cultivado/Palmar inducido | Máxima | 1.00
8 | Pastizal | Máxima | 1.00
11 | Sin vegetación | Máxima | 1.00
4 | Asentamiento humano | Moderada | 0.70
9 | Selva baja | Baja | 0.56
10 | Selva mediana | Baja | 0.56
12 | Sabana | Muy baja | 0.33
1 | Acuícola | Nula | 0.00
6 | Cuerpo de agua | Nula | 0.00
7 | Manglar | Nula | 0.00
13 | Tular | Nula | 0.00
14 | Vegetación de duna costera | Nula | 0.00
15 | Vegetación de petén | Nula | 0.00
16 | Vegetación halófila hidrófila | Nula | 0.00
17 | ND | Nula | 0.00

**Función de valor de cobertura**

![]()





### 1.3 Mapa de aptitud

#### 1.3.1 Mapa de aptitud de fuente hidrocarburos líquidos

##### 1.3.1.1 Zonas de aprovechamiento actual de hidrocarburos líquidos

**Insumos**

Capa | Poliducto Progreso - Mérida y centrales eléctricas de combustóleo
-- | --
Fuente | [1] Infraestructura Nacional de Almacenamiento y Transporte por Ducto de Petrolíferos y [2] Mapas de Infraestructura Energética y Recursos Renovables SENER
Año | [1] ?; [2] 2016
Escala | [1] ?; [2] Sin dato
Unidades | Adimensional

![]()

##### 1.3.1.2 Zonas de exclusión actual de hidrocarburos líquidos

**Insumos**

Campo | Uso del suelo y vegetación
-- | --
Fuente | [1] Conjunto de datos vectoriales de la carta de Uso del suelo y vegetación. Serie VI. Conjunto Nacional INEGI y [2] Mapa de uso del suelo y vegetación de la zona costera asociada a los manglares, Región Península de Yucatán CONABIO
Año | [1] 2017; [2] 2021
Campo | [1] descripcio; [2] Descrip
Escala | [1] 1:250,000; [2] 1:50,000
Unidades | Adimensional

**Tabla de exclusión del sector energía de fuente hidrocarburos líquidos**

ID | Cobertura
-- | --
1 | Acuícola
4 | Asentamiento humano
6 | Cuerpo de agua
7 | Manglar
13 | Tular
14 | Vegetación de duna costera
16 | Vegetación halófila hidrófila
17 | ND

![]()

##### 1.3.1.3 Mapa de aptitud de energía de fuente hidrocarburos líquidos

![]()

#### 1.3.2 Mapa de aptitud de fuente gas natural

##### 1.3.2.1 Zonas de aprovechamiento actual de gas natural

**Insumos**

Capa | [1] Centrales eléctricas de gas; [2] Gasoducto
-- | --
Fuente | [1] Mapas de Infraestructura Energética y Recursos Renovables SENER; [2] Gasoductos GeoComunes con datos de CRE, SEMARNAT, ASEA y CFE
Año | [1] 2016; [2] 2020
Escala | Sin dato
Unidades | Adimensional

![]()

##### 1.3.2.2 Zonas de exclusión actual de gas natural

**Insumos**

Campo | Uso del suelo y vegetación
-- | --
Fuente | [1] Conjunto de datos vectoriales de la carta de Uso del suelo y vegetación. Serie VI. Conjunto Nacional INEGI y [2] Mapa de uso del suelo y vegetación de la zona costera asociada a los manglares, Región Península de Yucatán CONABIO
Año | [1] 2017; [2] 2021
Campo | [1] descripcio; [2] Descrip
Escala | [1] 1:250,000; [2] 1:50,000
Unidades | Adimensional

**Tabla de exclusión del sector energía de fuente gas natural**

ID | Cobertura
-- | --
1 | Acuícola
4 | Asentamiento humano
6 | Cuerpo de agua
7 | Manglar
13 | Tular
14 | Vegetación de duna costera
16 | Vegetación halófila hidrófila
17 | ND

![]()

##### 1.3.2.3 Mapa de aptitud de energía de fuente gas natural

![]()



#### 1.3.8 Mapa de aptitud de energía

![]()

**Pesos globales de los atributos del sector energía**

Fuente de energía | Criterio | Peso
-- | -- | --
Gas natural | Distancia del gasoducto a las&nbsp;   zonas industriales | 0.274
Hidrocarburos líquidos | Carreteras | 0.256
Hidrocarburos líquidos | Localidades | 0.138
Solar | Distancia a red eléctrica | 0.091
Gas natural | Distancia del gasoducto a localidades | 0.065
Eólica | Velocidad | 0.057
Biomasa | Residuos urbanos | 0.026
Eólica | Distancia a la red eléctrica | 0.020
Solar | Cobertura | 0.018
Solar | Tenencia de la tierra | 0.018
Eólica | Cobertura | 0.012
Biomasa | Distancia a granjas porcícolas | 0.010
Eólica | Distancia a localidades | 0.004
Eólica | Distancia a caminos | 0.004
Biomasa | Residuos vegetales | 0.002

**Área por categoría de aptitud**

Categoría | km² | Porcentaje del estado
-- | --: | --:
Muy alta | 617.2 | 2
Alta | 2079.3 | 5
Moderada | 9181.9 | 23
Baja | 17188.5 | 43
Muy baja | 7800.3 | 20
Nula | 2669.4 | 7


## 2. Mapa de aptitud de energías renovables

### 2.1 Modelo de decisión del mapa de aptitud de energías renovables

![]()

#### 2.1.1 Mapa de aptitud de energías renovables

![]()

**Pesos globales del mapa de aptitud de energías renovables**

Fuente de energía | Criterio | Peso
-- | -- | --
Solar | Distancia a red eléctrica | 0.399
Eólica | Velocidad  | 0.204
Solar | Cobertura | 0.080
Solar | Tenencia de la tierra | 0.080
Eólica | Distancia a la red eléctrica | 0.074
Biomasa | Residuos urbanos | 0.060
Eólica | Cobertura | 0.046
Biomasa | Distancia a granjas porcícolas | 0.024
Eólica | Distancia a carreteras | 0.014
Eólica | Distancia a localidades | 0.014
Biomasa | Residuos vegetales | 0.005

**Área por categoría de aptitud**

Categoría | km² | Porcentaje del estado
-- | --: | --:
Muy alta | 1786.4 | 5
Alta | 10186.2 | 26
Moderada | 13293.6 | 34
Baja | 9922.8 | 25
Muy baja | 2476.1 | 6
Nula | 1871.4 | 5



<!-- .. csv-table::
   :file: recursos/tabla_c_biofisicos_silvopastoril.csv
   :header-rows: 1
   :align: center -->


