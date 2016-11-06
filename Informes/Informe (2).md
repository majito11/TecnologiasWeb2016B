# CSS

### Materia: TECNOLOGIAS WEB CON JAVASCRIPT
### TEMA: CSS
### FECHA: 02/11/2016
### ESTUDIANTE: María José Caiza Cargua
### PROFESOR: Ing. Tania Calle - Ing. Adrian Eguez
### NUMERO DE NFORME: N°2 

## Indice de contenidos

1. Tema
2. Objetivos
3. Marco Teorico
4. Desarrollo de la practica
5. Conclusiones y recomendaciones

## 1. Tema

# css

## 2. Objetivos

-	Aprender acerca del uso de estilos CSS
-   Aprender los conceptos de JavaScript

## 3. Marco Teórico 

## CSS

CSS significa 
### C ascading 
### S tyle 
### S heets

CSS es un lenguaje de hojas de estilos creado para controlar el aspecto o presentación de los documentos electrónicos definidos con HTML y XHTML. CSS es la mejor forma de separar los contenidos y su presentación y es imprescindible para crear páginas web complejas.

Separar la definición de los contenidos y la definición de su aspecto presenta numerosas ventajas, ya que obliga a crear documentos HTML/XHTML bien definidos y con significado completo (también llamados "documentos semánticos"). Además, mejora la accesibilidad del documento, reduce la complejidad de su mantenimiento y permite visualizar el mismo documento en infinidad de dispositivos diferentes.
HTML fue nunca la intención de contener etiquetas para dar formato a una página web!

HTML fue creado para describir el contenido de una página web, como:

<H1>Este es un encabezado</H1>

<P> Este es un párrafo.</P>


[Fuente](http://www.w3schools.com/css/css_intro.asp)

![CSS + HTML](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/CSS1.png)


## JAVASCRIPT

![JavaScript](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/JS.jpg)

JavaScript (abreviado comúnmente JS) es un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos, basado en prototipos, imperativo, débilmente tipado y dinámico.

Se utiliza principalmente en su forma del lado del cliente (client-side), implementado como parte de un navegador web permitiendo mejoras en la interfaz de usuario y páginas web dinámicas4 aunque existe una forma de JavaScript del lado del servidor(Server-side JavaScrip o SSJS). Su uso en aplicaciones externas a la web, por ejemplo en documentos PDF, aplicaciones de escritorio (mayoritariamente widgets) es también significativo.

[Fuente](https://es.wikipedia.org/wiki/JavaScript)


## ECMAScript

![ECMAScript](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/ES.PNG)

ECMAScript define un lenguaje de tipos dinámicos ligeramente inspirado en Java y otros lenguajes del estilo de C. Soporta algunas características de la programación orientada a objetos mediante objetos basados en prototipos y pseudoclases.

La mayoría de navegadores de Internet incluyen una implementación del estándar ECMAScript, al igual que un acceso al Document Object Model para manipular páginas web. JavaScript está implementado en la mayoría de navegadores, Internet Explorer de Microsoft usa JScript. El navegador Opera tiene su propio intérprete de ECMAScript con extensiones para soportar algunas características de JavaScript y JScript. Cada navegador tiene extensiones propias al estándar ECMAScript, pero cualquier código que se adecúe al estándar debería funcionar en todos ellos.

[Fuente](https://es.wikipedia.org/wiki/ECMAScript)


## JQuery
 
JQuery es una biblioteca de JavaScript, creada inicialmente por John Resig, que permite simplificar la manera de interactuar con los documentos HTML, manipular el árbol DOM, manejar eventos, desarrollar animaciones y agregar interacción con la técnica AJAX a páginas web. Fue presentada el 14 de enero de 2006 en el BarCamp NYC. jQuery es la biblioteca de JavaScript más utilizada.

[Fuente](https://es.wikipedia.org/wiki/JQuery)


## 4. Desarrollo de la Práctica 

1. Para el desarrollo de la practica utilizaremos la alicacion JSBin. (Para empezar utilizaremos HTML)

![JSBIN](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/JSBIN1.PNG)

Obtenemos los CDN de CSS y JavaScript

[CDNs](https://www.bootstrapcdn.com/)

![CDN](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/CDN.PNG)

2. Copiamos fragmentos de codigo de la pagina de bootstrap en la cual realizamos dos clases "aqua" y "pink" 

![JSBIN](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/JSBIN2.PNG)

El resultado de correr el codigo es el siguiente:

![JSBIN](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/JSBIN3.PNG)

Por ultimo copiamos el siguiente codigo: 

* Codigo apartado `NavBar`

```

<nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Brand</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">Separated link</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">One more separated link</a></li>
          </ul>
        </li>
      </ul>
      <form class="navbar-form navbar-left">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Search">
        </div>
        <button type="submit" class="btn btn-default">Submit</button>
      </form>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">Separated link</a></li>
          </ul>
        </li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
  
```

Y obtenemos lo siguiente:

![JSBIN](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/JSBIN4.PNG)

Obtenemos el siguiente link de página

[Link JSBIN](http://jsbin.com/qanevebipi/1/edit?html,console,output)


## Introduccion a JavaScript

En la interfaz creada, le asignamos una accion al botón con el siguiente código

```
<button class="aqua" ondblclick="alert('ADVERTENCIA')">Botón</button>

```

Y al dar click obtenemos:

![JSBIN](https://github.com/majito11/TecnologiasWeb2016B/blob/master/Graficos/JSBIN5.PNG)


## 5. Conclusiones y recomendaciones

* CSS es el lenguaje que describe el estilo de un documento HTML.
* Mediante la creacion de clases se puede cambiar color, tipo de leta, etc. de varios componentes de un documento HTML.
* Es recomendable utilizar clases o ID para la asignacion de colores a los diferentes componentes.







 
 





