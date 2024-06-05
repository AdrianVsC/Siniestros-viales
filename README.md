# SINIESTROS VIALES en la Ciudad de Buenos Aires

![alt text](/imagenes/image-4.png)

### Índice del contenido:
* [Introducción](#introducción)
* [Contexto](#contexto)
* [Presentación del trabajo de Data Analytics](#presentación-del-dashboard-interactivo)
* [Dashboards en Power BI](#dashboard-powerbi)
* [Análisis y conclusiones](#objetivo-final)

## Introducción:
En una metrópolis como Buenos Aires, los siniestros viales son preocupación considerable debido al alto volumen de tráfico y la densidad poblacional. Estos eventos impactan significativamente en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.

Las tasas de mortalidad asociadas a siniestros viales son un indicador crítico de la seguridad vial en cualquier región. Dichas tasas suelen calcularse como el número de muertes por cada cierto número de habitantes o por cada cantidad específica de vehículos registrados. La reducción de estas tasas es un objetivo primordial para mejorar la seguridad vial y proteger vidas en la ciudad.

## Contexto:
En Argentina, anualmente mueren cerca de 4,000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, estos continúan siendo la principal causa de muertes violentas en el país. Los informes del Sistema Nacional de Información Criminal (SNIC) del Ministerio de Seguridad de la Nación revelan que entre 2018 y 2022 se registraron 19,630 muertes en siniestros viales en todo el país, lo que equivale a 11 víctimas fatales diarias.

En el año 2022, se contabilizaron 3,828 muertes fatales por siniestros viales. Expertos en seguridad vial indican que en Argentina, la probabilidad de que una persona muera en un siniestro vial es dos o tres veces más alta que en un hecho de inseguridad delictiva.

## Presentación del trabajo de Data Analytics 

**1. Exploración de Datos**

* Revisa los diccionarios de datos para comprender las variables.
* Examina las tablas de datos "df_v" y "df_h" para identificar la estructura y el contenido.
* Identifica variables clave relacionadas con siniestros viales (por ejemplo, fecha, hora, ubicación, tipo de vehículo).

**2. Limpieza y Preparación de Datos**

* Identificación de datos faltantes
* Tratamiento de datos faltantes identificando si sería mejor eliminar o rellenar el nulo
* Identificación de duplicados mediante duplicated(keep=first)
* Eliminación de duplicados
* Convierte los datos al formato adecuado para el análisis (por ejemplo, numérico, categórico).

**3. Análisis de Datos**


* Corrige las inconsistencias en los datos (por ejemplo, valores atípicos, errores ortográficos), usando boxplot para los outliers e histogramas para los errores tipográficos.

![alt text](/imagenes/image-1.png)

### Realiza un análisis exploratorio de datos para identificar patrones y tendencias, como por ejemplo, la cantidad de víctimas por año:

![alt text](/imagenes/image.png)

### Identifica factores que posiblemente correlacionados, como la hora del siniestro, el mes del año, el vehículo, etc.

![alt text](/imagenes/image-2.png)


## Presentación del dashboard interactivo


**1. Dashboard Interactivo**

* Desarrolla un dashboard interactivo que permita a los usuarios:
* Explorar los datos mediante gráficos interactivos (por ejemplo, histogramas, gráficos de dispersión).
* Filtrar los datos por variables específicas (por ejemplo, tipo de vehículo, ubicación).
* Ver tablas resumen que proporcionen estadísticas clave (por ejemplo, número de víctimas fatales por año)

![alt text](/imagenes/image-3.png)

# Objetivo Final:

Proporcionar información valiosa que ayude a las autoridades a implementar medidas efectivas para reducir las víctimas fatales en los siniestros viales.

### ETL
Se llevo a cabo un pequeño trabajo de preprocesamiento de datos para normalizar columnas y valores. Del Cual salieron los archivos para el EDA.

### EDA
En el archivo EDA se análizo el conjunto de datos proveniente del ETL, en cual se le hizo tratamientos a valores atípicos o outliers. En este nuestro principal objetivo era la busqueda de patrones y tendencias en los conjuntos de datos, donde se encontraron insights valiosos para la creación de KPIs en PowerBI.

### Dashboard PowerBI
Se utilizo la herramienta de Microsoft, PowerBI, para la creación de un dashboard interactivo, para facilitar la vizualización de los datos. En este mismo se llevo a cabo la creación de KPIs para el análisis de la situación de los siniestros viales en la ciudad de Buenos Aires.