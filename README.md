# Desafío Legalbot

## Objetivo e Instrucciones
El objetivo de este desafío es validar tus habílidades lógicas y conocimientos de programación. Hemos preparado esta actividad con desarrollos que ya hemos hecho en la empresa y nos gustaría saber como los hubieses enfrentado tu. 

Este desafío cuenta de dos partes independientes. Si no logras realizar alguna de ellas envía de todas formas tus respuestas de las otras partes. Envía tus resultados en forma de repositorio en Github.


## Parte 1: Scraper
En la página del Diario Oficial (http://www.diariooficial.interior.gob.cl) se encuentran todas las publicaciones digitalizadas de los últimos años. Estas publicaciones corresponden a extractos de publicaciones de leyes, normas y constitución de empresas entre otras. Para este ejercicio nos enfocaremos solo en la parte de empresas.

Si navegas a la sección de "EDICIÓN ELECTRÓNICA" y luego a la sub-seccion de "EMPRESAS Y COOPERATIVAS" verás un detalle de todas las Constituciones, Modificaciones y Disoluciones del día actual.

Escribe un "seudo código" o describe la lógica que utilizarías para resolver las siguientes preguntas:

..a) Guardar en un arreglo TODOS los links de los archivos PDF que aparecen en el día de actual. Aquellos del tipo Ver PDF (CVE-157XXXX)
..b) Guardar SOLO los links PDF de las CONSTITUCIONES (Dejar fuera Modificaciones y Disoluciones) del día actual.
..c) Guardar en un arreglo TODOS los links de los archivos PDF de CONSTIUCIONES, MODIFICACIONES Y DISOLUCIONES del año 2018
..d) Guardar en un arreglo TODOS los links de los archivos PDF de CONSTIUCIONES, MODIFICACIONES Y DISOLUCIONES del año 2016

## Parte 2: OCR
En la carpeta "parte-2" verás 5 archivos PDF con constituciones de sociedad. 

a) Escribe un código en Python que sea capaz de extraer el texto de cada uno.
b) Escribe una función que tenga como input el texto extraído en la parte (a) y como output el domicilio de la sociedad.
c) ¿Puedes extraer con la misma función de la parte (a) los textos de los PDF en la carpeta "parte-2-b"? ¿Qué es lo distinto, si es que no pudiste? ¿Se te ocurre una forma de resolverlos?
