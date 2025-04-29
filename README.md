INSTALACIÓN Y EJECUCIÓN

Clonar el repositorio desde GitHub.
Ejecutar el siguiente comando para instalar las dependencias: npm install.
Iniciar el servidor de desarrollo con: npm run dev.
Abrir el navegador y entrar a la dirección que aparece, generalmente http://localhost:5173.



FUNCIONALIDAD DEL PROYECTO

Página de Inicio donde se presenta el portal.
Página de Personajes donde se listan personajes de la saga de Star Wars.
Cada personaje muestra información como:

Nombre.
Altura.
Peso.
Género.
Color de piel.
Color de pelo.
Color de ojos.
Año de nacimiento.

Paginación básica con botones "Anterior" y "Siguiente" para recorrer los personajes.
Estilo visual inspirado en Star Wars: textos amarillos, y tarjetas en tonos oscuros.



TECNOLOGÍAS UTILIZADAS

Vue.js 3.
Vite.
Vue Router.
Fetch API.
CSS (Flexbox y Grid para diseño responsive).



NAVEGACIÓN

Ruta "/" muestra la página de Inicio.
Ruta "/people" muestra la lista de personajes con paginación.



API CONSUMIDA

SWAPI.tech - API pública de Star Wars.
Endpoint utilizado: https://www.swapi.tech/api/people

