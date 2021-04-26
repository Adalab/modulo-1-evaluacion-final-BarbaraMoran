# Mi web starter kit

# Evaluación final Módulo 1 de Bárbara Morán.

¡Hola! Te presento mi prueba técnica de finalización del Módulo 1 de Adalab.
Se trata de un proyecto de página web responsive realizada en SCSS y HTML5 en base a un diseño dado. Si tienes permiso del administrador puedes consultar el modelo aquí: https://app.zeplin.io/project/5c8ff9170ffc6f2525b2790c.

Para realizar el proyecto he utilizado el Adalaber Starter Kit, creado en **node y gulp**. Se trata de una **plantilla de proyecto con funcionalidades preinstaladas y preconfiguradas** que he adaptado a las necesidades de este proyecto en concreto .

Este Kit incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local y muchas cosas más. El Kit nos ayuda a trabajar más cómodamente, nos automatiza tareas.

**NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/) para trabajar con este proyecto:

### Pasos a seguir para arrancar el proyecto.

1. Descarga este repositorio.
1. **Abre una terminal** en la carpeta raíz del repositorio.
1. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```

### Pasos para arrancar el proyecto:

Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez que nos pongamos a programar.** Para ello ejecuta el comando:

```bash
npm start
```

Este comando:

- **Abre una ventana de Chrome y muestra la página web**, al igual que hace el plugin de VS Code Live Server (Go live).
- También **observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que se modifique un fichero **refresca tu página en Chrome**.
- También **procesa los ficheros** HTML, SASS / CSS y JS y los **genera y guarda en la carpeta `public/`**. Por ejemplo:
  - Convierte los ficheros SASS en CSS.
  - Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

Después de ejecutar `npm start` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta `src/` y programar cómodamente.

### Pasos para publicar el proyecto en GitHub Pages:

Para generar tu página para producción ejecuta el comando:

```bash
npm run docs
```

Y a continuación:

1. Sube a tu repo la carpeta `docs/` que se te acaba de generar.
1. Entra en la pestaña `settings` de tu repo.
1. Y en el apartado de GitHub Pages activa la opción **master branch /docs folder**.
1. Y ya estaría!!!

## Estructura de carpetas

Mi proyecto de web está estructurado de la siguiente manera:

```
src
 ├─ api // los ficheros de esta carpeta se copian en public/api/
 |  └─ data.json
 ├─ images -> Incluye todas las imágenes del proyecto.
 |
 ├─ scss -- Fichero principal (styles.scss) donde se unen todas las hojas de estilo parciales que se encuentran en     |  |       las  carpetas de scss, además de los links externos a Google Fonts.
 |  |
 |  ├─ core - Incluye hoja de reset y variables.
 |  ├─ layout - Incluye hojas de estilos del <footer>, <header> y lo específico del <body>.
 |  └─ pages - Incluye las hojas de estilos que se corresponden al <main>, llamadas _section1 y _section2
 |
 └─ html -- Fichero principal (index.html) donde se unen todos los partials.
    |
    └─ partials- Ficheros .html que corresponden a diferentes las partes del index.html. Contamos con partials para el <header>, <main> (con sus subpartials bautizados como section1 y section2) y el <footer>.
```

Si tienes cualquier duda o cualquier sugerencia para mejorar el proyecto puedes ponerte en contacto conmigo a tráves de las issues o mandarme un email a barbaramoranrr@gmail.com. ¡Muchas gracias por tu atención!
