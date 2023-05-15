# Argentina Programa - Proyecto Final: Backend

Este repositorio contiene el código fuente y los archivos necesarios para el proyecto final del programa Argentina Programa. El proyecto consiste en el desarrollo del backend para un portafolio personal utilizando tecnologías como Node.js, Express y MongoDB.

## Descripción

El objetivo de este proyecto es crear el backend para un portafolio personal interactivo que muestre las habilidades, proyectos y experiencia de un individuo. El backend se encarga de gestionar la lógica de negocio, manejar las solicitudes del cliente y almacenar los datos en una base de datos.

El proyecto se ha desarrollado utilizando las siguientes tecnologías:

- **Node.js**: Un entorno de ejecución de JavaScript del lado del servidor que permite la construcción de aplicaciones web escalables y de alto rendimiento.
- **Express**: Un framework web rápido y minimalista para Node.js que proporciona una capa de abstracción para construir API y manejar solicitudes HTTP.
- **MongoDB**: Una base de datos NoSQL orientada a documentos que permite el almacenamiento y recuperación eficiente de datos.

## Características principales

El backend desarrollado en este proyecto cuenta con las siguientes características:

1. **Autenticación y autorización**: Implementa un sistema de autenticación y autorización para proteger ciertas rutas o funcionalidades del portafolio personal.
2. **Gestión de proyectos**: Permite crear, leer, actualizar y eliminar proyectos del portafolio, almacenando la información en la base de datos.
3. **Gestión de habilidades**: Proporciona operaciones para administrar las habilidades y tecnologías del propietario del portafolio, permitiendo agregar, editar o eliminar habilidades.
4. **Gestión de experiencia**: Permite administrar la experiencia laboral o proyectos anteriores del propietario del portafolio, incluyendo operaciones para crear, editar y eliminar registros de experiencia.
5. **Almacenamiento de imágenes**: Permite subir y almacenar imágenes relacionadas con los proyectos o el perfil del propietario del portafolio.

## Instalación

Sigue los pasos a continuación para configurar el proyecto de backend en tu entorno local:

1. Clona este repositorio en tu máquina local utilizando el siguiente comando:

   ```
   git clone https://github.com/vvintra/Portafolio-Backend/
   ```

2. Navega al directorio del proyecto:

   ```
   cd nombre-repositorio
   ```

3. Instala las dependencias del proyecto utilizando el siguiente comando:

   ```
   npm install
   ```

4. Configura las variables de entorno. Crea un archivo `.env` en el directorio raíz del proyecto y define las siguientes variables:

   ```
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/portafolio
   JWT_SECRET=secreto-para-generar-token
   ```

   Asegúrate de proporcionar la URL correcta para la base de datos MongoDB y elige un valor adecuado para la clave secreta de JWT.

5. Inicia el servidor:

   ```
   npm start
   ```

   El servidor estará disponible en `http://localhost:3000`.
