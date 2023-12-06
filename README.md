<h1 align='center'>
 <b>SINIESTROS VIALES BUENOS AIRES</b>
</h1>

<h1 align='center'>
 <b>Análisis de Accidentes de Tránsito en la Ciudad Autónoma de Buenos Aires</b>
</h1>

<p align='center'>
<img src="https://cdn.aarp.net/content/dam/aarp/auto/2021/05/1140-minor-fender-bender-esp.imgcache.rev.web.700.402.jpg" alt="Accidente de tránsito">
</p>

# Introducción

Este proyecto aborda el análisis de datos de accidentes de tránsito en la Ciudad Autónoma de Buenos Aires con el objetivo de proporcionar información crucial para tomar medidas que reduzcan las víctimas fatales en siniestros viales. El proyecto se desarrolla desde un rol de analista de datos, en colaboración con el `Observatorio de Movilidad y Seguridad Vial` (OMSV) de la ***Secretaría de Transporte*** del Gobierno de la Ciudad Autónoma de Buenos Aires y se basa en datos recopilados entre 2016 y 2021.

# Proceso de Trabajo

El análisis se centra en dos bases de datos en archivos Excel: `homicidios.xlsx` y `lesiones.xlsx`, que contienen información sobre accidentes de tránsito en la Ciudad de Buenos Aires. Estos datos se someten a un proceso de ETL para unificar y limpiar los datos. Luego, se realiza un análisis exploratorio de datos (EDA) para comprender las tendencias y patrones clave.

### Paso 1: ETL

- Extracción, transformación y carga de datos de `homicidios.xlsx` y `lesiones.xlsx`.
- Unión de datos de víctimas fatales y víctimas con lesiones en un solo DataFrame.

### Paso 2: EDA

- Normalización de tipos de datos y limpieza.
- Visualización y análisis inicial.
- Creación de `siniestrosEDA.csv` Power BI.

### Paso 3: Visualizaciones y KPI

- Creación de visualizaciones específicas y cálculo de KPI en `Visualizaciones.ipynb`.
- Generación de archivos `kpi_1.csv`, `kpi_2.csv` para su consulta en Power BI.

### Paso 4: Power BI

- Creación de un dashboard interactivo y un informe de análisis.
