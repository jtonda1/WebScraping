# WebScraping
Práctica número 1 asignatura Tipología y Ciclo del Dato

DOI del DATASET.- DOI: 10.5281/zenodo.3748912

Miembros del equipo:

Esta práctica se ha realizado de manera individual por Juan Ramón Tonda Barberá.

Motivación:

A lo largo del ejercicio de mi profesión me he encontrado con la necesidad de extraer datos de un pdf. Por lo tanto he querido realizar la presente práctica en esa línea, es decir, localizar un documento con datos en un pdf, extraerlos y tratarlos. 

Método empleado:

Para la realización de la presente práctica he utilizado las siguientes herramientas:
- Jupyter Notebook incluido en Anaconda para el código realizado en lenguaje Python.
- Una API denominada PDFtoExce_API (https://pdftables.com/pdf-to-excel-api) que utilizaré para convertir el PDF a CSV dentro del código Python
- Herramienta Excel para realizar alguna transformación del documento CSV generado por la APV con el Query Editor, como por ejemplo la eliminación de cabeceras y texto.
- Las librerías requests, pandas, matplotlib y para el tratamiento de fechas datetime.

Dataset Seleccionado: "Contaminación de NO2 en la Pista de Silla de Valencia".

El dataset seleccionado es un conjunto de datos con información procedente de una estación meteorológica situada en la Pista de Silla  de Valencia. Dicho conjunto de datos presenta para cada día del año la información recogida respecto a diferentes contaminantes de interés entre los que se encuentra en Dióxido de Nitrógeno, agente contaminante producido por los vehículos que circulan por la zona.

Resultado:

El resultado final es la creación de un Dataset con la información diaria para los años 2019 y 2020 del contaminante Dióxido de  Nitrógeno. 
