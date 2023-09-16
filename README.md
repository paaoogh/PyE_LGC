# PyE_LGC

## Descripción
En este repositorio se encuentan los materias que se trabajen durante el semestre 2023-1 de la materia de Probabilidad y Estadístia, así como material complementario sobre el pre-procesamiento de datos para algunos proyectos que puede quedar de referencia.


## Descripción de datos
Dentro de la carpeta de datasets se encuentran archivos de terminación .csv. A continuación se presenta una breve descripción (que iremos construyendo entre todxs).

**SISMOS EN PARICUTIN: Paricutin_2023.csv** 
150 sismos en Michoacán ocurridos en marzo de 2023. El reporte lo pueden encontrar en [este sitio](http://www.ssn.unam.mx/sismicidad/reportes-especiales/2023/SSNMX_rep_esp_20230315_secuenciaMichoacan_M46.pdf). Este dataset cuenta con datos de punto flotante que difieren en sus dimensiones; por lo tanto, uno de los retos para este caso es la interpretabilidad de la combinación de ambos y su abstracción estadística. Una coparación intresante sería combinarlo con el dataset de **Paricutin_Tancitaro.csv** que se obtuvieron de [este sitio](http://www2.ssn.unam.mx:8080/catalogo/ )
- Variables y tipos
- Significado de variables
- Contexto metodológico de producción de datos
- Reservas y dudas *

**SSNMX_sismos.csv**
Este dataset, al igual que los dos anteriores, son obtenidos del [Servicio Sismológico Nacional](http://www2.ssn.unam.mx:8080/sismos-fuertes/). En este caso solamente tenemos datos sobre la primera mitad del año 2022. Sin embargo, son los sismos más grandes registrados. Lo interesante de este conjunto será pensar con respecto a la frecuencia y tendencia de los sistmos. 
- Variables y tipos
- Implicaciones de serialidad en el tiempo
- Contexto metodológico de producciòn de datos
- Reservar y dudas*

**calor_geotermico.csv** 
Este proyecto de Luca Ferrari es sobre los volcanes recientes de la [Sierra Madre Occidental](https://www.sciencedirect.com/science/article/pii/S0375650522000839?via%3Dihub), sus datos originales se encuentran en tablas que requieren de pre-procesamiento. El reto màs interesante de este dataset es que el diccionario de datos sobre este dataset puede contar más de los datos que la misma descripción de datos.
- Variables y tipos
- Diccionario de datos
- Indagación sobre posibilidades de muestreo

**datoMeteo_UMAR - DatosMet_May_Jun_2022.csv**
Este catálogo de la [Universidad del Mar en Puerto Ángel](https://www.mareografico.unam.mx/portal/index.php?page=Estaciones) durante el huracán Agatha de mayo 2022. Lo más curioso de este conjunto es que depende fuertemente del contexto metodológico y diccionario de datos.
- Variables y tipos
- Diccionario de datos
- Contexto de datos
- Contexto metodológico de selección de datos

**hawaii_earthq.csv**
[Sismicidad en Hawaii desde 1970](https://earthquake.usgs.gov/earthquakes/search/ ) con datos sencillos seriales sobre sus epicentros y descripciones básicas. En este caso, serìa muy interesante jugar con las muestras y observabilidad de correlaciones entre algunos atributos.
- Variables y tipos
- Diccionario de datos
- Indagación en uso de variables
- Propuesta de análisis en frecuencias y tendencias*

**mars-data.csv**
Qué maravilla poder tener datos sobre simicidad en [Marte del 2020](http://www.insight.ethz.ch/seismicity/catalog/v1/). Este conjunto ha sido curado desde los metadatos en XML; debido a su complejidad, también se encuentra el archivo JSON para la comprensión de éstos. El reto más grande será el análisis inicial y creación de diccionario de datos. 
- Variables y tipos
- Diccionario de datos
- Diagrama de datos
- Indagación en contexto metodológico de extracción de datos

**neas_nasa.csv**
Éste es un trocito de los datos de la [NASA](https://cneos.jpl.nasa.gov/nhats/ ) sobre observaciones de asteroides cercanos a la tierra. Tiene variables muy interesantes pero que se encuentran en dimensionalidades distintas y algunos atributos necesitan más manipulación de datos. 
- Variables y tipos
- Diccioanrio de datos
- Separabilidad de columnas-atributos
- Contexto de metodología sobre NEAS

**playa_azul.csv**
Estos datos son de una práctica de campo, son datos de resistividad en Playa Azul. Más información sobre éstos y e investigación sobre resistividad será necesaria para llevar a cabo el proyecto.
- Variables y tipos
- Diccionario contextual de datos
- Contexto metodológico de extracción de datos

**solar_flares.csv**
Como su nombre lo dice, son datos de eyecciones solares obtenidas del [National Oceanic and Atmospheric Administration](https://www.ngdc.noaa.gov/stp/solar/solarflares.html) de septiembre del año 2022. Lo interesante de este conjunto es la dimensionalidad en la que se encuentran los datos y compararlos con las tendencias y frecuencias que puede tener el sol. Además, puede dar pie a un análisis y abstracción de la representatividad subjetiva de los datos que obtenemos con los que podrían llegar a existir.
- Variables y datos
- Inspección/indagación sobre la dimensionalidad de datos
- Conexto metodológico de extracción de datos.

