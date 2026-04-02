## Taller Multimedial  
1.[Ejercicio 1 Semana 1](https://github.com/Aura0403/Multimedial/blob/main/README.md#:~:text=Ejercicio%201%20semana%201)<br>
2.[Semana 2](https://github.com/Aura0403/Multimedial#:~:text=Semana%202-,ejercicio,-2%20(Enlaces))<br>
3.[Semana 3](https://github.com/Aura0403/Multimedial/blob/main/README.md#:~:text=Semana%203%3A%20Mini%20sitio%20(3%20p%C3%A1ginas%20conectadas))<br>


Ejercicio 1 semana 1

```
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

  background-color: pink;
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
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->

```
## Semana 2 ejercicio 2 (Enlaces)

Ejemplo 1:

```
<a href="pagina2.html">Ir a la página 2</a>
```

Ejemplo 2:

Index.html

```
<!DOCTYPE html>
<html>
<head>
<title>Mi sitio</title>
</head>

<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>

```

Pagina.html

```
<!DOCTYPE html>
<html>
<head>
<title>Página 2</title>
</head>

<body>

<h1>Esta es la segunda página</h1>

<a href="index.html">Volver a la página principal</a>

</body>
</html>
```

## Semana 3: Mini sitio (3 páginas conectadas)

Ejercicio insertar imágenes en cada página.

Index.html
```
<!DOCTYPE html>
<html>
<head>
<title>Inicio</title>
</head>

<body>

<h1>Mi sitio</h1>

<img src="inicio.jpg" alt="Imagen de inicio" width="300">

<br><br>

<a href="obra.html">Obra</a><br>
<a href="contacto.html">Contacto</a>

</body>
</html>

```
Codigo modificado:

```
!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: pink;
  /* Define que el fondo de toda la página sea blanco */

  color: white;
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
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->


<!-- Texto que aparece en el centro de la pantalla -->
 
<h1>Aura Encina</h1>
<h3>Artista visual</h3>



<img src="img/IMG_7136.jpeg" alt="Bodegon" width="300">

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->

```
Obra.html
```

<!DOCTYPE html>
<html>
<head>
<title>Obra</title>
</head>

<body>

<h1>Mi obra</h1>

<img src="obra.jpg" alt="Imagen de la obra" width="300">

<p>Descripción de mi trabajo artístico</p>

<a href="index.html">Inicio</a><br>
<a href="contacto.html">Contacto</a>

</body>
</html>
```
Codigo modificado:
```

<!DOCTYPE html>
<html>
<head>
<title>Obra</title>
</head>

<body>

<h1>Mi obra</h1>

<img src="img/IMG_2148_Original_Original.jpeg" alt="Cuando hay que encapsular el dolor" width="300">

<p>Mi trabajo aborda temas como el refugio y la soledad</p>

<a href="index.html">Inicio</a><br>
<a href="contacto.html">Contacto</a>

</body>
</html>
```
contacto.html:
```
<!DOCTYPE html>
<html>
<head>
<title>Contacto</title>
</head>

<body>

<h1>Contacto</h1>

<img src="contacto.jpg" alt="Imagen de contacto" width="300">

<p>email@email.com</p>

<a href="index.html">Inicio</a><br>
<a href="obra.html">Obra</a>

</body>
</html>
```
Codigo modificado:
```
<!DOCTYPE html>
<html>
<head>
<title>Contacto</title>
</head>

<body>

<h1>Contacto</h1>

<img src="img/IMG_5003.jpeg" alt="Espiritu del presente" width="300">

<p>encinaaura@gmail.com</p>

<a href="index.html">Inicio</a><br>
<a href="obra.html">Obra</a>

</body>
</html>
```

















