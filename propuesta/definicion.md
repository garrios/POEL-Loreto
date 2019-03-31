# Definición

## DEFINICION DE LA PROPUESTA

Como se ha comentado a lo largo de las diferentes etapas del Programa de ordenamiento ecológico
territorial del Municipio de Loreto, este instrumento de política ambiental tiene como principal objetivo
propiciar que se realicen las actividades productivas necesarias para el sustento de la población,
pero garantizando que con su realización se logre la protección al ambiente y por consecuencia
ocurra el aprovechamiento sustentable de los recursos naturales, favoreciendo las actividades en
función de la aptitud que se determine como la mejor para el uso del suelo. Debe ubicar a través del
análisis de aptitud las mejores áreas para el desarrollo de las actividades (turismo, campamentos
pesqueros, ganadería y conservación).

La elaboración de las unidades de gestión ambiental (UGA) depende del seguimiento de una serie de
procesos analíticos elaborados a partir de la selección de capas de información del terreno y
atributos ambientales específicos para cada sector, así como la combinación lineal ponderada de los
criterios de decisión y sus pesos de importancia. El formato se cambia de vectorial a formato raster
con el fin de realizar las operaciones correspondientes al análisis.

Requerimientos:
Información vectorial poligonal de los atributos ambientales seleccionados
Valor del peso normalizado asignado a los polígonos
Software especializado para el análisis de SIG (Arc Map 9.0) con extensión Spatial Analyst

## ANÁLISIS DE APTITUD

El resultado de los talleres sectoriales plasmado en atributos ambientales representa la selección de
capas de información vectorial disponibles, a las que se les otorga un mayor o menor peso que es el
que se pondera entre las capas que se utilizan en el análisis. Los atributos se agrupan en función de
características comunes. Cada grupo dentro de los atributos del sector tiene en conjunto un peso
normalizado que al sumarse a los demás grupos da un valor de 1 (Tablas 8, 9 y 10).

```
Tabla 8. Atributos ambientales y ponderación por grupos de criterios para el sector Conservación.
```

```
Tabla 9. Atributos ambientales y ponderación por grupos de criterios para el sector Turismo
```

```
Tabla 10. Atributos ambientales y ponderación por grupos de criterios para el sector Pesca
```

Las capas que pertenecen al mismo grupo y que por ende comparten el mismo peso en la organización
jerárquica, se unen de forma vectorial para formar un sólo polígono que represente al grupo
correspondiente. Cada uno de los grupos de información vectorial es transformado a formato raster
asignándole el peso normalizado específico para su análisis. Posteriormente, ya obtenidos los mapas de
cada grupo A, B, C), se suman (A+B+C+D) obteniendo con esto una clasificación de valores que van de 0 a
1, mostrando de esta manera los sitios de mayor aptitud para el sector.


Esta misma operación se repite para cada uno de los sectores identificados.

Una vez obtenidos los mapas de aptitud para cada uno de los sectores, se sobreponen y suman
originando un mapa de las zonas de mayor incidencia de valores máximos de aptitud. Esto determina
las áreas de conflicto entre los sectores (Figura 20).


```
Figura 20. Mapas de grupos para los sectores conservación, Turismo y pesca en el Municipio de Loreto, B.C.S.
```
## UNIDADES DE GESTIÓN AMBIENTAL (UGA)

Una UGA es la unidad mínima territorial donde se aplican tanto lineamientos como estrategias
ambientales, de política territorial, aunado con esquemas de manejo de recursos naturales, es decir
criterios o lineamientos finos del manejo de estos recursos, orientados a un desarrollo que transite a
la sustentabilidad y que facilita a los tomadores de decisión las planeación organizada de los usos
potenciales del territorio.


Una vez generado el mapa de conflictos de los sectores, se analizan los polígonos resultantes. Es
decir, el mapa de conflictos se conforma de la división virtual del territorio (en este caso del Municipio
de Loreto) en polígonos irregulares que representan partes del terreno que poseen valores de aptitud
que son más apropiados para alguno de los sectores. Estos polígonos son el resultado de la
clasificación numérica obtenida por medio del método de partición politético divisivo, una vez aplicado
el análisis de componentes principales a las capas digitales derivadas de los modelos multicriterio
(Figura 21).

Cada uno de los polígonos es extraído y validado para de esta manera poder utilizarlo como máscara
al analizar los mapas de aptitud por sector. Para la elaboración de las unidades de gestión ambiental,
es necesario designar áreas que sean reconocibles en el campo o de manera topográfica. Por ello el
resultado del análisis de conflictos es cruzado o sobrepuesto con las capas de información que se
pueden identificar físicamente (p.ej. la de Uso de suelo y vegetación, las Subcuencas hidrológicas,
topográfico, vías terrestres y centro de población, campamentos pesqueros, campos agrícolas,
pozos).

