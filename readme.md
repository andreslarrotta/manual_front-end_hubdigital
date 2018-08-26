Con el fin de facilitar y optimizar los tiempos de desarrollo en los landings.
Hemos creado esta carpeta para establecer un formato y manejar un sistema de carpetas con unas tareas para procesar el código de html, css y javascript.
De igual manera las imágenes dentro de nuestros sitios   

## Pre requisitos
- [NodeJS](https://nodejs.org/)
- Instalar Gulp Globalmente
Esto de debe hacer solo una vez
```
npm install -g gulp
```

Preguntar como instalar estas herramientas con el equipo de Ingenieria

## Para verificar si está instalado todo 
```
node --version
```
```
npm --version
```
```
gulp --version
```

## Instalación
- Lo primero que debe hacer es clonar este repositorio en su equipo para poder realizar las pruebas localmente.
```
git clone //pendiente
```
- Luego se abre la consola, se ubica la carpera donde clonó el repositorio.
### Mac
- Haz clic en el icono "Finder" situado en el Dock, luego selecciona "Aplicaciones > Utilidades"
- Finalmente dale doble clic al icono "Terminal"

### Windows
- Abrir Consola de Comandos con WIN + R en Windows 10
- Escribir cmd

- Se ejecuta el siguiente comando en la consola para descagar las librerías necesarias.
```
npm install
```

## Directorios del proyecto

**assets** - Es el directorio donde se encontrarán las respectivas carpetas que se procesarán para subir los archivos al eloqua

**eloqua** - Es el directorio donde se encontrarán se exportarán los archivos mitificados compatibles para todos los navegadores, de igual manera las imágenes y si es el caso los archivos preprocesados de sass.

**index.html** - Es el archivo que será emplazado por el maquetador para poder usarlo y generar el archivo minificado

## Tarea

### Gulp

En la consola de comandos únicamente tendrá que ejecutar el siguiente comando:

```
gulp
```
Se crea  http://localhost:3000/ Y podrá ver el corte, css y js que va generando de acuerdo con los archivos que usted ubico previamente en la carpeta de assets, la tarea va escuchando todos los cambios que usted va haciendo y refresca automáticamente el navegador.


Para finalizar la tarea debe oprimir 

```
Ctrl + c
```

Todos los archivos se van a generar en la carpeta que eloqua.

## Archivos del Eloqua

**eloqua/css** - Se genera un archivo eloqua.min.css el cual tendrá todos los archivos minificados  y unidos de la carpeta previa en assets/css

**eloqua/js** - Se genera un archivo eloqua.min.js el cual tendrá todos los archivos minificados  y unidos de la carpeta previa en assets/js

**eloqua/img** - Podrá encontrar todas las imágenes .png y .jpg optimizadas para poder subirlas al eloqua.

**eloqua/** - En la carpeta eloqua podrá ver los archivos .html minificados para poder subirlos al eloqua 