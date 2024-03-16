# Pruebas con Cypress en Cypress E2E Framework

Este repositorio es una extensión del curso [Introducción a Cypress](https://testautomationu.applitools.com/cypress-getting-started/) en Test Automation University.

## Autor
El autor original del curso es Filip. Es DevRel en [Replay.io](https://replay.io) y embajador de [Cypress](https://cypress.io/ambassadors/).

## Contenido del Repositorio
Este repositorio contiene todos los materiales del curso. La mayoría de los capítulos comienzan con el archivo `[nombre_del_capitulo]_start.js` y terminan con el archivo `[nombre_del_capitulo]_end.js`.

## Aplicación Clon de Trello
La aplicación de Trello, clonada para este curso, está incluida como un submódulo en el repositorio. Esta aplicación te permite crear tableros, listas y tarjetas. Puedes arrastrar y soltar tarjetas entre listas e incluso subir imágenes a los detalles de la tarjeta. También cuenta con un registro y inicio de sesión simples que te permiten crear tableros privados.

### Instalación
La instalación es muy sencilla:
1. `npm install`
2. `npm start`
3. Abre tu navegador en `http://localhost:3000`

### Base de Datos
La aplicación utiliza un archivo JSON como base de datos, que puedes encontrar en `trelloapp/backend/data/database.json`. Los archivos subidos están en la carpeta `trelloapp/backend/data/uploaded`.

### Utilidades de la Aplicación
Al presionar la tecla `F2` en la aplicación, aparecerá un pequeño conjunto de herramientas que te permitirán restablecer tu aplicación a un estado deseado. Puedes eliminar tableros, listas, tarjetas, usuarios o todo. Esto es útil cuando juegas con la aplicación manualmente.

## Documentación de la API
[La documentación completa de la API se encuentra aquí.](#api-documentation)

## Mi Contribución
Mi trabajo se encuentra en la carpeta `e2e`. Aquí he desarrollado pruebas de extremo a extremo utilizando Cypress para validar diversas funcionalidades de la aplicación clon de Trello.

## Contacto
Si tienes alguna pregunta sobre mi contribución a este proyecto, no dudes en contactarme.

¡Gracias por tu interés en las pruebas automatizadas con Cypress en Cypress E2E Framework!
