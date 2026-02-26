# Documentación del Proyecto: Mi Perfil Web Personal

## Nombre del Proyecto

Mi Perfil Web Personal desarrollado con Laravel.

## Descripción

El presente proyecto consiste en el desarrollo de una aplicación web utilizando el framework Laravel. 
Su objetivo es presentar información personal organizada en diferentes secciones: Perfil, Intereses, Habilidades y Metas.

Cada sección se implementa mediante vistas Blade independientes y se accede a ellas a través de rutas definidas en el archivo web.php. 
El proyecto incluye navegación entre páginas mediante un menú funcional y un diseño visual desarrollado con CSS propio, sin el uso de frameworks externos como Bootstrap.

Este desarrollo permite aplicar conocimientos fundamentales sobre:
- Definición de rutas en Laravel
- Creación de vistas con Blade
- Organización básica de un proyecto MVC
- Enlace de archivos CSS externos
- Uso de control de versiones con Git y GitHub

## Requisitos del Sistema

Para ejecutar el proyecto correctamente se requiere:

- PHP versión 8.0 o superior
- Composer instalado
- Laravel instalado
- Servidor local (XAMPP, Laragon o similar)
- Navegador web actualizado
- Sistema operativo Windows, Linux o MacOS

## Instrucciones de Instalación

Para instalar el proyecto en un entorno local, se deben seguir los siguientes pasos:

1. Clonar el repositorio desde GitHub:
   git clone https://github.com/Nicolas1609-1/mi-perfil.git

2. Ingresar al directorio del proyecto:
   cd mi-perfil

3. Instalar las dependencias necesarias:
   composer install

4. Generar la clave de la aplicación:
   php artisan key:generate

## Cómo Ejecutar el Proyecto

Para ejecutar la aplicación, se debe iniciar el servidor de desarrollo de Laravel con el siguiente comando:

php artisan serve

Posteriormente, abrir el navegador e ingresar a la siguiente dirección:

http://127.0.0.1:8000/perfil

Desde esa página se podrá navegar a las demás secciones:
- /intereses
- /habilidades
- /metas

## Autor y Fecha

Autor: Nicolás Javier Abello Suárez  
Programa: Ingeniería de Sistemas  
Año: 2026