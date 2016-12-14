## MATERIA: TECNOLOGIAS WEB CON JAVASCRIPT


### TEMA: NPM
### Nombre: Caiza Cargua María José
### Fecha: 2016-11-23
### Nombre Profesor: Ing. Tania Calle - Ing. Adrian Eguez
### Informe: N° 7

## Indice de contenidos

1. Tema
2. Objetivos
3. Marco Teorico
4. Desarrollo de la practica
5. Conclusiones y recomendaciones 

## 1. Tema

   El tema de la practica es NPM
   
## 2. Objetivos
 
-	Instalar y utilizar Node JS
-   Crear y publicar paquetes NPM
-    Instalar, desintalar y versionar parquetes NPM


## 3. Marco Teórico 


#### NPM

NPM se incluye automáticamente cuando se instala Node.js. NPM consiste en una línea de comandos de cliente que interactúa con un registro remoto. Permite a los usuarios consumen y distribuyen los módulos de JavaScript que están disponibles en el registro. Paquetes en el registro están en CommonJS formato e incluyen un archivo de metadatos en JSON formato. Más de 280.000 paquetes están disponibles en el registro principal de la NGP Paquetes en la NGP se registran en un primer llegado primer servido base y no distinguen entre los autores, lo que significa que se anule la publicación de un paquete no sólo puede romper los proyectos que dependen de ella, sino también plantear un riesgo para la seguridad. El registro NPM tiene ningún proceso de selección para la presentación, lo que significa que los paquetes encontrados no puede haber baja calidad, inseguro, o malicioso. Sin embargo, los administradores del servidor de la NGP son totalmente capaces de borrar paquetes maliciosos o prohibición de usuarios maliciosos.  NPM expone las estadísticas de uso y el número de paquetes en función de ayudar a los desarrolladores en la selección de las bibliotecas. 

[Fuente](https://en.wikipedia.org/wiki/Npm_(software))

¡[NPM](https://vorba.ch/2012/nodejs-npm.png)

#### NPM

Como un evento asíncrono impulsada JavaScript tiempo de ejecución, el nodo está diseñado para construir aplicaciones de red escalables. En el siguiente ejemplo "hola mundo", muchas conexiones se pueden manejar simultáneamente. Tras cada conexión de la devolución de llamada se dispara, pero si no hay trabajo por hacer Nodo está durmiendo.

[Fuente](https://nodejs.org/en/about/)



## 4. Desarrollo de la Práctica 
 

1. Creamos la carpeta Node y en esta carpeta iniciamos la consola en la cual ingresamos al compilador de node con el comando 
node 

![](https://github.com/majito11/TecnologiasWeb2016B/blob/07-nodeJS/Graficos/ImagenesNPM/Captura1.PNG)

2. Creamos el archivo app.js en la carpeta Node realizamos unas pequeñas funciones y podemos ejecutarlas en la consola de node.

![](https://github.com/majito11/TecnologiasWeb2016B/blob/07-nodeJS/Graficos/ImagenesNPM/Captura2.PNG)

3. Para realizar la publicacion de un paquete nos creamos una cuenta en [NPM](https://www.npmjs.com/) 

![](https://github.com/majito11/TecnologiasWeb2016B/blob/07-nodeJS/Graficos/ImagenesNPM/Captura3.PNG)


4. Para crear un paquete vamos a utilizar el siguiente comando

```npm -init```


5. En el cual nos solicitara varios campos para llenar

![](https://github.com/majito11/TecnologiasWeb2016B/blob/07-nodeJS/Graficos/ImagenesNPM/Captura4.PNG)

6. Para publicar un paquete, tomamos como guia el video de npm [video](https://docs.npmjs.com/getting-started/publishing-npm-packages)



7. Debemos ingresar con el comando 

```npm login```


8. Luego podemos publicar nuestro paquete con el comando

``` npm publish```


9. Para instalar un paquete npm utilizamos el siguiente comando

```npm i "nombre del paquete publicado"```


10. Para desinstalar un paquete npm

```npm uninstall "nombre del paquete"```


## 5. Conclusiones

* La utilizacion de npm mediante NodeJS es mas facil debido a que ya viene por defecto.
* Para poder hacer la creacion de paquetes necesitamos tener una cuenta en npm
* Debemos tener presente que puede haber errores al momento de la publicacion de algun paquete.










 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
