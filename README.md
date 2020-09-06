/*ESTRUCTURA BASE*/
Tarea GULP(folder)
    build(folder)
        cssminify(folder)
            Descripción: contiene archivos minify css
        jsminify(folder)
            Descripción: contiene archivos minify js
    dist(folder)
        css(folder)
            Descripción: contiene archivos css
        index.html
    node_modules(folder)
        Descripción: contiene las dependencies
    src(folder)
        js(folder)
            Descripción: contiene archivos de prueba js 
        scss(folder)
            Description: contiene archivos para el precompilador sass
    .gitignore
    package.json

/*COMANDOS DE INSTALACIÓN*/
-- Instalación de dependencias necesarias
npm install

/*TAREAS*/

scssTask
--Compilar los archivos de sass en estios en cascada para el navegador (CSS)

watchTask
--Observar cambios en los archivos de sass para compilar automáticamente

serveTask
--Sirve archivos automáticamente en navegador

reloadTask
--Actualización de cambios en tiempo real en el navegador

minifycssTask
--Minificación de archivos CSS

minifyjsTask
--Minificación de archivos js