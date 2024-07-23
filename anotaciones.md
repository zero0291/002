# Node
Ejecutar javascript del lado del sistema operativo

## NMP (node package manager)
Nos permite gestionar las librerias/paquetes de nuestro proyecto

https://www.npmjs.com/package/sweetalert2

## Vite herrmaienta para desarrollar moderna

## Creando un proyecto de vite

``` sh
npm create vite@latest . # Le indica que cree todos los archivos de la carpeta actual
npm crete vite.latest # Viteme va a preguntar el nombre de la carpeta y dentro va a crear todos los archivos
```

## Levanto el servidor de desarrollo

``` sh
npm run dev # Como si fuera un live server (ya no uso mas el live server)
# http://Localhost:5173
```

## Detener el servidor de desarrollo

Ctrl + C

## Pasos para subir el proyecto a la nube

1. Detengo el servidor de desarrollo
2. Genero los archivos a subir

```sh
npm run build
```
3. Me logueo en netlify y arrastro la carpeta dist.

## Actualizar el proyecto

1. Volver a ejecutar el servidor de desarrollo
2. Corregir proyecto
3. Cierro sv de desarrollo
4. volver a netlify/Deploys
5. arrastrar nuevamente carpeta dist


