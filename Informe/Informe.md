## MATERIA: TECNOLOGIAS WEB CON JAVASCRIPT


### TEMA: SAIILS.JS
### Nombre: Caiza Cargua María José
### Fecha: 20/12/2016
### Nombre Profesor: Ing. Tania Calle - Ing. Adrian Eguez
### Informe: N° 10

## Indice de contenidos

1. Tema
2. Objetivos
3. Marco Teorico
4. Desarrollo de la practica
5. Conclusiones y recomendaciones 

## 1. Tema

 Sails.js Assets-Pipeline-Views-Controller 
   
## 2. Objetivos

* Instalar el framework Sails.js
* Aprender su funcionamiento
* Levantar un servidor http con Sails.js


## 3. Marco Teórico 

### Sails

Sails es, por supuesto, un marco web. Pero dar un paso atrás. Qué significa eso? A veces, cuando nos referimos a la "web", nos referimos a la "front-end". Pensamos en conceptos como los estándares web o HTML 5, CSS. Sails no es "ese tipo" de un framework de desarrollo web.

Por otro lado, a veces, cuando hablamos de "marcos web", nos referimos a la "red de servicios de fondo." Esto evoca conceptos como REST, o HTTP, o WebSockets; y tecnologías como Java o Ruby, o Node.js. Un "Web de back-end" marco ayuda a hacer cosas como construir API, servir a los archivos HTML, y manejar cientos de miles de usuarios simultáneos. Velas es "ese tipo" de framework de desarrollo web.

[Fuente](http://sailsjs.com/whats-that)

![Sails](https://camo.githubusercontent.com/6c76c5e3904170744bad0031ac667f8bc252147f/687474703a2f2f692e696d6775722e636f6d2f52497675392e706e67)

### Assets

Los activos se refieren a archivos estáticos (js, css, imágenes, etc) en el servidor que desea mostrar al mundo exterior. En Sails, estos archivos se colocan en la carpeta Assets/. Cuando levante su aplicación, se puede agregar archivos a la carpeta assets/, o cambiar los assets existentes. Sails procesos y sincroniza esos archivos en una carpeta oculta (.tmp / public /).

[Fuente](http://sailsjs.com/documentation/concepts/assets)

### Views

En Sails, las vistas son plantillas markup que se compilan en el servidor en páginas HTML. En la mayoría de los casos, las vistas se utilizan como respuesta a una solicitud HTTP entrante, por ejemplo para servir la página de inicio.
Alternativamente, una vista puede ser compilada directamente en una cadena HTML para usarla en el código del backend. Por ejemplo, puede usar este enfoque para enviar correos electrónicos HTML o para construir grandes cadenas XML para usar con un API heredada.

[Fuente](http://sailsjs.com/documentation/concepts/views)

### Controllers

Este es el directorio que contiene sus controladores. En Sails, los controladores son archivos javascript que contienen lógica para interactuar con los modelos y renderizar vistas apropiadas para el cliente.
Cuando se llama a sails se genera un API a través de la línea de comandos desde dentro del directorio raíz de su proyecto, Sails generará el archivo api / controllers / CatsController.js junto con un modelo de emparejamiento.

[Fuente](http://sailsjs.com/documentation/anatomy/api/controllers)

 
## 4. Desarrollo de la Práctica 
 
 * Instalamos Sails.js, para eso abrimos una consola de windows y con la ayuda del gestor de paquetes ``` npm install -g sails```
 
  
 ![Instalacion](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/1.PNG)

* En la carpeta que deseamos crear un proyecto ejecutamos el comando ```Sails new NombreProyecto```


 ![Proyecto](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/2.PNG)


* Cuando se crea el proyecto se generaran los siguientes archivos

 ![Carpetas](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/3.png)

* Para levantar el servidor ejecutamos el siguiente comando ``` Sails lift ```

 ![Levantar Sevicio](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/4.PNG)

* Despues pordemos comprobar que el servidor esta levantado, accediendo a localhost:1337 

 ![Resultado](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/5.PNG)

* En los archivos creados podemos encontrar la carpeta assets creamos estos tres archivos:

1. app.js


 ![Archivo app.js](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/8.PNG)
2. estilo.css

 ![Archivo estilos.css](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/7.PNG)

3. index.html

 ![Archivo index.html](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/6.PNG)

* Podemos observar su funcionamiento ingresando a localhost:1337/App/index.html

 ![Resultado](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/9.PNG)



* Podemos editar el archivo pipeline.js el cual se encuentra dentro de la carpeta tasks, este es el archivo que indica que archivos css se utilizaran.

 ![Archivo pipeline.js](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/10.PNG)
 
 * Podemos modificar el archivo cambiando
 
  ![Codigo de archivo](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/11.PNG)


* La carpeta Vistas (views) esta dentro del proyecto, la cual contiene los siguientes archivos.

 ![Archivos](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/12.PNG)


* Estos archivos hacen referencia a las pantallas de error, por ejemplo:

 ![Archivo error](https://github.com/majito11/TecnologiasWeb2016B/blob/10-sails/Informe/Graficos/13.PNG)




## 5. Conclusiones

* Sails es un framework web que nos ayuda a la creacion de aplicaciones.
* El servidor web de sails se encuentra localizado en la carpeta asets.
* Es necesario levantar el servicio cuantas veces sea haga un cambio.











 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
