# Proyecto de Herencia en CSS

Este proyecto es una demostración básica del uso de la herencia en CSS. Fue realizado como parte de una actividad para la clase del programa "Becalos Tech Challenge".

## Descripción

El objetivo de este proyecto es mostrar cómo se puede utilizar la herencia en CSS para aplicar estilos de manera eficiente y consistente en un documento HTML. Se han implementado varios ejemplos para ilustrar cómo los estilos pueden ser heredados y sobrescritos en diferentes elementos.

## Estructura del Proyecto

El proyecto consta de los siguientes archivos:

- `index.html`: Contiene la estructura HTML del proyecto.
- `style.css`: Contiene los estilos CSS aplicados al documento.
- `README.md`: Este archivo, que describe el proyecto.

## Detalles de Implementación

### Estilos Globales

Se han definido estilos globales para el elemento `body`, incluyendo la fuente, el peso de la fuente, el estilo de la fuente, el color y la altura de línea. Estos estilos se heredan por defecto en todos los elementos hijos.

```css
body {
    font-family: "Playwrite GB J Guides", cursive;
    font-weight: 400;
    font-style: normal;
    color: #333;
    line-height: 1.6;
}
```
## Herencia Explícita
Se han definido estilos específicos para el header y sus elementos hijos, como el h1.

```css
header {
    background-color: #f4f4f4;
    padding: 1em;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    color: #1a11c2;
}
```
## Estilos para Secciones
Se han aplicado estilos a las secciones y sus elementos hijos, demostrando cómo se pueden heredar y sobrescribir los estilos.

```css
section {
    margin: 1.5em 0;
    padding: 1em;
    border: 1px solid #ddd;
    background-color: #fafafa;
}

.herencia {
    font-family: Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

section h2 {
    font-size: 1.8rem;
    color: #444;
}

section p {
    margin: 0.5em 0;
}
```
## Clases y IDs Especificos
Se han utilizado clases e IDs para aplicar estilos específicos a ciertos elementos.

```css
.subrayado {
    background-color: yellow;
    font-weight: bold;
}

#especial {
    color: #f00;
}
```
## Forzar herencia
Se ha demostrado cómo se puede forzar la herencia de ciertos estilos utilizando inherit.

```css
div p {
    color: inherit;
    font-size: inherit;
}
```
## Conclusión
Este proyecto muestra cómo se puede utilizar la herencia en CSS para aplicar estilos de manera eficiente y consistente. Es una demostración básica pero efectiva de los conceptos de herencia en CSS.

## ¿Como puedo ver el resultado?
Visita la pagina de GitHub Pages
[Herencia CSS - Becalos Tech Challenge](https://andresarguelles.github.io/herencia-css/)

## Créditos
[Andres Arguelles](https://github.com/andresarguelles)