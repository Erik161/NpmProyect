<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Npm-logo.svg/1280px-Npm-logo.svg.png" width="400"></p>


### [NPM](https://www.npmjs.com/)
```
¿Qué es NPM (node package manager)? 
Es un gestor de paquetes el mas popular que tiene javascript donde encontraras una gran cantidad de recursos
que podras inplementar en tus proyectos tambien vas a poder crear tus propios paquetes y compartirlos 
con toda la comunidad.

El cual se encarga de administrar todos estos paquetes tiene un sitio robusto donde tu vas a encontrar toda
esta información y tambien como desarrollador vas a poder crear estos paquetes aqui vas a poderlos publicar 
tener una serie de recursos para la comunidad puedan implementar con tus proyectos.

Encontraras un gran listado de recursos donde tu como desarrollador podras implementar en tus proyectos
desde librerias que son Open Source, hasta proyectos que nos van a dar vida a nuestras aplicaciones.

```

### INSTALACIÓN
```
Descarga Node.js ya te incluye una versión de NPM
```

## [NODE.JS](https://nodejs.org/es/)


<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="400"></p>

```
Luego de la instalación debemos ingresar el siguiente comando para comprobar si existe una versión 
mas reciente de npm y si existe la va instalar en nuestro sistema nos va a garantizar que tengamos
la ultima versión.
```
> $ npm install -g npm@latest


## INICIAR NUESTRO PROYECTO
```
Ingresamos el siguiente comando:
```
> $ npm init

```
Nos permite crear el archivo package.json con el cual vamos a tener una configuración establecida una 
descripción del proyecto y ciertos valores que necesita.
```
>package name: (jsnpm)

>version: (1.0.0)

>description:Construir un paquete para node.

>entry point:(index.js) src/index.js

>test command:

>git repository:

>keywords: javascript,node, package

>author: Erik Hernandez <erikexamplehotmail.com>

>license: MIT

## INICIAR PROYECTO DE FORMA RAPIDA

```
No modificamos el Json hasta mas adelante, realiza un Json estatico,
ingresamos el siguiente comando en consola:
```
> $ npm init -y

## SIGUIENTE FORMA DE DECLARAR DE FORMA ESTATICA TU PROYECTO

```
Al ingresar estos comandos va anadir en la configuracion de npm este valor, automaticamente establece 
estos valores a cada proyecto que tu inicialices
```
>npm set init.author.email "erikexample@hotmail.com"

>npm set init.author.name "Erik Hernandez"

>npm set init.license "MIT"
