# Club deportivo

## Descripción del Proyecto

Proyecto donde se valida conocimientos de desarrollo de sistemas CRUD y persistencia de datos en archivos JSON, con creación de rutas y endpoints en un servidor, manejo de solicitudes y respuestas HTTP, así como la implementación de operaciones de Crear, Leer, Actualizar y Eliminar.

Contexto: El Club Deportivo Discipline Spa está haciendo negocios con una empresa de software para
la construcción de su aplicación para control interno que se conecte con la misma base de
datos de su sitio web. Su requerimiento principal es poder registrar, ver, editar y eliminar los
deportes que ofrecen en sus sucursales.
Deberás crear un sistema tipo CRUD que persista la información en un archivo JSON
correspondiente a los deportes que ofrece este club deportivo. 

## Sobre el poryecto 🚀

### ✨ Requerimientos ✨

1.Crear una ruta que reciba el nombre y precio de un nuevo deporte, lo persista en un archivo JSON. Validar en el backend que se reciben los parámetros necesarios o requeridos y en el tipo adecuado, debe validarse que no se repitan los nombres de los deportes. Manejar esta ruta con queryStrings.
2. Crear una ruta que al consultarse devuelva en formato JSON todos los deportes registrados.
3. Crear una ruta que edite el precio de un deporte registrado, utilizando los parámetros de la consulta y persista este cambio. Recuerde que para modificar se debe consultar, por tanto, hay que validar 2 cosas primero que se reciba el parámetro y después que exista el deporte coincidente con el parámetro. Manejar esta ruta con queryStrings.
4. Crear una ruta que elimine un deporte solicitado desde el cliente y persista este cambio. En el Backend Validar que se recibe el parámetro requerido, también validar después si existe el deporte solicitado y solo si existe se podrá eliminar. Manejar esta ruta utilizando parámetros no queryStrings, ojo, que esto requiere un pequeño cambio en el Front.
Nota: Agregar control de ruta No Existente, se deben manejar control de errores con bloques try/catch, y usar variedad de errores y respuestas del servidor según sean necesarias.

### Prerrequisitos 📋

Lista de software y herramientas, incluyendo versiones, que necesitas para instalar y ejecutar este proyecto:

 "dependencies": 
 - "axios": "^1.6.8",
 - "express": "^4.19.2"
"devDependencies": 
-  "nodemon": "^3.1.0"
  

### Instalación 🔧

 Instalo en terminal:
- npm init --yes
- npm install express
- npm i nodemon --D
- npm i axios

## Renders y Pruebas ⚙️

Levantando servidor con:
- nodemon +nombrearchivo
- node +nombrearchivo

## Despliegue 📦

A través de localhost en navegador o con extensión Visual Code ThunderClient para corroborar urls.

## Construido Con 🛠️

Explica qué tecnologías usaste para construir este proyecto. Aquí algunos ejemplos:

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - El lenguaje utilizado
- [Express](https://expressjs.com/en/5x/api.html)- Node paquete Express
- [Nodemon](https://www.npmjs.com/package/nodemon)- Node paquete Nodemon
- [Axios]([https://www.npmjs.com/package/axios])- Node paquete Axios
  

## Autor ⚡ 

- **Andrea Rosero** ⚡  - [Andrea Rosero](https://github.com/andreaendigital)

