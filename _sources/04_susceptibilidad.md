# Susceptibilidad y amenaza

## Definición de los conceptos de susceptibilidad y amenaza
La susceptibilidad de un terreno a fallar es definida por {cite:t}`Brabb1984` como la tendencia de un deslizamiento a ser generado en el
futuro en una área específica. En el mismo sentido, {cite:t}`Soeteres1996` definen susceptibilidad como la posibilidad de que un
fenómeno ocurra en un área de acuerdo con las condiciones locales del terreno, y especifican que factores detonantes tales
como precipitación o sismicidad no son considerados. Entre tanto, la amenaza se define como la probabilidad de ocurrencia de un fenómeno potencialmente dañino dentro de un periodo de tiempo específico y dentro de un área dada ({cite:t}`Varnes1984`). Concretamente, el término amenaza expresa la probabilidad de ocurrencia de un potencial fenómeno destructivo en espacio y tiempo
definidos.

En este sentido, la susceptibilidad es el primer acercamiento hacia la evaluación de la amenaza, debido a que debe explicar la
distribución de los deslizamientos de acuerdo con la evolución geomorfológica del terreno ({cite:t}`Mather2002`
2002). El entendimiento de la ocurrencia de deslizamientos corresponde a un proceso comprensivo, donde cada paisaje es
caracterizado por una jerarquía de movimientos en masa distribuidos como una secuencia en tiempo y espacio, entendido como susceptibilidad, y
descrito por la frecuencia y magnitud incluyendo la duración y secuencia de los eventos del proceso, entendido como
amenaza ({cite:t}`Brunsden2002`).

Los términos amenaza y susceptibilidad han sido erróneamente usados como sinónimos. Los mapas de susceptibilidad zonifican el
terreno de acuerdo a la favorabilidad a fallar de una ladera, con el propósito de analizar posteriormente los mecanismos detonantes. En tanto, amenaza es la probabilidad de ocurrencia de deslizamientos en áreas susceptibles, y que a diferencia de susceptibilidad involucra frecuencia y magnitud. Esta definición de amenaza considera tiempo y espacio, dos factores que involucran la cuantificación de las causas
detonantes.

A la definición de amenaza {cite:t}`Guzzetti1999` le adiciona la inclusión de la magnitud del evento. Por lo tanto, la definición de la amenaza por movimientos en masa incorpora los conceptos de localización, tiempo y magnitud. Como consecuencia, una completa evaluación de la amenaza debe predecir de forma cuantitativa dónde un movimiento en masa ocurrirá, cuándo o qué tan frecuente será su ocurrencia, y qué tan grande será el evento.

Considerando estos tres elementos, la probabilidad de amenaza por movimientos en masa en una área dada puede ser obtenida a partir de la probabilidad espacial (PS), que señala la probabilidad espacial relativa de ocurrencia de un movimiento en masa;  de la probabilidad temporal (PT), que señala la probabilidad de ocurrencia de un factor detonante que genera movimientos en masa; y de la probabilidad de magnitud (PM), que señala la probabilidad que un movimiento en masa pueda ser de un cierto tamaño. La amenaza (H) entonces puede ser calculada asumiendo independencia entre las tres probabilidades utilizando la siguiente ecuación:

$H = PM x PS x PT$

## Metodologías para la evaluación y zonificación de la susceptibildiad y/o amenaza
Existen en la literatura múltiples métodos para evaluar la susceptibilidad o amenaza por movimientos en masa, los cuales pueden ser divididos en cuantitativos y cualitativos ({cite:t}`Fell2008`; {cite:t}`Aleotti1999a`; {cite:t}`Carrara1983`; {cite:t}`Guzzetti1999`; {cite:t}`Westen2006`). 

Los métodos cualitativos utilizan técnicas de cartografía geomorfológica y álgebra de mapas, mediante la asignación de pesos relativos de las variables que influyen en la ocurrencia de movimientos en masa. Es decir, se basan en el conocimiento o criterio de algún experto en el tema y, por lo tanto, son altamente subjetivos ({cite:t}`Barredol2000`; {cite:t}`Westen2003`). 

