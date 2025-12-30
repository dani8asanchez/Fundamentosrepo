# Fundamentosrepo
# Documento Detallado de Diseño (DDD)

## 1. Descripción del Trabajo
Este proyecto consiste en el desarrollo de un portafolio profesional estático para la asignatura de **Fundamentos de la Ingeniería Informática**. La web está diseñada para centralizar la trayectoria académica del autor, utilizando una arquitectura de archivos organizada y profesional.

### Estructura Técnica:
- **Tecnologías:** HTML5 para el marcado, CSS3 para el diseño visual y Git/GitHub para el control de versiones y despliegue (GitHub Pages).
- **Arquitectura de Información:** - El proyecto reside en la carpeta `/docs` para facilitar el despliegue.
  - El `index.html` actúa como eje central, conectando con las secciones de **Estudios** (`degree.html`), **Ciberseguridad** (`topic.html`), **Red de Contactos** (`net.html`) y **Contacto** (`contacts.html`).
- **Diseño UI:** Se ha implementado un diseño limpio con una paleta de colores profesional (#2c3e50 y #1abc9c) y botones interactivos para accesos directos.

## 2. Problemas durante el Desarrollo
A lo largo de la creación de la web, se identificaron y resolvieron los siguientes retos técnicos:

* **Gestión de Rutas Relativas:** Uno de los mayores desafíos fue el manejo de enlaces entre el archivo raíz y los archivos dentro de la carpeta `/public`. Se solucionó mediante el uso correcto de `../` para navegar entre niveles de carpetas.
* **Despliegue en GitHub Pages:** Hubo una dificultad inicial para visualizar la web online. El problema se resolvió configurando GitHub Pages para que leyera la rama `master` específicamente desde la carpeta `/docs`.
* **Consistencia Visual:** Lograr que los enlaces de la universidad y de los compañeros se vieran iguales. Se solucionó creando una clase CSS común (`.btn-link`) para estandarizar todos los botones de la red.
* **Gestión de Imágenes:** Asegurar que la foto de perfil se visualizara correctamente tras el despliegue, respetando las mayúsculas/minúsculas en el nombre del archivo y su ubicación en `/img`.

## 3. Conclusiones
La realización de este proyecto ha permitido asentar las bases del flujo de trabajo de un ingeniero informático:
1.  **Orden y Estructura:** Se ha aprendido que la organización de carpetas es vital para el mantenimiento del software.
2.  **Control de Versiones:** El uso de Git ha sido fundamental para gestionar los cambios de forma segura y profesional.
3.  **Adaptabilidad:** La capacidad de resolver errores de despliegue y rutas demuestra una competencia técnica necesaria en el desarrollo web.
Este portafolio no solo cumple con un requisito académico, sino que sirve como base escalable para futuros proyectos y marca el inicio de mi perfil profesional en la red.
