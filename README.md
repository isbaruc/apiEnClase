# apiEnClase

1.  Crear el repositorio -> https://github.com/isbaruc/apiEnClase
2.  Crear el archivo api.js -> https://github.com/isbaruc/apiEnClase/blob/main/api.js
3.  Instalar las dependencias
    [] nodemon -> npm install nodemon
    [] express -> npm install express
    [] moment -> npm install moment

    Resultado:
    /package.json ->

         "dependencies": {
         "express": "^4.18.2",
         "moment": "^2.29.4",
         "nodemon": "^2.0.22"
         }

4.  Crear usuarios.json
5.  Agregar `"type": "module"` al package.json
6.  Importar usuarios.json en api.js
    6.1. Crear una función con newPromise, que:
    [] Contenga un setTimeout que demore 4000 milisegundos en ejecutarse
    [] Retorne todos los usuarios al cumplirse
    [] Imprima "Error al buscar usuarios" si hay un reject
7.  Invocar la función
    7.1. Hacer uso de `.then`
    7.2. Hacer `console.log` de la respuesta
    7.3. Hacer `.catch`para `console.log`del error

> 💡 Como importar -> `import usuarios from './usuarios.json' assert { type: "json" };`
