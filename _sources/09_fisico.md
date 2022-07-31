# Métodos con base física
Los modelos con base física evalúan la ocurrencia de movimientos en masa en términos de factor de seguridad o probabilidades de 
ocurrencia, a través de modelos numéricos que acoplan análisis geotécnicos de estabilidad de laderas con modelos 
de infiltración. Sin embargo existen diferentes aproximaciones a la física del problema con simplificaciones diferentes, por lo cual es fundamental utilizar el modelo que se ajuste a las necesidades o particularidades del área de estudio. 

El componente hidrológico de estos modelos explica el proceso de infiltración el agua en el suelo y el avance del frente húmedo o aumento de un nivel fgreático colgado. Para esto utilizan modelso de flujo estático horizontal o modelos de flujo transitorio vertical. Desde el componente geotécnico, la mayoría de modelos utilizan métodos de equilibrio límite de talud infinito. Alguno han incoporado modelos de dovelas que permiten análisis de superficies de falla circulares.

Los modelos con base física permiten tener en consideración la complejidad de los factores detonantes (sismo y/o lluvia) y las características geomecánicas del terreno. Sin embargo, los análisis determinísticos basados en el factor de seguridad no consideran la variabilidad espacio-temporal de los factores que intervienen en el análisis de estabilidad, introduciendo en los resultados incertidumbres y variaciones como producto de un análisis singular. 

Estos métodos son recomendables para áreas pequeñas a escalas detalladas, ya que requieren una gran cantidad de información de entrada, que se obtiene de ensayos de laboratorio o mediciones de campo. Por lo que la parametrización de los modelos puede ser complicada, en especial la distribución espacial de la profundidad del suelo, la cual juega un papel fundamental.

Como parte de los modelos físicos una gran variedad de modelos hidrológicos se han utilizado considerando el flujo de agua en el suelo en estado estático o transitorio, y en condiciones saturadas o parcialmente saturadas, utilizando las ecuaciones de Richards para el flujo vertical y las ecuaciones de Darcy para el flujo lateral. Entre estos se encuentra TOPOG (O’Loughlin, 1986), TAPES (Moore et al., 1988), TOPMODEL (Beven & Kirkby, 1979), GEOtop (Bertoldi & Rigon, 2004), tRIBS (Ivanov et al., 2004), SHIA (Vélez 2001), y los modelos de Green-Ampt (1911), Pradel & Raad (1993) e Iverson (2000). Por el contrario, los modelos geotécnicos utilizados son muy similares, generalmente utilizando el método talud infinito y análisis de equilibrio límite, suponiendo la superficie de falla paralela a la superficie del terreno y que la longitud de falla es mucho mayor que el espesor de la capa desplazada (Borga et al., 2002).

:::{figure-md} hidrologico
<img src="https://i.pinimg.com/564x/52/32/4a/52324a660eca43147a3ad80d2da9f621.jpg" alt="modelo hidrologico" width="600px">

Dos posibles mecanismos de saturación para deslizamientos detonados por lluvias. Izquierda: incremento del nivel freático colgado paralelo a la ladera a partir de una superficie de contraste de permeabilidad. Derecha: avance de frente húmedo a partir de la superficie del terreno.
:::

Uno de los primeros modelos físicos fue propuesto por Wu y Sidle (1995) denominado dSLAM (distribuited Shallow LAndslide Model), y posteriormente modificado como IDSSM (Integrated Dynamic Slope Stability Model) por Dhakal & Sidle (2003). Corresponde a un modelo físico, dinámico y distribuido, que utiliza un análisis de estabilidad de talud infinita con un modelo hidrológico de onda cinemática propuesto por Takasao y Shiiba (1988). Este modelo considera la vegetación y asume que la infiltración es siempre mayor a la intensidad de la lluvia.
Sin embargo uno de los modelos físicos más reconocido por su sencillez y fácil aplicación es el modelo propuesto por Montgomery & Dietrich (1994) y Montgomery et al. (1998), denominado SHALSTAB. Este modelo emplea el modelo hidrológico TOPOG para estimar la altura de la porción saturada de suelo, el cual asume que el control dominante de la distribución espacial de los movimientos está dado por la topografía. Estos autores definen para su análisis un índice topográfico, el cual es utilizado para predecir el nivel freático en función del flujo del agua en el suelo y la intensidad de la lluvia. El modelo de estabilidad propuesto utiliza el criterio de Mohr-Coulomb, en el cual por simplificación asumen la cohesión igual cero. 