Las capas de información vectorial, se cruzan entre sí para crear polígonos que tengan una
expresión topográfica, creando con esto una máscara digital con la que extraerán los valores de
aptitud para cada sector.


El resultado ahora son polígonos irregulares con expresión topográfica. Una vez analizados estos
polígonos se procede a eliminar los errores del proceso, discriminando los polígonos menores a 1
hectárea, y uniéndolos al vecino más próximo. De esta manera se obtienen UGA mejor integradas y
de mayor tamaño.

Cada uno de los polígonos es transformado a formato raster para hacerlos compatibles con los
archivos raster de los análisis de aptitud, con lo cual se extraen los valores de los diferentes sectores.

Una vez rasterizados, se extraen los valores multiplicando el polígono raster de la UGA por cada uno
de los análisis de aptitud, extrayendo así el valor de aptitud por sector para cada una de las UGA.

La delimitación de las UGA se realizó a partir del mapa obtenido de la regionalización y apoyado con
la cartografía de las unidades de paisaje, unidades de vegetación, delimitación de las áreas
propuestas para la preservación y utilizando además las fuentes cartográficas del PSDRU. Se
utilizaron capas temáticas para hacer subdivisiones de las Unidades de Gestión Ambiental obtenidas
inicialmente, en particular para las que existían problemas de delimitación clara de las aptitudes y
actividades dentro de las UGA. Esta división y delimitación fue realizada con base a capas temáticas
como la topográfica y de vegetación principalmente, lo que permitió la ubicación y delimitación física
de cada una de las UGA de una manera más práctica y fácil de definir para los sectores. Un ejemplo
de esto es la separación que se realizó en algunas de las UGA que por su conformación contenían
tanto áreas pegadas como alejadas de la costa y cercanas en este caso a las sierras. Entonces, se
presentaban áreas de alta aptitud para la pesca en zonas altas de la sierra o alejadas de la costa.
Ello se debió a que los atributos señalados en los talleres sectoriales por los participantes no
discriminaron las áreas alejadas de la costa simplemente refiriéndose a la cercanía a fuentes de agua
dulce (pozos). La forma de corregirlo fue haciendo un corte de las UGAs que tenían en una de sus
partes bajas cercanía a costa y potencialidad para el sector comunidades pesqueras. Se estableció
entonces el límite de la cota de los 100msnm como medida estandarizada de su área de actividad
potencial, desde la costa. Como resultado de este proceso se pudo obtener un alto porcentaje de
UGA sin conflictos ambientales por actividades o usos de suelo compatibles entre los otros sectores,
dando mayor peso y preferencia al sector con el valor de aptitud más alto.

El resultado obtenido después de este tratamiento permitió que se definieran un total de 94 UGA, 31
de ellas subdivididas para fines de una mejor delimitación como se explicó anteriormente.
Adicionamente, para lograr una diferenciación clara y fácil, a las UGA que se encuentran dentro del
polígono del PSRDU se les antepuso la letra P aunque mantuvieron su numeración.

## ASIGNACIÓN DE POLÍTICA Y ACTIVIDAD

Para la asignación de las políticas ambientales y criterios a las UGA, se analizaron inicialmente los
valores de aptitud obtenidos para cada sector en la UGA (Tabla 11), lo cual daba una primera
aproximación a la política y criterios a asignar. Sin embargo, debido a los atributos seleccionados por
los sectores que no fueron discriminantes se registraron aptitudes altas en algunas UGA para el
sector Pesca en zonas altas incluso sin costa. Es decir, se extrajo todo aquel atributo físico, biológico
o socio demográfico existente dentro de cada una de las UGA. Esto se logra haciendo intersecciones
entre los polígonos vectoriales de las UGA, y los temas vectoriales de los atributos ambientales para
de esta manera extraer su información (Tabla 12).


```
Tabla 11. Matriz de apoyo para la toma de decisión de la política ambiental a asignar a cada UGA en
función de Fragilidad del (los) ecosistema(s) y su Vulnerabilidad medida en función de la demanda de
recursos naturales que pueden ocurrir en la superficie de cada UGA.
```

```
Tabla 12 Ejemplo de atributos ambientales considerados para la caracterización de las UGA.
```

```
Figura 21 Diagrama de flujo de la obtención de las UGA, su política ambiental y las actividades que generen
menos deterioro ambiental.
```

