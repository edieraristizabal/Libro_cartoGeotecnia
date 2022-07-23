# Susceptibilidad y amenaza

## Definición de los conceptos de susceptibilidad y amenaza
La susceptibilidad de un terreno a fallar es definida por {cite:t}`brabb1984` como la tendencia de un deslizamiento a ser generado en el
futuro en una área específica. En el mismo sentido, {cite:t}`soeteres1996` definen susceptibilidad como la posibilidad de que un
fenómeno ocurra en un área de acuerdo con las condiciones locales del terreno, y especifican que factores detonantes tales
como precipitación o sismicidad no son considerados. Entre tanto, la amenaza se define como la probabilidad de ocurrencia de un fenómeno potencialmente dañino dentro de un periodo de tiempo específico y dentro de un área dada ({cite:t}`varnes1984`). Concretamente, el término amenaza expresa la probabilidad de ocurrencia de un potencial fenómeno destructivo en espacio y tiempo
definidos.

En este sentido, la susceptibilidad es el primer acercamiento hacia la evaluación de la amenaza, debido a que debe explicar la
distribución de los deslizamientos de acuerdo con la evolución geomorfológica del terreno (Griffiths y otros,
2002). El entendimiento de la ocurrencia de deslizamientos corresponde a un proceso comprensivo, donde cada paisaje es
caracterizado por una jerarquía de movimientos en masa distribuidos como una secuencia en tiempo y espacio, entendido como susceptibilidad, y
descrito por la frecuencia y magnitud incluyendo la duración y secuencia de los eventos del proceso, entendido como
amenaza (Brunsden, 2002).

Los términos amenaza y susceptibilidad han sido erróneamente usados como sinónimos. Los mapas de susceptibilidad zonifican el
terreno de acuerdo a la favorabilidad a fallar de una ladera, con el propósito de analizar posteriormente los mecanismos detonantes. En tanto, amenaza es la probabilidad de ocurrencia de deslizamientos en áreas susceptibles, y que a diferencia de susceptibilidad involucra frecuencia y magnitud. Esta definición de amenaza considera tiempo y espacio, dos factores que involucran la cuantificación de las causas
detonantes.

A la definición de amenaza Guzzetti et al., (1999) le adiciona la inclusión de la magnitud del evento. Por lo tanto, la definición de la amenaza por movimientos en masa incorpora los conceptos de localización, tiempo y magnitud. Como consecuencia, una completa evaluación de la amenaza debe predecir de forma cuantitativa dónde un movimiento en masa ocurrirá, cuándo o qué tan frecuente será su ocurrencia, y qué tan grande será el evento.

Considerando estos tres elementos, la probabilidad de amenaza por movimientos en masa en una área dada puede ser obtenida a partir de la probabilidad espacial (PS), que señala la probabilidad espacial relativa de ocurrencia de un movimiento en masa;  de la probabilidad temporal (PT), que señala la probabilidad de ocurrencia de un factor detonante que genera movimientos en masa; y de la probabilidad de magnitud (PM), que señala la probabilidad que un movimiento en masa pueda ser de un cierto tamaño (Guzzetti, 2004; Jaiswal et al., 2010; Wu y Chen, 2013). La amenaza (H) entonces puede ser calculada asumiendo independencia entre las tres probabilidades utilizando la siguiente ecuación:

$H = PM x PS x PT$

## Metodologías para la evaluación de la susceptibildiad y/o amenaza
Existen en la literatura múltiples métodos para evaluar la susceptibilidad o amenaza por movimientos en masa, los cuales pueden ser divididos en cuantitativos y cualitativos (Aleotti y Chowdhury, 1999; Carrara et al., 1995; Guzzetti et al., 1999; Van Westen et al., 2006). Los métodos cualitativos utilizan técnicas de cartografía geomorfológica y álgebra de mapas, mediante la asignación de pesos relativos de las variables que influyen en la ocurrencia de movimientos en masa. Es decir, se basan en el conocimiento o criterio de algún experto en el tema y, por lo tanto, son altamente subjetivos (Barredo et al., 2000; Castellanos Abella y Van Westen, 2001 van Westen et al., 2003;). Los métodos cuantitativos pueden ser clasificados en métodos basados en datos o estadísticos, y métodos con base física, o también conocidos como métodos determinísticos o probabilísticos (Palacio et al., 2020). Los métodos con base física, en general, utilizan modelos geotécnicos acoplados con modelos hidrológicos, dando como resultado un factor de seguridad o probabilidades de ocurrencia. Su principal desventaja es que necesitan información geotécnica detallada, por lo que no son recomendables para grandes escalas (Borga et al., 1998; Pourghasemi y Rahmati, 2018; Sorbino et al., 2010; Zieher et al., 2017). Los métodos basados en datos tratan de explicar la relación entre factores de inestabilidad conocidos y la distribución pasada y presente de movimientos en masa, estableciendo relaciones entre variables explicativas (pendiente, geología, aspecto, etc.) y una variable dependiente (ocurrencia de movimientos en masa). Sin embargo, los métodos estadísticos más utilizados en los últimos años hacen asunciones estadísticas sobre la distribución de los datos, lo que los convierte en modelos paramétricos que consideran estrictamente funciones lineales. Como parte de los métodos estadísticos, en los últimos años se han 
desarrollado aceleradamente técnicas de Inteligencia Artificial (IA), entre las cuales destaca el Aprendizaje Automático (ML por sus siglas 
en inglés, Machine Learning) que se caracteriza por ser una amplia colección de algoritmos utilizados para crear modelos que aprendan 
de los datos históricos, con el objetivo de hacer predicciones o conocer las relaciones que pueden existir entre variables de entrada y salida (ocurrencia de un evento); estos modelos tienen varias ventajas, tales como no hacer ninguna asunción estadística de los datos, considerar que no existe linealidad entre las variables y permitir el uso de un amplio tipo de variables (Alpaydin, 2010; Beam y Kohane, 2018; El Naqa y Murphy, 2015; Moreno, 1994).

```{bibliography}
:style: plain
:filter: docname in docnames
```