Otros modelos conceptualmente similares al SHALSTAB se han desarrollado. El modelo SINMAP, desarrollado por Pack et al. (1998), evalúa las condiciones de estabilidad para movimientos en masa, utilizando la misma ecuación del factor de seguridad y las ecuaciones de Darcy para flujos saturados, pero a diferencia del SHALSTAB considera la cohesión del suelo. Y el modelo LISA (por sus siglas en inglés Level I Stability Analysis), desarrollado por Hammond et al. (1992), realiza un análisis probabilístico basado en el factor de seguridad, considerando la vegetación. Los valores para cada parámetro en la ecuación son definidos por una función de distribución de probabilidades y los resultados son presentados en un histograma que muestra la distribución del factor de seguridad calculado usando el método de Monte Carlo.

El modelo GEOtop –FS, desarrollado por Simoni et al. (2008), combina un análisis de estabilidad de talud infinito con el modelo hidrológico distribuido espacialmente y de diferencias finitas, GEOtop. El modelo estima el contenido de agua en el suelo y la evolución de la presión de poros resultante simulando los procesos de infiltración, escorrentía superficial, flujo subsuperficial saturado y no saturado, y flujos en canales. Para lo cual todas las celdas de la cuenca son divididas en celdas tipo canal y tipo laderas. El factor de seguridad se calcula con un enfoque probabilístico, donde los parámetros del suelo se asignan con funciones de distribución.
El modelo CHASM (Combined Hydrological And Stability Model), desarrollado por Wilkinson et al. (2000), utiliza el método simplificado circular de Bishop (1955) con un modelo hidrológico bidimensional de diferencias finitas para simular el cambio en las presiones de poros como respuesta a eventos de lluvia individuales. En cada intervalo de tiempo de simulación, las presiones de poro, tanto negativas como positivas, se incorporan directamente en la determinación de los esfuerzos efectivos y la resistencia al corte del suelo. Este análisis implica una búsqueda numérica de la superficie de deslizamiento que reduce al mínimo el factor de seguridad.

El modelo TRIGRS, desarrollado por Baum et al. (2002), utiliza el modelo hidrológico transitorio unidimensional para infiltración vertical propuesto por Iverson (2000), con un modelo de estabilidad de talud infinita asumiendo condiciones saturadas. El modelo evalúa el factor de seguridad como respuesta de las presiones de poros durante un evento de lluvia función de la profundidad y el tiempo, para lo cual divide el factor de seguridad en un componente estático (Fs0) asociados al estado estático o de largo plazo, y un componente que varía con el tiempo (FS)’ asociado al estado transitorio del evento de lluvia simulado.

Arnone et al. (2011) proponen un modelo físico distribuido, en el cual acoplan un modelo de talud infinita con el modelo hidrológico tRIBS (Triangulated Irregular Network Real-Time Integrated Basin Simulator) desarrollado por Ivanov et al. (2004). El modelo simula la intercepción de la lluvia, la evapotranspiración, la infiltración del agua en el suelo, la escorrentía superficial, y el flujo subsuperficial lateral a la ladera en condiciones saturadas y parcialmente saturadas, representando la heterogeneidad espacial de la topografía por una red irregular triangular (TIN) utilizada ampliamente por Sistemas de Información Geográfica (SIG) que reduce el tiempo computacional sin pérdidas aparentes de información. El modelo es también capaz de simular el volumen del material fallado y su posible trayecto.

Finalmente el modelo SHIA_Landslide propuesto por Aristizábal et al. (2014) acopla un modelo de talud infinita en condiciones saturadas con el modelo hidrológico distribuido de tanques a escala de cuenca que considera los flujos verticales y horizontales, denominado SHIA (Vélez, 2001). El modelo hidrológico está conformado por dos componentes: un balance de agua que simula los proceso hidrológicos dominantes en la cuenca, tales como infiltración, percolación, escorrentía superficial, flujo sub superficial, y flujo subterráneo; y un componente que simula el flujo del agua a través de la red de drenaje, lo que permite calibrar con valores observados la hidrología de la cuenca y las laderas previo a la simulación de estabilidad de las vertientes. 

:::{figure-md} modelos
<img src="https://i.pinimg.com/564x/21/f9/1d/21f91d0d89d2aac8176b08e2b832c18b.jpg" alt="modelos" width="800px">

Dos posibles mecanismos de saturación para deslizamientos detonados por lluvias. Izquierda: incremento del nivel freático colgado paralelo a la ladera a partir de una superficie de contraste de permeabilidad. Derecha: avance de frente húmedo a partir de la superficie del terreno.
:::

