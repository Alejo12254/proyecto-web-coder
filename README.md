# Portfolio profesional

Portfolio web personal desarrollado como proyecto de formación en desarrollo web.

## Descripción

Este proyecto presenta información sobre mí, mis habilidades, proyectos y formas de contacto. El sitio está compuesto por cinco páginas y cuenta con navegación entre secciones, diseño responsive y componentes de Bootstrap.

Los estilos propios del proyecto están desarrollados utilizando **SCSS/Sass**, organizados mediante parciales, variables, mixins y una estructura modular.

También incluye una propuesta conceptual de una plataforma académica llamada **CampusHub**.

## Tecnologías utilizadas

- HTML5
- SCSS / Sass
- CSS
- Bootstrap
- JavaScript
- npm
- Git
- GitHub

## Páginas

- **Inicio:** presentación principal.
- **Sobre mí:** información personal y formación.
- **Proyectos:** proyectos realizados y propuestas conceptuales.
- **Habilidades:** tecnologías y conocimientos.
- **Contacto:** medios para contactarme.

## Estructura del proyecto

```text
proyecto-web-coder/
├── css/
│   └── styles.css
├── img/
├── pages/
│   ├── sobre-mi.html
│   ├── proyectos.html
│   ├── habilidades.html
│   └── contacto.html
├── scss/
│   ├── main.scss
│   ├── utilities/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _tipografia.scss
│   │   └── _base.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _footer.scss
│   │   └── _nav.scss
│   └── components/
│       ├── _buttons.scss
│       └── _cards.scss
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

## SCSS

El archivo `main.scss` funciona como punto de entrada y utiliza `@use` para importar los distintos módulos de estilos.

Los estilos se organizan en:

- **Utilities:** variables y mixins reutilizables.
- **Base:** estilos generales y tipografía.
- **Layout:** estructura principal, navegación y footer.
- **Components:** botones, tarjetas y otros elementos reutilizables.

El archivo `css/styles.css` es generado a partir de `scss/main.scss`.

### Compilación de SCSS

Para compilar los estilos se utiliza Sass mediante npm:

```bash
npm run sass
```

Este comando genera el archivo:

```text
css/styles.css
```

## Sitio web

[Ver portfolio online](https://alejo12254.github.io/proyecto-web-coder/)

## Autor

Alejo Santiago Martin