<img  align="left" width="150" style="float: left;" src="https://www.upm.es/sfs/Rectorado/Gabinete%20del%20Rector/Logos/UPM/CEI/LOGOTIPO%20leyenda%20color%20JPG%20p.png">
<img  align="right" width="60" style="float: right;" src="http://www.dit.upm.es/figures/logos/ditupm-big.gif">

<br/><br/><br/>

# Práctica 2 - CV

Versión: 25 de Enero de 2023

## Objetivos

* Crear una página web con código HTML.
* Definir el estilo gráfico de una página web con CSS.


## Descripción de la práctica

En esta práctica, elaboraremos una página web estática con la información del curriculum vitae del alumno. Para definir la estructura del documento se utilizará HTML y para el estilo gráfico, CSS. La página web incluirá los bloques semánticos típicos (`<header>`, `<main>`, `<section>`, `<footer>`, etc.); integrará objetos externos como imágenes o enlaces; y modificará el estilo a través de CSS.    


## Descargar el código del proyecto

Instrucciones [aquí](https://github.com/CORE-UPM/Instrucciones_Practicas/blob/main/README.md#descargar-el-c%C3%B3digo-del-proyecto).

## Tareas

Todas las tareas en esta práctica consistirán en escribir en el **directorio raíz del proyecto** el código HTML de la página web en el fichero `cv.html`, y los estilos CSS en el fichero `cv.css`.

Para superar la entrega el alumno debe incluir en el CV:

### 1. Estructura básica de un fichero HTML

* Crear el esqueleto de un fichero HTML llamado `cv.html`. Debe incluir las etiquetas básicas de todo fichero HTML: `<html>`, `<head>`, `<body>`, etc. 
* Crear el fichero CSS (`cv.css`) y cargarlo desde el HTML.

### 2. Head

Incluir en el campo head:
* Título (por ejemplo CV de + su nombre)
* Incluir la hoja de estilos `cv.css`

### 3. Header

Incluir header (`<header>`) que contenga:
* Campo con nombre y apellidos del alumno. La etiqueta utilizada, por ejemplo `<h1>`, debe incluir como atributo `id="nombre"`. 
* Fecha de nacimiento del alumno. La etiqueta utilizada, por ejemplo `<p>`, debe incluir como atributo `id="fecha_nacimiento"`.
* Fotografía del alumno (`img src="foto.jpg"`). La fotografía debe guardarse en el directorio raíz del proyecto y llamarse `foto.jpg`. 
* Otros datos personales como email, dirección, etc., que completen el CV.

### 4. Secciones

El CV debe incluir las siguientes secciones (marca HTML section):

* Sección 1 con atributo `id="estudios"`. El contendio de la sección debe incluir la información académica del alumno. Se recomienda utilizar una lista que muestre en orden cronológico inverso los estudios cursados.
* Sección 2 con atributo `id="laboral"`. El contenido de la sección debe incluir la experiencia laboral del alumno o intereses laborales. Se recomienda utilizar una lista que separe las distintas entradas.
* Sección 3 con atributo `id="otros"`. Se recomienda utilizar una lista como contenido de esta sección. El contenido de la sección debe incluir:
  * Un enlace al correo UPM del alumno (con el @alumnos.upm.es)
  * Información adicional, por ejemplo, idiomas, aficiones, etc.

### 5. Footer

Incluir un footer con la fecha de actualización del CV. Debe contener el siguiente texto: `Actualizado el` + fecha de actualización.

### 6. Modificar el CSS

Modificar el estilo de la página web. 

* Como mínimo se pide modificar el estilo de la etiqueta `<body>` (cambiar el color de fondo) y el estilo de la etiquet `<section>` (cualquier cambio, por ejemplo, añadir borde a las secciones). 
* Realizar otros cambios sobre el CSS.


## Pruebas con el autocorector

Instrucciones [aquí](https://github.com/CORE-UPM/Instrucciones_Practicas/blob/main/README.md#pruebas-con-el-autocorector).

## Pruebas manuales y capturas de pantalla

Instrucciones [aquí](https://github.com/CORE-UPM/Instrucciones_Practicas/blob/main/README.md#pruebas-manuales-y-capturas-de-pantalla).

Capturas a entregar con esta práctica: 

- Captura 1: Captura de pantalla de la página resultante
<kbd>
<img src="https://user-images.githubusercontent.com/52309/211205417-e7065838-a540-43ac-81ad-79752b1bdf37.png" alt="drawing" width="500"/>
</kbd>

- Captura 2: Captura de pantalla de las developer tools (de cualquier navegador, en el siguiente ejemplo se ven las de Chrome pero vale Firefox, Edge, etc.) en la que se vea el html de la página, con algunas secciones abiertas:
<kbd>
<img src="https://user-images.githubusercontent.com/52309/212846269-c6d0eb5c-89dc-4ee0-a344-ee96a3fc2bf2.png" alt="drawing" width="500"/>
</kbd>

## Instrucciones para la Entrega y Evaluación.

Instrucciones [aquí](https://github.com/CORE-UPM/Instrucciones_Practicas/blob/main/README.md#instrucciones-para-la-entrega-y-evaluaci%C3%B3n
).

## Rúbrica

Se puntuará el ejercicio a corregir sumando el % indicado a la nota total si la parte indicada es correcta:

- **10%:** Existen todas las etiquetas del esqueleto básico de HTML. 
- **10%:** La página web incluye la hoja de estilos (CSS).
- **30%:** Información de la cabecera:
  - **10%:** Existe la cabecera.
  - **10%:** La cabecera contiene la foto (foto.jpg).
  - **10%:** La cabecera contiene los datos personales (mímimo nombre y fecha de nacimiento).
- **20%:** información de las secciones:
  - **10%:** Existen las tres secciones pedidas (estudios, laboral, y otros).
  - **10%:** La sección otros incluye el correo del alumno (con @alumnos.upm.es)
- **10%:** Existe el pie de página con la fecha de actualización.
- **20%:** Se han añadido los estilos solicitados al body y sections de la página web.


Si pasa todos los tests se dará la máxima puntuación.