Los modelos más conocidos e implementados anivel mundial son el modelo SHallow Landslide Stability (SHALSTAB) y Transient Rainfall Infiltration and Gridbased Slope-Stability (TRIGRS), a continuación se describe cada uno de ellos.

## Modelo SHALSTAB
El modelo SHALSTAB, desarrollado por Montgomery & Dietrich, (1994), emplea el modelo hidrológico TOPOG (O'Loughlin, 1986) en condiciones de lluvia estacionaria para construir un mapa del patrón de la humedad basado en el área aferente a cada punto, la pendiente y la transmisividad del suelo. En el modelo la humedad del suelo es calculada como:

$W=\frac{Qa}{bTsinθ}$

Donde $Q$ es la lluvia en condiciones estacionarias ($mm/d$), a es el área de drenaje ($m^2$), $b$ es la longitud de cada celda ($m$), $T$ es la transmisividad del suelo en condiciones saturadas ($m^2/$), $\theta$ y  es la pendiente. Asumiendo que la transmisividad no varía con la profundidad, se puede entonces asumir:

$W= \frac{h}{z_t}$ 				

Donde $h$ es el espesor del suelo saturado y $z_t$ el espesor total de suelo. Combinando las dos ecuaciones anteriores se puede estimar la saturación relativa del perfil de suelo como:

$\frac{h}{z_t}=\frac{Qa}{bTsinθ} 	$

En cuanto al componente geotécnico, el modelo SHALSTAB está basado en análisis de equilibrio límite con talud infinito y el criterio de falla de Mohr-Coulomb.

$ρ_sgz_tsinθcosθ=C'+[ρ_s-ρ_w\frac{h}{z_t}]gzcos^2θtanϕ 	$

Donde $ρ_s$ es la densidad del suelo, $ρw$ es la densidad del agua, $g$ es la aceleración de la gravedad, $C’$ es la cohesión efectiva del suelo, y $φ$ es el ángulo de fricción. Esta ecuación puede ser escrita en términos de la relación h/z como:

$\frac{h}{z_t}=\frac{ρ_s}{ρ_w}(1-\frac{tanθ}{tanϕ})+\frac{C'}{wgz_tcos^2θtanϕ}$
Finalmente acoplando el modelo hidrológico con el modelo de estabilidad se obtienen la siguiente ecuación:

$\frac{a}{b}=\frac{T}{Q}sinθ[\frac{ρ_s}{ρ_w}(1-\frac{tanθ}{tanϕ})+\frac{C'}{wgzcos^2θtanϕ}]$

A partir de esta ecuación es posible determinar cuatro condiciones de estabilidad para cada celda de análisis. Las celdas donde la relación entre el área de drenaje aferente y la longitud de la celda (a/b) es mayor que la expresión al lado derecho de la ecuación corresponde a celdas inestables, en caso contrario son celdas estables. Las dos condiciones restantes corresponden a condiciones de estabilidad que no dependen de la lluvia. Las celdas estables en condiciones completamente saturadas de todo el perfil de suelo (h/zt=1) son denominadas incondicionalmente estables y cumplen la siguiente condición:

$tanθ<1-(\frac{ρ_s}{ρ_w})tanϕ+\frac{C'}{ρ_sgz_tcos^2θ $

Y las celdas inestables en condiciones secas (h/zt=0) se denominan incondicionalmente inestables y cumplen la siguiente condición:

$tanθ>=tanϕ+\frac{C'}{ρ_sgz_tcos^2θ$	


## Modelo TRIGRS
El modelo TRIGRS (Transient Rainfall Infiltration and Gridbased Slope-Stability) incorpora en su análisis el proceso de infiltración del agua lluvia y el cálculo del factor de seguridad. Este es un modelo con base física que evalúa la distribución temporal y espacial de movimientos en masa superficiales detonados por lluvia a través del cálculo de los cambios transitorios de la presión de poros y su incidencia en la variación del factor de seguridad, debido a la infiltración de la lluvia. 

El modelo de infiltración está basado en la solución lineal de las ecuaciones de Richards, y el flujo de 
agua en el suelo es el resultado de la sumatoria del estado estacionario y el componente transitorio asociado al evento de 
lluvia modelado. La solución para el caso de frontera basal impermeable a una profundidad finita está dada por:


Donde 𝜓 es la cabeza de presión, 𝑡 el tiempo. 𝑍 = 𝑧/𝑐𝑜𝑠 𝛿, 𝑍 es la coordenada en dirección vertical (positiva hacia abajo), 𝑧
la coordenada en dirección normal al talud y δ es el ángulo del terreno con la horizontal; 𝑑 es la profundidad inicial del nivel en 
dirección vertical. 𝐵 = 𝑐𝑜𝑠2𝛿 − (𝐼𝑍𝐿𝑇/𝐾𝑠), 𝐾𝑠 es la conductividad hidráulica saturada en dirección 𝑍, 𝐼𝑍𝐿𝑇 la tasa de infiltración estacionaria (inicial) en la superficie del suelo. 𝐼𝑛𝑍 es la tasa de infiltración a una intensidad dada para el n-ésimo intervalo de tiempo. 𝐷1 = 𝐷0/𝑐𝑜𝑠2𝛿, 𝐷0 es la difusividad hidráulica saturada (𝐷0 = 𝐾𝑠/𝑆𝑠, donde 𝑆𝑠 es el almacenamiento especifico). 𝑁 es el número total de intervalos y 𝐻(𝑡 − 𝑡𝑛) es la función de paso de Heaviside, donde 𝑡𝑛 es el tiempo en el n-ésimo intervalo en la secuencia de infiltración de lluvia. La función 𝑖𝑒𝑟𝑓𝑐 tiene la forma 𝑖𝑒𝑟𝑐𝑓 (𝜂) = 1√𝜋exp(−𝜂2) − 𝜂 𝑒𝑟𝑓𝑐 (𝜂), donde 𝑒𝑟𝑓𝑐(𝜂) es la función de error complementario.

Para estimar los cambios en el factor de seguridad como función de la profundidad (Z) y el tiempo (t) se utiliza el modelo de estabilidad de talud infinito de acuerdo con la siguiente ecuación: 

$FS(Z,t)=\frac{tan}{tanδ}+\frac{c'-ψ(Z,t)\gamma_wtanϕ'}{\gamma_sZsenδcosδ}$

Donde 𝑐′ es la cohesión efectiva del suelo, 𝜙′ el ángulo de fricción efectivo, 𝛾𝑤 el peso unitario del agua, 𝛾𝑠 el peso unitario 
del suelo y 𝜓(𝑍,𝑡) la cabeza de presión en función de la profundidad y el tiempo 𝑡. En se tiene información detallada del 
modelo TRIGRS.

## Modelo FOSM (First Order Second Moment)

Entre los modelos de confiabilidad más utilizados en la geotecnia se encuentran el método de Montecarlo, FOSM y estimativas puntuales. Para el presente trabajo se emplea el método estadístico FOSM, el cual emplea la expansión de la serie de Taylor de primer orden para derivar el 
primer y segundo momento de variables de entrada aleatorias. De esta forma, para estimar indirectamente la probabilidad de 
falla se calcula el Índice de Confiabilidad, dado por la relación entre la media y la desviación estándar de una función de 
probabilidad que se ajusta al factor de seguridad. 

Las ventajas del modelo FOSM consisten en que los cálculos son simplificados y solo requiere el conocimiento de los valores 
de los momentos de las distribuciones estadísticas de las variables que forman la función, expresados en la media y la varianza de cada variable, asumiendo una distribución normal tanto para las variables como para el factor de seguridad (FS). De esta manera, para N variables 
aleatorias no correlacionadas F (x1, x2,…, xN), conservando solamente los términos del primer orden (lineales) de la serie de 
Taylor, se producen las siguientes expresiones:

Donde 𝑥̅𝑖 y V(𝑥𝑖) son la media y varianza de cada variable aleatoria, respectivamente. Para los valores de las derivadas 
usualmente se utiliza la aproximación numérica dada en (5) propuesta por .

Finalmente, se obtiene el Índice de Confiabilidad del Factor de Seguridad, calculado por (6):

Donde 𝐸[𝐹𝑆] es el valor esperado del factor de seguridad calculado con los parámetros medios de las variables independientes y 𝜎[𝐹𝑆] es la desviación estándar del Factor de Seguridad (FS) obtenida por (3), teniendo como el FS crítico el valor 
igual a 1. Este índice expresa la confiabilidad del factor de seguridad en relación con la probabilidad de falla o ruptura.
El método FOSM permite evaluar la variabilidad de cualquiera de los parámetros incluidos dentro del análisis. En el 
presente estudio se evalúan los efectos de las variaciones de los parámetros de resistencia (cohesión y ángulo de fricción) y el 
espesor de suelo en el factor de seguridad.

