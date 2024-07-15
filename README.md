
## README

<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>

 <h2 align=center>Miguel Denis</h2>




Proyecto Individual N°2 para Henry (Data Analytics) 

<hr>  

## Descripción
En este Proyecto extraemos data de ENACOM de Argentina para realizar un Análisis Estadístico acompañado de un Dashboard respecto al acceso y conexiones a Internet en ese país.

## Tabla de Contenido
1. [Descripción](#descripción)
2. [Librerias y Servicios](#librerías-y-servicios-utilizados)
3. [Estructura del Repositorio](#estructura-del-repositorio)
4. [Uso y Ejecución](#uso-y-ejecución)
5. [Fuente de datos](#fuente-de-datos)
6. [Metodología](#metodología)
7. [KPIs](#kpis)
8. [Conclusiones del Análisis](#conclusiones-del-análisis)



## Librerías y Servicios utilizados:
- Python 3.7 o superior
- pandas
- numpy
- Power BI Desktop


## Estructura del Repositorio

- `Dashboard.pbix`: Archivo PowerBI con el Dashboard del Análisis

- `data/`: Carpeta con los archivos de datos procesados a partir del dataset original que fueron utilizados

- `notebooks/`: Contiene el notebook de Jupyter con el Análisis exploratorio y preprocesamiento de datos

- `README.md`: Archivo de documentación y Análisis del proyecto.


## Uso y Ejecución
1. Para ver el Dashboard descargar el archivo `Dashboard.pbix` y abrirlo en Power BI
2. Si faltaran las tablas, cargar los archivos que se encuentran en la carpeta `data/`



## **Fuente de Datos**

- El dataset original proviene del Ente Nacional de Comunicaciones de Argentina (ENACOM) disponibles en el sitio web [https://indicadores.enacom.gob.ar/datos-abiertos](https://indicadores.enacom.gob.ar/datos-abiertos)

- Para este Análisis, se trabajará solo con los datos del link `Internet` que abarcan del año 2014 a 2023 incluidos

- Los datos preprocesados utilizados en el Dashboard se encuentran en este repositorio en la carpeta `data/`



## Metodología
Luego de una previa selección de las hojas más importantes, se realizó un Análisis Exploratorio de Datos del dataset original, limpiando duplicados, faltantes e irregularidades, obteniendo 2 datasets para el Dashboard:

-`Datos_nacionales.xlsx`: Acceso a internet, Velocidades de conexión, Ingresos y Tecnologías de conexión a nivel Nacional por año y trimestre

-`Datos_provinciales.xlsx`: Acceso a internet, Velocidades de conexión y Tecnologías de conexión por Provincia, año y trimestre

## KPIs

Se definen las siguientes KPI a observar:

- Aumento de un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia

- Aumento de un 5% en la velocidad promedio de descarga para el próximo trimestre por provincia.

- Aumento del 8% en el uso de fibra óptica como medio de conexión respecto al trimestre anterior por provincia



## Conclusiones del Análisis

**Acceso a Internet**

- Las conexiones a internet han aumentado consistentemente de 6.4 Millones a comienzos del año 2014 a 11.5 Millones para el fin de 2023.

- Del Total de 11.5 Millones de conexiones actuales, 8 Millones se encuentran solamente entre Buenos Aires, Capital Federal, Córboda y Santa Fe.

- Los accesos por cada 100 habitantes / 100 hogares han aumentado consistentente en el tiempo, y para finales del año 2023, el acceso a internet promedio por cada 100 habitantes era de 21.27%, con una desviación estándar de 8.71 entre provincias. 
<br> El mínimo se encuentra en Formosa con 9.98% y el máximo en Capital Federal, con 47,8%.

- El Ingreso total del servicio ha crecido exponencialmente, muy por sobre el aumento de conexiones. Esto se debe a un contexto socio-económico nacional de inflación más que por el precio del servicio

<br>

**Velocidad de Bajada**

- La velocidad de bajada ha crecido explosivamente, con un salto a finales del año 2022, pasando por una media en 2014 de 3,40 MBps, en 2020 de 22.26 MBps y a finales de 2023 de 85.21 MBps, creciendo un 24,4% respecto al año anterior

- A finales del año 2023, la velocidad de bajada nacional promedio era de 85.21 MBps, con el mínimo en Tierra del Fuego con 17.92 MBps y el máximo en Capital Federal con 218.13 MBps.

- Las conexiones de velocidades más bajas (menos de 30 Mbps) han sido desplazadas por las velocidades de más de 30 MBps, hasta constituir un 71.22% de las conexiones a nivel nacional para 2023

**Tecnologias de Conexión**

- La forma de conexión más utlizada en el año 2014 (ADSL 57%), ha perdido dominancia. Para el año 2023, el 52% era Cablemodem, 32% Fibra óptica y ADSL sólo un 9%

- En cuanto a Dial-up/Banda ancha fija, Dial-up pasó de 36 mil conexiones en 2014 a un tercio de eso en 2023. 
<br> Mientras que la banda ancha fija casi duplicó desde 6 millones en 2014 a 11.53 millones en 2023


