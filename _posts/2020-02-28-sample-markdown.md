---
layout: post
title: Cómo el UX puede mejorar la recepción del producto
subtitle: Diseñar pensando en las personas marca la diferencia
gh-repo: Ritual01/miPagina
gh-badge: [star, fork, follow]
tags: [UX, diseño, experiencia-de-usuario]
comments: true
mathjax: false
author: Marcelo Manrique
---

{: .box-success}
Este es un pequeño blog donde comparto cómo el **Diseño de Experiencia de Usuario (UX)** puede hacer una gran diferencia en cómo los usuarios perciben e interactúan con un producto digital. Ya seas diseñador, desarrollador o simplemente alguien curioso, entender estos principios puede marcar un antes y un después en tu proyecto.

**Diseñar con intención significa diseñar con empatía.**

## ¿Por qué el UX importa?

[La experiencia de usuario](https://www.nngroup.com/articles/definition-user-experience/) no solo se trata de que algo se vea bonito. Se trata de **hacer que las personas se sientan cómodas**, que puedan lograr sus objetivos de forma rápida, fácil y sin frustraciones.

[Este es un link a mi portafolio UX](#portfolio) y [este otro a un recurso que me encanta](https://uxdesign.cc/).

Aquí hay una tabla simple para mostrar cómo un buen diseño UX puede influir:

| Problema común | Solución UX | Resultado |
| :------------- |:------------ | :-------- |
| Formularios largos | Dividir en pasos | Menos abandono |
| Botones confusos | Jerarquía visual clara | Mayor interacción |
| Texto técnico | Lenguaje simple y humano | Más comprensión |
| Sin feedback visual | Microinteracciones | Confianza del usuario |

## Algunos principios clave de UX:

- Empatía: Ponte en los zapatos del usuario.
- Consistencia: No reinventes la rueda en cada pantalla.
- Claridad: Elimina lo innecesario.
- Retroalimentación: Cada acción debe tener una reacción.

![UX UI](https://www.hostingplus.pe/wp-content/uploads/2024/03/UX.jpg)

A veces solo se trata de hacer que una app "se sienta" bien.

```javascript
// Microejemplo de accesibilidad: cambiar el foco con teclado
document.addEventListener('keydown', function(e) {
  if(e.key === 'Tab') {
    document.body.classList.add('user-is-tabbing');
  }
});

