# Ejemplo de Chat en Ionic

_Este es un proyecto de ejemplo de una aplicación de chat básico creada con Ionic y AngularJS. Este ejemplo utiliza gulp para tareas de construcción y organiza el código en módulos de controladores y servicios para mantener una estructura limpia._

## Estructura del Proyecto

- www/: Carpeta principal donde se encuentran los archivos HTML, CSS, JavaScript, y otros activos de la aplicación.
- scss/: Contiene los archivos SCSS personalizados.
- lib/: Contiene los archivos de Ionic y AngularJS necesarios para ejecutar el proyecto.
- hooks/: Archivos de configuración de Ionic.

## Dependencias

Este proyecto utiliza las siguientes herramientas y dependencias:

- Ionic Framework: Proporciona la interfaz de usuario y la estructura básica del proyecto.
- AngularJS: Framework de JavaScript utilizado para la lógica de la aplicación.
- Gulp: Herramienta de tareas para compilar SCSS y optimizar otros activos.

## Instalación de Dependencias

**Para instalar las dependencias del proyecto, asegúrate de tener Node.js y npm instalados. Luego, en la raíz del proyecto, ejecuta:**

```bash
npm install

```

## Configuración del Proyecto

- Configuración de Ionic: Edita el archivo ionic.config.json para establecer el tipo de proyecto como custom:

```bash
{
  "name": "ejemplo1",
  "type": "custom"
}
```

- Compilación de SCSS y otros archivos: Usa Gulp para compilar los archivos SCSS y generar el CSS necesario en www/css/. Ejecuta:

```bash
gulp
```

## Ejecución del Proyecto

Para correr el proyecto en un servidor de desarrollo:

- Instala un servidor estático si no lo tienes:

```bash
npm install -g http-server
```

- Inicia el servidor en la carpeta www:

```bash
http-server www
```

- Accede a la aplicación en el navegador:

```bash
http://localhost:8080
```

## Funcionalidades

Este proyecto de chat básico incluye:

- Vista de chats: Lista de conversaciones activas.
- Detalle del chat: Vista de mensajes individuales.
- Pestañas de navegación: Acceso rápido a diferentes secciones (chats, cuenta, etc.).

## Contact

If you have any questions or suggestions, feel free to get in touch at **cvarelagarcia@gmail.com.**

## Author

- [@VarelaCristianFacundo](https://github.com/VarelaCristianFacundo)
