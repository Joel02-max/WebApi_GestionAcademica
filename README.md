# 📚 Web API Gestión Académica
Proyecto de implementación de una API REST utilizando ASP.NET Web API como backend y HTML, CSS y JavaScript como frontend,
para la gestión académica de asignaciones, carreras, cursos y estudiantes.

## 🚀 Tecnologías Utilizadas

- **Backend**: ASP.NET Web API (.NET Framework)
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **Servidor de desarrollo**: Node.js (para levantar frontend con servidor sencillo)
- **Herramientas**:
  - Visual Studio (para el desarrollo del Backend)
  - Visual Studio Code (para el desarrollo del Frontend)
- **Dependencias**:
  - Express (Node.js)

## 🏛️ Estructura del Proyecto

El proyecto está dividido en dos entornos de desarrollo:

- **Backend** (WebApi_GestionAcademica) trabajado en **Visual Studio**.
- **Frontend** (frontend/) trabajado en **Visual Studio Code**.

- ## ⚙️ Instalación y ejecución

  * Clonar el repositorio
  * Backend (API), Abrir la solución WebApi_GestionAcademica.sln en Visual Studio.
  * Ejecutamos el BackEnd
  * Backend (API)
  * Abrir la solución WebApi_GestionAcademica.sln en Visual Studio.
    
 
    https://github.com/Joel02-max/WebApi_GestionAcademica/blob/master/ConexionBD.JPG

´Ejecutamos el backend y nos dara algo similar a esto: https://localhost:5001/api y nos,
dirigira a la web a nuestro apartado web donde se reflejaran las peticiones´



     ---

  * Abrimos la carpeta del frontend Visual Studio Code.
  * Instalar dependencias, en caso de requerirlo
    - npm install
  * Corremos el servidor 'node server.js'
  * El frontend estará disponible en..: http://localhost:3000

  ⚠️ Consideraciones
No se utiliza motor de vistas como Razor porque el proyecto separa claramente API y Frontend.

Es importante levantar ambos servidores (API y Frontend) para la correcta interacción de toda la solución.

Tener cuidado con el manejo de CORS si el puerto del backend y frontend son diferentes.


