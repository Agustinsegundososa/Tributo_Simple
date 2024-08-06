<img src="https://github.com/IsmaDeveloper16/Tributo_Simple/blob/main/imagenes/header.jpeg" alt="Header" width="1200" height="150">

El proyecto implica la implementación de un proceso ETL (Extracción, Transformación y Carga) utilizando Python, seguido de la carga de los datos procesados en una base de datos relacional y la creación de un reporte interactivo en PowerBI. Los datos utilizados provienen de la página de la AFIP y se proporcionaron en formato tmp, con un volumen de más de 5 millones de registros.

**Los archivos del proyecto se pueden encontrar en el siguiente link:** https://drive.google.com/drive/folders/1Y-yE36JlBGLdA7z-014uWugXyUDooXHl?usp=sharing

## Proceso ETL
### Extracción
Para la extracción de los datos se utilizaron las siguientes librerías de Python:
- BeautifulSoup
- zipfile
- os
- requests

### Transformación
Para la transformación de los datos, se utilizó la librería Pandas. Los datos se procesaron para convertirlos de su formato original tmp a formato CSV, lo que permitió manipular y limpiar los datos de manera efectiva.

### Carga
Los datos transformados se cargaron en una base de datos MySQL con una estructura que incluye tablas para actividad monotributo, denominación, empleador, impuesto a las ganancias, impuesto IVA, integrante social y tipo de monotributo, y una tabla principal que referencia a estas tablas.

## Reporte en **PowerBI**
El reporte realizado en PowerBI cuenta con 2 paginas principales, en las cuales quise abordar temas especificos con los datos.
- **Registros/actividad:**
<div align="center">
<img src="https://github.com/IsmaDeveloper16/Tributo_Simple/blob/main/imagenes/reporte%202.jpg" alt="Header" width="800" height="400">
</div>

- **Impuestos:**
<div align="center">
<img src="https://github.com/IsmaDeveloper16/Tributo_Simple/blob/main/imagenes/reporte%203.jpg" alt="Header" width="800" height="400">
</div>

## Conclusion:
Para finalizar este proyecto me gustaria resaltar mi capacidad para poder realizar procesos ETL y realizar visualizaciones en PowerBi, tambien me gustaria resaltar que estoy comprometido en aprender a realizar reportes con Looker studio.
