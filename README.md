# Notas:

```
ejecutar este comando para crear los node_modules
npm install
```

``````````
Directorio en el cual estara el producto final
 "outDir": "dist",  
``````````

``````````
combertir nuestro codigo typescript a javascript
         comando tsc
``````````

``````````
ejecutamos el comando nodemon dist/index
````````````

``````````
instalamos npm install express
           npm install @types/express --save-dev       
En el server.ts creamos al configuracion del servidor
``````````

``````````
npm i copyfiles para que el tsc nos combierta los archivos html
dentro de la carpeta dist

"html": "copyfiles --up 1 src/public/*.html dist"
"build": "tsc && npm run html"
     npm run build
``````````
``````````
En el archivo mysql.ts es donde establecemos las credenciales para conectarnos a la bd

npm install mysql
npm install mysqljs/mysql
npm install @types/mysql --save-dev
tabien creamos una funcion para ejecutar consultas ejecutarQuery()
````````