En la Figura 22 se presenta el Modelo de Ordenamiento Ecológico obtenido con la propuesta de las
Unidades de Gestión Ambiental (UGA), una vez que han sido delimitadas y caracterizadas, reflejando
con esta Política Ambiental correspondiente a la mayor aptitud de la UGA y/o el estado más deseable


de la misma, y considerando particularmente como puntos de referencia la delimitación del polígono
del PSDRU y de las áreas de preservación propuestas.

```
Figura 22. Modelo de Ordenamiento Ecológico del Municipio de Loreto. Unidades de Gestión clasificadas de
acuerdo a la política ambiental correspondiente y la delimitación de la zona del PSRDU.
```

De las 94 UGA finales se obtienen un total de 184 sub unidades de las cuales 51 tienen como política
ambiental el aprovechamiento sustentable, 59 con política ambiental de conservación, 64 de
preservación y 10 de restauración. La división de algunas UGA en sub unidades se debió
principalmente a la delimitación de las zonas de preservación y el límite del PSDRU. Por otro lado, de
acuerdo a la principal actividad asignada a las UGA por su aptitud y características particulares, se
obtuvo una UGA de actividad agrícola, subdividida en 9 unidades, 125 para la conservación, 33 para
la pesca y 20 para el turismo, éstas con sus correspondientes combinaciones con otras actividades
(Figura 23, Tabla 13).

Por otro lado, también se obtuvieron UGA con áreas en las cuales dos sectores registraron valores
altos de aptitud y cuyas actividades no son muy compatibles. Es en estas UGA donde se hizo un
análisis preciso para definir el uso o los usos más adecuados de acuerdo a su aptitud (Tabla 12). Las
actividades se deben realizar de acuerdo a los criterios de regulación a fin de garantizar que se
registre el menor impacto negativo sobre los recursos naturales y sin detrimento de la calidad de vida
de los pobladores.

Finalmente para poder construir un patrón óptimo de la ocupación del territorio del Municipio de
Loreto se hace una restricción de las actividades sectoriales en cada grupo resultante a fin de
subdividir estos grupos de acuerdo a la compatibilidad e incompatibilidad de las actividades de los
sectores que se logra maximizando el valor total de los residuales de Gower obtenidos. Esta
metodología permite maximizar el valor de aptitud total del Municipio.

```
Tabla 13 Cantidad y tipo de sector en las UGA del Municipio de Loreto.
```

Por otro lado, aunque se pudiera ver como posibilidad que se presenten conflictos, es importante
recordar que el propósito de los Programas de ordenamiento ecológico territorial es lograr la
protección del medio ambiente, así como la preservación y el aprovechamiento sustentable de los
recursos naturales. El objetivo último de este proceso es que, en el desarrollo de sus actividades, los
diferentes sectores realicen un aprovechamiento sustentable que permita la conservación,
preservación y protección de los recursos naturales de una región. Por ello, es necesario se
consideren las estrategias, lineamientos y criterios ecológicos o de regulación que garanticen este
aprovechamiento sustentable de los recursos contenidos en cualquiera de las UGA.

La zona donde pueden registrarse los mayores conflictos tanto por el uso de suelo como por la
presión en el uso de recursos naturales requeridos en función de las actividades planeadas a
realizar, es la delimitada dentro del PSRDU (Figura 23). Se registraron más de 8,000 hectáreas
donde los sectores Turismo y Comunidades Pesqueras registran simultáneamente valores altos y
muy altos de aptitud, dentro del polígono de PSDRU. Sin embargo, las actividades realizadas por
ambos sectores son relativamente poco incompatibles siempre y cuando se permitan los accesos a
playa e instalaciones correspondientes a las comunidades pesqueras y no se modifiquen sus
instalaciones. Con ello no se prevé se existan conflictos importantes. Entre los sectores
Comunidades Pesqueras y Conservación se cuantificaron 921 hectáreas en donde ambos sectores
registran simultáneamente valores altos y muy altos de aptitud. Entre estos sectores nuevamente no
se registran altas incompatibilidades mientras las actividades relacionadas a la pesca no afecten los
ambientes críticos y las zonas de conservación y/o preservación de la costa (como manglares y
humedales de inundación).

En la tabla 14 se reportan las hectáreas que analizando de manera comparten los sectores,
señalando de manera especial (amarillo) cuando ambos sectores tienen aptitud alta y muy alta, y es
en estas áreas donde se pueden registrar los principales conflictos ambientales. Solo el 5% de las
hectáreas de alta - muy alta aptitud del sector Comunidades pesqueras se traslapa con el 3% de las
hectáreas de alta aptitud-muy alta aptitud del sector Conservación (921Ha); de éstas, dada la
naturaleza de las actividades que tienen ambos sectores, pueden minimizarse los posibles impactos
si se regulan adecuadamente las actividades a fin de proteger las zonas de importancia para la
conservación, pero permitiendo el acceso a la zona de costa y disponibilidad de agua que requieren
para la pesca ribereña.

