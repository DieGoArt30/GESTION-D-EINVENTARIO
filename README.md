# GESTION-DE-INVENTARIO

# Caso de Estudio Genérico: Creación de aplicación web con persistencia y autenticación.
## Selecciona alguno de los siguientes proyectos e implmente las tareas a realizar para demostrar tus conocmientos de las diferentes tecnologías que debe dominar un desarrollador python con Django:

## Opción de Proyecto 1: Sistema de Gestión de Inventario
## Resumen:
### Implementar un sistema de gestión de inventarios para pequeñas y medianas empresas que permita el seguimiento de productos, proveedores y pedidos. Los usuarios podrán gestionar el inventario, crear pedidos de compra y venta, y generar informes de stock.

## Requisitos Técnicos:
- Lenguaje de progrmación: Python
- Frameworks: Django y Django Rest Framework
- Bases de datos: SQLite
- Seguridad: Django Auth
- Control de versiones: Git

# Tareas a Realizar:

## Creación del Proyecto:
- Generar un nuevo proyecto Django con una estructura clara y adecuada para una aplicación de mediana escala.
- Configuración adecuada de las settings de Django, incluyendo la base de datos, zona horaria, y archivos estáticos.

## Aplicación y Modelos:
- Crear al menos una aplicación Django que represente la lógica del negocio.
- Definir modelos Django con relaciones apropiadas (ForeignKey, ManyToMany, etc.) y validaciones de campos.

## Administración de Django:
- Personalizar el panel de administración de Django para gestionar los modelos creados, incluyendo listas personalizadas, filtros, y búsquedas.

## Django Rest Framework:
- Implementar una API REST utilizando Django Rest Framework que permita operaciones CRUD en los modelos definidos.
- Aplicar autenticación y permisos para restringir el acceso a la API según los roles de usuario.

## Serialización:
- Crear serializers para transformar los modelos Django en JSON y viceversa, utilizando tanto serializers simples como ModelSerializer.

## Vistas y URLs:
- Implementar vistas utilizando tanto la API funcional como las clases basadas en vistas (CBVs) de Django y Django Rest Framework.
Configurar correctamente las URLs para acceder a las vistas y a la API.

## Templates:
- Desarrollar templates Django para la renderización de HTML en el frontend, utilizando la sintaxis de templates de Django para mostrar datos dinámicos.

## Documentación:
- Incluir un archivo README.md en el proyecto que documente cómo instalar, configurar y ejecutar el proyecto, así como una descripción general de la estructura del proyecto y la API.

## Criterios de Aceptación
- Funcionalidad Completa: La aplicación debe cumplir con todas las funcionalidades especificadas en los requisitos técnicos.

- Calidad del Código: El código debe ser claro, conciso y seguir las buenas prácticas de programación de Python y Django.

- Uso de Django Rest Framework: Implementación correcta de APIs REST utilizando Django Rest Framework, incluyendo autenticación y permisos.

- Interacción con la Base de Datos: Los modelos deben estar correctamente definidos y relacionados, con migraciones aplicadas sin errores.

- Integración y Uso del Panel de Administración: Los modelos deben ser accesibles y gestionables a través del panel de administración de Django.

- Frontend Funcional: Uso efectivo de Django Templates para crear interfaces de usuario dinámicas y responsivas.

- Documentación: El proyecto debe incluir un archivo README con instrucciones de instalación, configuración y uso, además de comentarios en el código cuando sea necesario.