Los métodos cuantitativos pueden ser clasificados en métodos basados en datos o estadísticos, y métodos con base física, o también conocidos como métodos determinísticos o probabilísticos ({cite:t}`Palacio2020`). Los métodos con base física, en general, utilizan modelos geotécnicos acoplados con modelos hidrológicos, dando como resultado un factor de seguridad o probabilidades de ocurrencia. Su principal desventaja es que necesitan información geotécnica detallada, por lo que no son recomendables para grandes escalas ({cite:t}`Borga1998`; {cite:t}`Sorbino2010`). Los métodos basados en datos tratan de explicar la relación entre factores de inestabilidad conocidos y la distribución pasada y presente de movimientos en masa, estableciendo relaciones entre variables explicativas (pendiente, geología, aspecto, etc.) y una variable dependiente (ocurrencia de movimientos en masa). Sin embargo, los métodos estadísticos más utilizados en los últimos años hacen asunciones estadísticas sobre la distribución de los datos, lo que los convierte en modelos paramétricos que consideran funciones lineales. Como parte de los métodos estadísticos, en los últimos años se han desarrollado aceleradamente técnicas de Inteligencia Artificial (IA), entre las cuales destaca el Aprendizaje Automático (ML por sus siglas en inglés, Machine Learning) que se caracteriza por ser una amplia colección de algoritmos utilizados para crear modelos que aprendan de los datos históricos, con el objetivo de hacer predicciones o conocer las relaciones que pueden existir entre variables de entrada y salida (ocurrencia de un evento); estos modelos tienen varias ventajas, tales como no hacer ninguna asunción estadística de los datos, considerar que no existe linealidad entre las variables y permitir el uso de un amplio tipo de variables ({cite:t}`Ospina2021`).

:::{figure-md} metodos
<img src="https://ars.els-cdn.com/content/image/1-s2.0-S2212420919313494-gr4.jpg" alt="metodos" width="700px">

Métodos para la evaluación de la susceptibilidad y/o amenaza por movimientos en masa. Tomado de {cite:t}`Thiery2020`.
:::

Luego de la evaluación de la susceptibilidad y/o amenaza se debe subdividir el terreno en áreas homogeneas o dominios y su rango de acuerdo con el grado actual o potencial de susceptibilidad o amenaza., lo cual se le denomina zonificación. Existen diferentes escalas de zonificación con objetivos y alcances diferentes, lo cual implica tambien metodologías diferentes. Escalas pequeñas se refieren generalmente a <100:000 para áreas con extensiones de decenas de miles de $km^2$ a nivel de país y donde corresponden principalmente a inventarios de movimientos o evaluaciones de susceptibilidad. Escalas medias entre 100:000 y 10:000 para áreas de varios $km^2$  incluso miles, donde se realizan inventarios, zonificación de la susceptibilidad, o incluso zonificación de la amenaza, a nivel de cuenca o regiones, o en algunos casos proyectos de ingeniería de gran escala. finalmente, escalas de detalle por >10.000 para áreas de algunos $km^2$ o hectareas, donde se realizan desde inventarios hasta zonificación de la amenaza y riesgo.

Es tambien importante diferenciar entre cartografía geotécnica, que se refiere a la evaluación y zonificación de la amenaza en las laderas principalmente, y  estudios geotécnicos, que se refieren a estudios de sitio, donde no se zonifica sino que evalua la estabilidad de cortes de laderas o taludes con geometrias, parametrización y modelo geológico único y específico para dicho corte. En el caso de cartografía geotécnica, en general la geometria de las laderas es aproximada con modelos de elevacion digital que están representados por celdas, y el modelo geológico y la parametrización también corresponden a una generalización o simplificación. Los estudios geoténicos de sitio generalmente utilizan modelos mucho mas sofisticados, entre tanto los modelos de zonificación en cartografía geotécnica realizan una evaluación iterando celda a celda por lo que implementan modelos generalmente de talud infinito con superficies de falla plana, en los casos mas avanzados, disponibles en el estado del arte, utilizan técnicas de dovelas que implica superficies de fallas circulares o en algunos casos irregulares que analizan varias celdas.

