# Aura Digital Estudio — Proyecto Final Desarrollo Web

Sitio institucional de **Aura Digital Estudio**, estudio digital boutique de desarrollo web y apps.

🔗 **Sitio desplegado:** https://REEMPLAZAR-CON-TU-LINK.netlify.app

## Tecnologías
- HTML5 semántico
- SCSS (variables, nesting, mixins con parámetros, `@extend`) compilado a `styles/style.css`
- Bootstrap 5 (navbar responsiva y grilla)
- AOS (Animate On Scroll) + animaciones nativas con `@keyframes` y `transition`

## Estructura
```
index.html
pages/          servicios, proyectos, nosotros, contacto
scss/
  abstracts/    _variables, _mixins, _placeholders
  base/         _base, _animations
  layout/       _navbar, _footer
  components/   _buttons, _cards, _forms
  pages/        _home
  main.scss     (solo @use de los partials)
styles/style.css (compilado)
assets/img/
```

## Compilar SCSS
```bash
npm install -g sass
sass --watch scss/main.scss styles/style.css
```
