# Markdown Cheat Sheet

Gracias por visitar [Ciberninjas](https://ciberninjas.com)!

Esta hoja de trucos de Markdown proporciona una descripción general rápida de todos los elementos de la sintaxis de Markdown. Si necesitas más información sobre cualquiera de los elementos, consulta las guías de referencia para [la sintaxis básica](https://ciberninjas.com/cheatsheet-hoja-trucos-markdown/#sintaxis-básica ""Conoce la sintaxis básica de Markdown en Ciberninjas"") y [la sintaxis extendida](https://ciberninjas.com/cheatsheet-hoja-trucos-markdown/#sintaxis-avanzada "Conoce la sintaxis avanzada de Markdown en Ciberninjas").

## Sintaxis Básica

Estos son los elementos descritos en el documento de diseño original de John Gruber, y todas las aplicaciones de Markdown admiten estos elementos.

### Encabezados

# H1
## H2
### H3

### Negrita

**texto en negrita**

### Cursiva

*texto en cursiva*

### Blockquote

> blockquote

### Lista Ordenada

1. Primer item
2. Segundo item
3. Tercero item

### Unordered List

- Primer item
- Segundo item
- Tercero item

### Código

`código`

### Línea Divisoria Horizontal

---

### Enlace

[título](https://ciberninjas.com)

### Imagen

![texto alt](ciberninjas-logo.jpg)

## Sintaxis Avanzada

Estos elementos amplían la sintaxis básica agregando características adicionales. No todas las aplicaciones de Markdown admiten estos elementos.

### Tabla

| Sintaxis | Descripción |
| ----------- | ----------- |
| Cabecera | Título |
| Párrafo | Texto |

### Bloque de Código

```
{
  "primerNombre": "Pablo",
  "primerApellido": "Álvarez",
  "age": 25
}
```

### Nota al Pie de Página

Esta es una frase con una nota al pie de página. [^1]

[^1]: Este es el pie de página.

### Encabezado con ID

### Mi Encabezado Principal {#id-personalizado}

### Definición

termino
: definición

### Contenido tachado

~~El mundo es plano.~~

### Lista de Tareas

- [x] Escribir el comunicado de prensa
- [ ] Actualizar la página web
- [ ] Contactar con la prensa
