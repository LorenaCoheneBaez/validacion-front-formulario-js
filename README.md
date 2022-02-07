# Validación de formulario desde el frontend

## Objetivo:

Validar formularios sencillos de agregado y edición de películas, desde el lado del cliente manipulando el dom con JavaScript.

### Requisitos para la validación:

- Todos los campos son obligatorios.
- Los campos calificación y permios deben tener valores entre 0 y 10
- El campo duración debe tener valor entre 60 y 360.
- Los errores deben estar listados para que el usuario los visualice.
- Si no existen errores y se envia el formulario, debe informarse con un alert al usuario.

## Tecnologías usadas

<p align="left">
<!-- javascript -->
<a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" data-bs-toggle="tooltip" title="JavaScript"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javaScript"/> </a>
<!-- express -->
<a href="https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction" alt="Express Js" ><img src= "https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" /></a>
<!-- css -->
<a href="https://www.w3schools.com/css/" target="_blank" data-bs-toggle="tooltip" title="CSS3"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css3"/> </a>
<!-- bootstrap  -->
<a href="https://getbootstrap.com" target="_blank" data-bs-toggle="tooltip" title="Bootstrap"> <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="bootstrap"/> </a>
</p>

### ¿Cómo instalar el proyecto?

#### Desde la terminal:

<h4> Clonar el proyecto:</h4>
<p>- <strong> git clone https://github.com/LorenaCoheneBaez/validacion-front-formulario-js.git </strong> </p>
<p>- Ingresar a la carpeta del proyecto: <strong>cd validacion-front-formulario-js</strong> </p>
<p>- Para instalar las dependencias correr: <strong>npm install</strong> </p>

### Levantar el servidor del proyecto: npm test

### Rutas:

- Home "http://localhost:3001/"
- Formulario agregar película "http://localhost:3001/movies/add"
- Formulario editar película "http://localhost:3001/movies/edit/:id"
