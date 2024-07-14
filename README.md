
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

- Para este Análisis, se trabajará solo con los datos del link `Internet`

- Los datos preprocesados utilizados en el Dashboard se encuentran en este repositorio en la carpeta `data/`



## Metodología
Luego de una previa selección de las hojas más importantes, se realizó un Análisis Exploratorio de Datos del dataset original, limpiando duplicados, faltantes e irregularidades, obteniendo 2 datasets para el Dashboard:

-`Datos_nacionales.xlsx`: Acceso a internet, Velocidades de conexión, Ingresos y Tecnologías de conexión a nivel Nacional por año y trimestre

-`Datos_provinciales.xlsx`: Acceso a internet, Velocidades de conexión y Tecnologías de conexión por Provincia, año y trimestre

## KPIs

Se definen las siguientes KPI a observar:

- Aumento de un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia

- Aumento de un 5% en la velocidad promedio de descarga para el próximo trimestre por provincia.

- Tercer KPI probablemente sobre las tecnologias de conexion



## Conclusiones del Análisis
- 


