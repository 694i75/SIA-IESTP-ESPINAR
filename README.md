# Sistema de Información Académica - IESTP Espinar

Prototipo web de un sistema de información académica para el Instituto de Educación Superior Tecnológico Público de Espinar. Incluye vistas distintas para administración y estudiantes, con una interfaz adaptable a pantallas pequeñas.

## Requisitos

- Un navegador web moderno.
- No requiere Node.js, base de datos ni instalación de dependencias.

## Cómo abrir la página

Abre `index.html` en el navegador. También puedes servir la carpeta con una extensión como Live Server en Visual Studio Code para trabajar localmente.

## Accesos de demostración

| Perfil | Usuario o DNI | Contraseña |
| --- | --- | --- |
| Administrador | `00000000` | `Admin123!` |
| Estudiante | `00000001` | `00000001` |

Estas credenciales son únicamente para la demostración. No uses datos reales ni reutilices estas contraseñas.

## Funcionalidades

### Administración

- Resumen del sistema.
- Registro y gestión de estudiantes.
- Gestión de cursos, semestres y créditos.
- Registro y edición de notas y evaluaciones parciales.
- Registro de asistencia.
- Consulta e impresión de reportes de notas.
- Configuración del periodo académico vigente.

### Estudiantes

- Panel personal y consulta de cursos.
- Consulta de notas y detalle de evaluaciones.
- Consulta e impresión del reporte de notas.
- Cambio de contraseña de la cuenta de demostración.

## Archivos principales

| Archivo | Descripción |
| --- | --- |
| `index.html` | Documento inicial y carga de los recursos de la página. |
| `style.css` | Estilos, diseño adaptable y apariencia de la interfaz. |
| `js.js` | Vistas, navegación, formularios y datos de demostración. |
| `logo-iestp (1).png` | Imagen institucional utilizada en la interfaz. |

## Almacenamiento y limitaciones

La aplicación guarda los datos y la sesión en `localStorage` del navegador. Por ello, la información solo está disponible en el navegador y dispositivo donde se utilizó; no se sincroniza entre usuarios ni equipos. Borrar los datos del sitio en el navegador elimina la información guardada.

Este proyecto es un prototipo de interfaz y no cuenta con servidor, base de datos, control de acceso seguro ni almacenamiento cifrado. Las contraseñas y los datos de demostración se manejan en el navegador, por lo que no debe utilizarse con información académica real ni desplegarse como sistema de producción sin implementar una API y autenticación seguras.