El 7% de las hectáreas de alta-muy alta aptitud que se registraron para el sector conservación se
traslapa con el 9% de las hectáreas de alta-muy alta aptitud del sector Turismo (1,778Ha). En este
caso podrían registrar conflictos por la posible incompatibilidad entre las actividades de los dos
sectores, sobre todo en las zonas cercanas a la costa, y más especialmente las que se encuentran
dentro del PSRDU, que tienen elementos de alta importancia para la conservación y donde se
pretenden realizar desarrollos turísticos de alto impacto. En estas zonas se podrían minimizar los
conflictos potenciales a fin de garantizar la sustentabilidad de la zona, dando especial énfasis a los
ambientes críticos y de importancia para la conservación, si se consideran densidades bajas, se
mantienen zonas de vegetación natural con función potencial como corredores biológicos y que
permitan la conservación de los ambientes críticos, vulnerables o frágiles. De protegerse estos sitios
puede darse un desarrollo moderado en dichas zonas que permitirá un crecimiento económico pero
sin menoscabo de la calidad de vida de los pobladores y de los recursos naturales de importancia. Y
esta importancia no es solo de la biodiversidad o por el alto valor ecológico que tiene la zona, sino
que también lo es por el interés como recurso pasajístico que pudiera representar para el sector
Turismo.

```
Figura 23. Modelo de Ordenamiento Ecológico del Municipio de Loreto. Unidades de Gestión y actividades de
mayor aptitud, mostrando la delimitación de la zona del PSRDU.
```

```
Tabla 14. Superficie (ha) de Intersección de los Sectores Conservación, Turismo y Pesca por
Categoría de Aptitud.
```
Por otro lado, los que comparten más hectáreas con valores altos-muy altos de aptitud son los
sectores pesca y turismo (8,789 Ha). Entre estos sectores se pueden minimizar los conflictos ya que
no existe mucha incompatibilidad en las actividades y áreas de desarrollo de las mismas, siempre y
cuando se respeten los accesos a playa o campamentos pesqueros y los sitios con disponibilidad de
agua, y las actividades relacionadas a la pesca o trabajos en los campos pesqueros no afecten los
ambientes críticos y hagan un adecuado manejo de residuos sin afectar las zonas de playa.


## PROPUESTA DE NUEVAS ANP. SIERRA DE LA GIGANTA Y ZONAS COSTERAS PARA PRESERVACIÓN

El resultado del ordenamiento ecológico territorial de Loreto debe delimitar los ambientes relevantes,
determinar las acciones de conservación que se deberán realizar en las áreas o regiones dentro del
Municipio que contengan la riqueza y diversidad de especies más alta y en su caso promover su
incorporación al Sistema de Áreas Naturales Protegidas del Estado de BCS y del país, como el caso
particular de los oasis presentes en el Municipio de Loreto.

La propuesta de las área para ANP y Preservación se hace en función de incluir las áreas de alta
riqueza de especies de flora y fauna, especies endémicas y de zonas de recarga de acuíferos así
como los oasis. Asimismo, se hizo la consideración de generar áreas de conectividad para las
poblaciones de estas especies y para que se mantenga la función de tal manera que los servicios
ambientales se preserven. En relación a la conectividad se evaluó que cumpliera este fin para aves
terrestres migratorias, especies de distribución restringida, depredadores tales como el puma, el
águila real y halcón peregrino, así como el borrego cimarrón. Esta área está delimitada físicamente
en la parte alta de la Sierra de la Giganta, a partir de los 600msnm (Figura 24).

Por otro lado y de manera igualmente relevante y probablemente más debido a las presiones que
tienen por el cambio de uso de suelo, en las partes baja costeras tanto en la parte norte como en la
sur del Municipio, se consideró mantener la conectividad de poblaciones de la gran riqueza de
especies de aves acuáticas residentes e invernantes que llegan a la costa del Municipio, además de
no dejar en situación de aislamiento los manglares de la zona costera de este Municipio. Se hizo la
consideración de estudios diversos a nivel mundial que han demostrado que es mejor tener algunas
áreas continuas relativamente grandes para conectar poblaciones que varias discontinuas (Figura
25)...

```
Figura 24. Modelo de Ordenamiento Ecológico del Municipio de Loreto. Unidades de Gestión con las politicas
ambientales correspondientes y la delimitación de la zona del PSRDU, considerando la zona de la sierra de la
Giganta como área propuesta para promoverse como ANP y dos zonas costeras como zonas de preservación
```
