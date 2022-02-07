# Métodos con base física

 los modelos 
con base física evalúan la ocurrencia de 
movimientos en masa en términos de 
factores de seguridad o probabilidades de 
ocurrencia [13], a través de modelos 
numéricos que acoplan análisis de 
estabilidad de equilibrio límite con modelos 
de infiltración [14]. Los modelos con base 
física permiten tener en consideración la 
complejidad de los factores detonantes 
(sismo y/o lluvia) y las características 
geomecánicas del terreno. Sin embargo, los 
análisis determinísticos basados en el 
factor de seguridad no consideran la 
variabilidad espacio-temporal de los
factores que intervienen en el análisis de 
estabilidad [15], introduciendo en los 
resultados incertidumbres y variaciones 
como producto de un análisis singular [16]. 

## Modelo TRIGRS (Transient Rainfall Infiltration and Gridbased Slope-Stability)

Para el análisis del proceso de infiltración del agua lluvia y el cálculo del factor 
de seguridad, se utiliza el modelo TRIGRS. 
Este es un modelo con base física que evalúa la distribución temporal y espacial de 
movimientos en masa superficiales detonados por lluvia a través del cálculo de los 
cambios transitorios de la presión de poros 
y su incidencia en la variación del factor de 
seguridad, debido a la infiltración de la 
lluvia [18]. El modelo de infiltración está 
basado en la solución lineal de las ecuaciones de Richards [19], [18], y el flujo de 
agua en el suelo es el resultado de la sumatoria del estado estacionario y el componente transitorio asociado al evento de 
lluvia modelado. La solución para el caso
de frontera basal impermeable a una profundidad finita está dada por (1).
Donde 𝜓 es la cabeza de presión, 𝑡 el 
tiempo. 𝑍 = 𝑧/𝑐𝑜𝑠 𝛿, 𝑍 es la coordenada en 
dirección vertical (positiva hacia abajo), 𝑧
la coordenada en dirección normal al talud 
y δ es el ángulo del terreno con la horizontal; 𝑑 es la profundidad inicial del nivel en 
dirección vertical. 𝐵 = 𝑐𝑜𝑠2𝛿 − (𝐼𝑍𝐿𝑇/𝐾𝑠), 𝐾𝑠
es la conductividad hidráulica saturada en 
dirección 𝑍, 𝐼𝑍𝐿𝑇 la tasa de infiltración estacionaria (inicial) en la superficie del suelo. 
𝐼𝑛𝑍 es la tasa de infiltración a una intensidad dada para el n-ésimo intervalo de 
tiempo. 𝐷1 = 𝐷0/𝑐𝑜𝑠2𝛿, 𝐷0 es la difusividad 
hidráulica saturada (𝐷0 = 𝐾𝑠/𝑆𝑠
, donde 𝑆𝑠
es el almacenamiento especifico). 𝑁 es el 
número total de intervalos y 𝐻(𝑡 − 𝑡𝑛
) es la 
función de paso de Heaviside, donde 𝑡𝑛 es 
el tiempo en el n-ésimo intervalo en la 
secuencia de infiltración de lluvia. La función 𝑖𝑒𝑟𝑓𝑐 tiene la forma 𝑖𝑒𝑟𝑐𝑓 (𝜂) =
1
√𝜋
exp(−𝜂
2
) − 𝜂 𝑒𝑟𝑓𝑐 (𝜂), donde 𝑒𝑟𝑓𝑐(𝜂) es 
la función de error complementario [20].
El modelo geotécnico empleado en 
TRIGRS es un modelo de talud infinito 
unidimensional. El factor de seguridad FS 
se determina a partir de (2) propuesta por 
[21].
Donde 𝑐
′ es la cohesión efectiva del suelo, 𝜙′ el ángulo de fricción efectivo, 𝛾𝑤 el 
peso unitario del agua, 𝛾𝑠 el peso unitario 
del suelo y 𝜓(𝑍,𝑡) la cabeza de presión en 
función de la profundidad y el tiempo 𝑡. En 
[18] se tiene información detallada del 
modelo TRIGRS.

## Modelo FOSM (First Order Second Moment)

Entre los modelos de confiabilidad más 
utilizados en la geotecnia se encuentran el 
método de Montecarlo, FOSM y estimativas puntuales [22]. Para el presente trabajo se emplea el método estadístico FOSM, 
el cual emplea la expansión de la serie de 
Taylor de primer orden para derivar el 
primer y segundo momento de variables de 
entrada aleatorias. De esta forma, para 
estimar indirectamente la probabilidad de 
falla se calcula el Índice de Confiabilidad 
(), dado por la relación entre la media y la 
desviación estándar de una función de 
probabilidad que se ajusta al factor de 
seguridad [23], [24]. 
Las ventajas del modelo FOSM consisten en que los cálculos son simplificados y 
solo requiere el conocimiento de los valores 
de los momentos de las distribuciones estadísticas de las variables que forman la 
función, expresados en la media y la varianza de cada variable, asumiendo una 
distribución normal tanto para las variables como para el factor de seguridad (FS) 
[25]. De esta manera, para N variables 
aleatorias no correlacionadas F (x1, x2,…, 
xN), conservando solamente los términos 
del primer orden (lineales) de la serie de 
Taylor, se producen las siguientes expresiones (3) y (4):

Donde 𝑥̅𝑖 y V(𝑥𝑖) son la media y varianza de cada variable aleatoria, respectivamente. Para los valores de las derivadas 
usualmente se utiliza la aproximación 
numérica dada en (5) propuesta por [26].

Finalmente, se obtiene el Índice de Confiabilidad del Factor de Seguridad, calculado por (6):

Donde 𝐸[𝐹𝑆] es el valor esperado del 
factor de seguridad calculado con los parámetros medios de las variables independientes y 𝜎[𝐹𝑆] es la desviación estándar 
del Factor de Seguridad (FS) obtenida por 
(3), teniendo como el FS crítico el valor 
igual a 1. Este índice expresa la confiabilidad del factor de seguridad en relación con 
la probabilidad de falla o ruptura.
El método FOSM permite evaluar la 
variabilidad de cualquiera de los parámetros incluidos dentro del análisis. En el 
presente estudio se evalúan los efectos de 
las variaciones de los parámetros de resistencia (cohesión y ángulo de fricción) y el 
espesor de suelo en el factor de seguridad.

