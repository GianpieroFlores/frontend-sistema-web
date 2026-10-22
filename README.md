# Qalikay – Frontend

Aplicación web desarrollada como proyecto universitario, orientada a la gestión de productos, recetas tradicionales y ventas. Cuenta con una interfaz para que los usuarios puedan acceder a las distintas funcionalidades del sistema según su rol.

Este repositorio contiene el frontend del proyecto, desarrollado con Angular.

## Funcionalidades

- Inicio de sesión y acceso según roles de usuario.
- Registro, consulta y edición de productos.
- Gestión de recetas y comentarios.
- Registro de ventas y opciones de pago.
- Administración de usuarios y roles.
- Visualización de reportes.

## Tecnologías utilizadas

- **Angular 18:** desarrollo del frontend.
- **TypeScript:** lógica de los componentes y servicios.
- **HTML y CSS:** estructura y estilos de las interfaces.
- **Angular Material:** componentes de interfaz.
- **Chart.js:** visualización de gráficos.

## Instalación y ejecución

Para ejecutar el proyecto localmente, es necesario tener instalado Node.js y npm.

1. Clonar el repositorio:

   `git clone https://github.com/GianpieroFlores/frontend-sistema-web.git`

2. Ingresar a la carpeta:

   `cd frontend-sistema-web`

3. Instalar las dependencias:

   `npm install`

4. Iniciar el servidor de desarrollo:

   `npm start`

5. Abrir en el navegador:

   `http://localhost:4200`

## Backend

El frontend se conecta a una API REST desarrollada con Java y Spring Boot. La dirección de la API se configura en `src/app/environments/environment.ts`.

El código del backend se encuentra en el siguiente repositorio:

[Qalikay – Backend](https://github.com/GianpieroFlores/backend-sistema-web)