## Unidad morfodinámica independiente
Entre las fases iniciales para un estudios de evalaución y zonificación de la susceptibilidad y/o amenaza por movimientos en masa se debe establecer el área de influencia del territorio a incorporar en el estudio. Un concepto importante que permite definir dicha área fue propuesto originalmente por el Prof. {cite:t}:`Chica1989`, y denominado Unidad Morfodinámica Independiente (UMI). Definidad como la unidad del territorio que enmarca la ladera de interés y que presenta un comportamiento independiente de las unidades adyacentes. Se considera que cualquier proceso morfodinámico que se presente en el exterior no afecta su interior e igualmente, cualquier proceso que se presente en el interior no afecta las unidades adyacentes. No existe un procedimiento estandar para la delimitación de la UMI, es un procedimiento heurístico, por lo tanto subjetivo, y que sus bordes coinciden generalmente por divisorias de aguas, drenjes o geoformas. Inicialmente el ejericicio para la definición de la UMI debe establecer el tipo de movimiento en masa a analizar, un criterio fundamental es la propagación del evento, la cual puede afectar áreas distanciadas cientos de kilómetros desde su origen, es diferente la UMI para eventos tipo flujos que para movimientos en masa tipo volcamiento.

## Unidad de mapeo o análisis
Adicional a definir el área de influencia, es necesario además esatblecer la unida de mapeo del terreno, la cual define la unidad mínima de análisis. Esta unidad representa el dominio que maximiza la homogeneidad interna y la hetereogeneidad entre las unidades. Se refiere a la porción del terreno que contiene un grupo de condiciones del terreno que difiere de las unidades adyacentes a lo largo de límites definidos ({cite:t}`Hansen1984`).

Existen diferentes unidades de mapeo, sin embargo las mas extendidas son unidad de condiciones únicas (UCU), unidad de ladera o celdas regulares. La unidad que menos se ajusta a la definición es precisamente la mas utilizada, celdas regulares, ya que favorece el manejo matemático y computacional durante la evaluación y zonificación. Las celdas regulares componen los mapas tipo *raster* por lo tanto desde el punto de vista computacional es mucho mas facil representar las variables como celdas regulares tipo raster. Y desde el punto de vista matemático, las variables representadas como celdas regulares corresponden a matrices, lo cual permite implementar algebra lineal, y por lo tanto técnicas estadísticas y de programación, que en otro caso serían demasiado complejas probablemente. Comos e mencionaba anteriormente, la desventaja de las celdas regulares se refiere a que precisamente no corresponden a bordes naturales o dominios que enmarquen condiciones especiales o únicas. Simplemente son celdas de tamaños establecidos que segmentan el terreno sin ningún criterio físico.

A diferencia la unidad de análisis tipo UCU o unidad de ladera si implica la segmentacion del terreno de acuerdo con criterios físicos. En el caso de la UCU corresponde a las combinaciones únicas resultado del álgebra de mapas de las variables a utilizar. En el caso de las unidades de ladera corresponden a la definición de ladera, es decir la unidad mínima del terreno con una superficie inclinada homogenea separada por cambios de pendiente. 

:::{figure-md} unidad de laderas
<img src="https://i.pinimg.com/originals/03/d9/d6/03d9d614d4d063a42283b3d3274beed1.jpg" alt="unidad de laderas" width="500px">

Unidad de análisis tipo (a) celdas regulares (b) unidad de ladera.
:::

:::{figure-md} UCU
<img src="https://i.pinimg.com/564x/27/e2/02/27e20275df23bde601ff21512f47ccc9.jpg" alt="UCU" width="500px">

Unidad de análisis tipo unidad de condiciones únicas.
:::

```{bibliography}
:style: plain
:filter: docname in docnames
```