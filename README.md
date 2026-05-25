# Int1-Practica02-250780
---

En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones de proyectos de desarrollo de software, aplicando princiíos de buenas prácticas den Documentación, Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador

Elaborado por: **Erick Cruz Gonzalez**

Materia: **Proyecto Integrador**

Docente: **M.T.I Marco Antonio Ramírez Hernández**

Periodo: *Mayo - Agosto*

## Comandos Básicos para Maquetado de la Documentación titularizando el estandar de Markdown (.md)
---

Markdown es el estándar utilizado por Git y GitHub, para estilizar (maquetar) la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

###1.- Encabezados o Títulos (HEADERS)
**EJEMPLOS**

# Enabezado de nivel 1
## Enabezado de nivel 2
### Enabezado de nivel 3
#### Enabezado de nivel 4
##### Enabezado de nivel 5
###### Enabezado de nivel 6
####### Encabezado de nivel 7 - *El estandar solo permite 6 niveles para títulos , a partir del séptimo será presentado como texto plano (sin estilo)* 

### 2. Separadores (SEPARATORS)

Si se desea marcar una separación visual de los contenidos podemos utliizar una línea horizontal indicando tres caráctees - continuos, en el maquetado.

***EJEMPLO***

### Título de la sección
---
Texto después del separador

### 3.- Párrafos (PARRAGRAPHS)

Son utilizados para presentar grandes secciones de texto que describen detalladamente el contenido de las secciones de la documentación, detallan procesos, explican código o contexto teórico.

***Ejemplo***
Párrafo 1: Este texto es del párrafo 1 Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1Este texto es del párrafo 1.

Párrafo 2: Este texto es del párrafo 2 Este texto es del párrafo 2 Este texto es del párrafo 2 Este texto es del párrafo 2 Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2Este texto es del párrafo 2.Este texto es del párrafo 2.

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**, **centrado** o **justificado**, debemos utilizar una etiqueta ```<p>``` con la propiedad align y la dirección deseada.

<p align="left"> Parrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la izaquierdaParrafo alineada a la 


<p align="right"> parrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la derechaparrafo alineado a la 


<p align ="center">parrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centradaparrafo con alineación centrada

<p align = "justify"> parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado  parrafo con texto justificado.