<style>
  body {
    background-color: #9b2059;
    color: #eaeaea;
  }
  div.highlighter-rouge,
  div.highlighter-rouge .highlight,
  div.highlighter-rouge pre {
    background-color: #000;
    color: #f2f2f2;
  }

  div.highlighter-rouge pre {
    padding: 1em;
    border-radius: 8px;
    overflow-x: auto;
  }

  div.highlighter-rouge code {
    background: transparent;
    color: inherit;
  }
</style>

# Multimedial

<img src="img/giphy%20(2).gif" alt="GIF de Multimedial" width="auto" height="auto" />

## Bitácora de taller multimedial: Aura Encina 
### Índice

## Unidad I. Taller Multimedia: Desarrollo Web (HTML)
1. [Ejercicio 1, codigo base](#1-ejercicio-1-semana-1-mi-primera-página) <br>
2. [Primer vistazo y enlaces](#2-estructura-de-carpetas-del-proyecto) <br>
3. [Construcción de la portada (w/index.html)](#3-construcción-de-la-portada-windexhtml) <br>
4. [Navegación entre páginas (Mini sitio de 3 páginas)](#4-navegación-entre-páginas-mini-sitio-de-3-páginas) <br>
5. [Publicación en GitHub Pages](#5-publicación-en-github-pages) <br>
6. [Ver sitio web / Portafolio en vivo](https://aura0403.github.io/Multimedial/w/index.html)

## <span style="color: purple;">Unidad 2</span>
1. [Chroma](https://drive.google.com/file/d/1FoSuo0MsIiyIaFPuccK0SWyaMMAqe5me/view?usp=drive_link) <br>
2. [Lsystem](https://drive.google.com/file/d/1SQJT6WJU7a_okktyoo1sFnawrnpI_QqD/view?usp=drive_link) <br>
3. [Point](https://drive.google.com/drive/folders/17M0PenrL7a8SVX96ALYR3-NVj5Ro60AU?usp=drive_link) <br>
4. [Comfy](https://drive.google.com/drive/folders/1fxfipq6L57-wN_1qWwnH6ICLYTfczmQC?usp=drive_link) <br>
5. [Proyecto personal](https://drive.google.com/file/d/1FSXz_iKuLHTPLSfBmPNvoSj7b77pBnDH/view?usp=drive_link)

---

## Unidad I. Proceso de creación del sitio web

#### 1. Ejercicio 1, semana 1: Mi primera página
El primer paso nos permitio comprender la estructura básica de un documento HTML5 y asi empezar nuestra pagina web.

```html
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin del head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

---

#### 2. Estructura de carpetas del proyecto

En este paso podemos ver como se genera una interaccion entre enlaces, ademas se aprecia un pequeño cambio al posar el cursor en cada enlace poniendo una linea debajo de cada palabra y cambiando el color.

<video controls width="640">
  <source src="https://raw.githubusercontent.com/Aura0403/Multimedial/main/img/Grabaci%C3%B3n%202026-11-17%20124538.mp4" type="video/mp4">
  Tu navegador no permite reproducir el video. [Ábrelo aquí](img/Grabaci%C3%B3n%202026-11-17%20124538.mp4).
</video>


---

#### 3. Construcción de la portada (w/index.html)
En este paso pudimos construir la portada en base a este codigo, en el cual se encuentra el nombre y la disciplina del autor la pagina.

```html
<!DOCTYPE html>
<!-- Declara el tipo de documento HTML5 -->

<html lang="es">
<!-- Inicio del documento HTML -->

<head>
<!-- Sección de configuración y metadatos -->

    <meta charset="UTF-8">
    <!-- Define la codificación de caracteres UTF-8 -->

    <title>Aura Encina</title>
    <!-- Título que aparece en la pestaña del navegador -->

</head>
<!-- Cierre de la configuración -->

<body>
<!-- Inicio del contenido visible en la página -->

    <div>
    <!-- Contenedor general que agrupa los elementos de la portada -->

        <header>
        <!-- Encabezado semántico con la identidad de la artista -->

            <h1>Aura Encina</h1>
            <!-- Título principal de nivel 1 con el nombre de la artista -->

            <h3>Artista visual</h3>
            <!-- Subtítulo de nivel 3 que indica su disciplina -->

        </header>
        <!-- Fin del encabezado -->

        <nav>
        <!-- Sección semántica para los enlaces de navegación del sitio -->

            <a href="obra.html">Obras</a>
            <!-- Enlace que dirige hacia la página obra.html -->

            <a href="contacto.html">Contacto</a>
            <!-- Enlace que dirige hacia la página contacto.html -->

        </nav>
        <!-- Fin del menú de navegación -->

        <img src="img/IMG_2147_Original.jpeg" alt="Bodegon" width="500">
        <!-- Inserta la imagen desde la subcarpeta local img/ -->
        <!-- alt="Bodegon" describe la obra para accesibilidad -->
        <!-- width="500" fija el ancho de visualización en 500 píxeles -->

    </div>
    <!-- Fin del contenedor principal -->

</body>
<!-- Cierre del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```


---

#### 4. Navegación entre páginas (Mini sitio de 3 páginas)
Para conectar la pagina completa, se enlazaron tres documentos HTML (`index.html`, `obra.html` y `contacto.html`):



##### Ejemplo de enlaces internos utilizados para navegar entre secciones:
```html
<!-- Navegación desde index.html hacia las páginas internas -->
<nav>
    <a href="obra.html">Obras</a>
    <a href="contacto.html">Contacto</a>
</nav>

<!-- Enlace de retorno desde obra.html o contacto.html hacia la portada -->
<a href="index.html">Inicio</a>
```

---

#### 5. Portafolio web
En mi pagina existe un apartado en "obra.html" que permite hacer un recorrido de mis obras:

<video controls width="640">
  <source src="https://raw.githubusercontent.com/Aura0403/Multimedial/main/img/Grabaci%C3%B3n%202026-11-17%20130942.mp4" type="video/mp4">
  Tu navegador no permite reproducir el video. [Ábrelo aquí](img/Grabaci%C3%B3n%202026-11-17%20130942.mp4).
</video>

Sitio accesible en:
   * [https://aura0403.github.io/Multimedial/w/index.html](https://aura0403.github.io/Multimedial/w/index.html)

---

## <span style="color: purple;">Unidad 2: Touch designer </span>
### Programación visual creativa basada en nodos e IA generativa

1. [Chroma](https://drive.google.com/file/d/1FoSuo0MsIiyIaFPuccK0SWyaMMAqe5me/view?usp=drive_link) — Experimentación con clave de color y composición de imagen.
2. [Lsystem](https://drive.google.com/file/d/1SQJT6WJU7a_okktyoo1sFnawrnpI_QqD/view?usp=drive_link) — Generación procedural de estructuras ramificadas mediante sistemas-L.
3. [Point](https://drive.google.com/drive/folders/17M0PenrL7a8SVX96ALYR3-NVj5Ro60AU?usp=drive_link) — Trabajo con nubes de puntos (*Point Clouds*) y manipulación espacial.
4. [Comfy](https://drive.google.com/drive/folders/1fxfipq6L57-wN_1qWwnH6ICLYTfczmQC?usp=drive_link) — Flujos de trabajo modulares basados en nodos en ComfyUI.
5. [Proyecto personal](https://drive.google.com/file/d/1FSXz_iKuLHTPLSfBmPNvoSj7b77pBnDH/view?usp=drive_link) — Desarrollo de obra personal integrando herramientas multimediales.
