#BACKEND JS - Servidor

###Servidor con Node JS

**Pasos a seguir:**
* npm install
* npm run start

**Lista de Endpoints:**

* GET http://localhost:3900/api/test-de-controlador -- Ruta de prueba de respuesta
* POST http://localhost:3900/api/save -- Crear un artículo
* * Parámetros: *title* - *content*
* POST http://localhost:3900/api/upload-image/:id -- Id del artículo
* * Parámetros: *files*
* GET http://localhost:3900/api/get-image/:nameImage.ext -- Nombre de la imagen con extensión
* GET http://localhost:3900/api/search/:search -- Cadena que busca en title o content
 
*Happy Coding!!!*