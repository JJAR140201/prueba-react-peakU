# Prueba Técnica Infodesign

Este repositorio contiene el desarrollo de la prueba técnica de Infodesign.

## Inicio Rápido 🚀

A continuación, encontrarás instrucciones generales sobre cómo ejecutar el proyecto de forma local.

### Requisitos Previos 📋

Para ejecutar el proyecto localmente, asegúrate de tener instalados los siguientes programas:

1. [Git](https://git-scm.com/) para clonar el repositorio.
2. [Visual Studio Code](https://code.visualstudio.com/) o tu editor de texto preferido.
3. [MySQL](https://www.mysql.com/) como motor de base de datos.
4. [Node.js](https://nodejs.org/) como lenguaje de programación necesario para ejecutar la aplicación.

### Instalación 🔧

Siguiendo estos pasos, podrás desplegar el proyecto localmente si cuentas con los programas mencionados:

1. Clona este repositorio en una carpeta de tu elección en tu equipo.
2. Accede a la carpeta raíz del repositorio y abre una terminal de comandos.
3. Ejecuta el comando `npm install`.
4. Luego, crea una base de datos en MySQL llamada "pruebainfodesign" y utiliza el archivo `.sql` proporcionado en el repositorio para importar los datos necesarios.
5. Una vez finalizado el proceso, ejecuta el comando `npm start`.

## Despliegue 📦

El comando `npm start` o `npm dev` desplegará la aplicación localmente. Por defecto, la aplicación se ejecuta en el puerto 4000. Si el puerto está ocupado o deseas utilizar otro, puedes modificar la constante `port` en el archivo "src/index.js".

## Explicación ⚙️

Cuando inicies la aplicación, la consola mostrará "El servidor se encuentra en el puerto 4000" junto con las conexiones a la base de datos.

La aplicación incluye 3 rutas definidas en el archivo "src/routes/routes.js":
1. `/tramos`: Proporciona un JSON con las fechas de inicio y finalización (por ejemplo, { "fechainicial": "2010-01-01", "fechafinal": "2010-01-30" }) para mostrar tramos de consumos, pérdidas y costos.
2. `/cliente`: Proporciona un JSON con las fechas de inicio y finalización (por ejemplo, { "fechainicial": "2010-01-01", "fechafinal": "2010-01-30" }) para mostrar tramos de consumos, pérdidas y costos divididos por tipos de usuarios.
3. `/tramos-cliente`: Proporciona un JSON con las fechas de inicio y finalización (por ejemplo, { "fechainicial": "2010-01-01", "fechafinal": "2010-01-30" }) para mostrar el top 20 de los peores Tramos/Clientes.

## Tecnologías Utilizadas 🛠️

- [Node.js](https://nodejs.org/) como plataforma de desarrollo.
- [Express.js](https://expressjs.com/) para crear la aplicación web.
- [MySQL](https://www.mysql.com/) como sistema de gestión de base de datos.

---
Agrega aquí cualquier otra información relevante o agradecimientos si es necesario.
