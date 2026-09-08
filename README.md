# Portafolio Personal - Guía 4

## 📌 Descripción del proyecto

Este proyecto consiste en el desarrollo de un portafolio personal de una estudiante de Ingeniería de Software. El sitio web está diseñado como una página de una sola sección principal con diferentes bloques de contenido que permiten presentar información personal, proyectos, habilidades y medios de contacto.

El proyecto fue desarrollado aplicando HTML5 semántico y CSS3 con Flexbox, siguiendo los requisitos establecidos en el Brief 2 de la Guía 4 de Ingeniería Web.

---

## 🎯 Objetivo

El objetivo del proyecto es crear una página web personal, clara, organizada y responsive que permita presentar el perfil profesional de la desarrolladora y mostrar algunos de sus conocimientos y proyectos.

Además, se busca aplicar correctamente conceptos fundamentales de desarrollo web como:

- HTML5 semántico.
- CSS3.
- Flexbox.
- Diseño responsive.
- Media queries.
- Accesibilidad básica.
- Organización de proyectos web.
- Control de versiones con Git y GitHub.

---

## ✨ Características

El portafolio cuenta con las siguientes características:

- Barra de navegación superior.
- Nombre o marca personal.
- Enlaces internos entre las diferentes secciones.
- Sección de presentación.
- Sección "Sobre mí".
- Fotografía personal.
- Sección de proyectos.
- Tarjetas de proyectos con imágenes.
- Sección de habilidades mediante etiquetas o chips.
- Formulario de contacto.
- Pie de página con enlaces a redes sociales.
- Diseño adaptable a diferentes tamaños de pantalla.
- Estructura HTML5 semántica.
- Uso de Flexbox para la distribución de los elementos.

---

## 🧱 Estructura HTML5 semántica

El proyecto utiliza diferentes elementos semánticos de HTML5 para organizar correctamente el contenido.

### `<header>`

Contiene la barra de navegación principal del sitio.

### `<nav>`

Se utiliza para organizar los enlaces de navegación y los enlaces de redes sociales.

### `<main>`

Contiene el contenido principal del portafolio.

### `<section>`

Cada sección del portafolio está organizada mediante elementos `<section>`:

- Inicio.
- Sobre mí.
- Proyectos.
- Habilidades.
- Contacto.

### `<article>`

Cada proyecto se encuentra dentro de un elemento `<article>`, permitiendo representar cada tarjeta como un contenido independiente.

### `<aside>`

Se utiliza para mostrar un dato destacado relacionado con el perfil.

### `<footer>`

Contiene la información de derechos de autor y los enlaces de redes sociales.

---

## 📐 Flexbox

Flexbox es uno de los principales recursos utilizados para construir el diseño del proyecto.

Se utiliza en diferentes partes del sitio:

### Barra de navegación

La navegación utiliza Flexbox para distribuir el nombre personal y los enlaces horizontalmente.

### Sección "Sobre mí"

La imagen y el texto se organizan inicialmente en una fila:

```css
.sobre-contenido {
    display: flex;
    flex-direction: row;
}
