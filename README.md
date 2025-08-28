# Preguntas y Respuestas sobre Desarrollo Web

## 1. ¿Qué es HTML y cuál es su función en la web?  
HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear páginas web. Su función es estructurar el contenido de la web mediante etiquetas que definen títulos, párrafos, enlaces, imágenes, formularios, entre otros.

---

## 2. ¿Qué es una etiqueta HTML y cuáles son las más comunes?  
Una etiqueta HTML es un elemento usado para definir la estructura y el contenido en una página web.  

**Ejemplos comunes:**  
`<html>`, `<head>`, `<body>`, `<h1> ... <h6>`, `<p>`, `<a>`, `<img>`, `<div>`, `<span>`.

---

## 3. ¿Qué es un atributo de una etiqueta HTML y cuáles son los más comunes?  
Un atributo es una característica que proporciona información adicional sobre un elemento HTML.  

**Ejemplos comunes:**  
`id`, `class`, `src`, `href`, `alt`, `style`, `title`.

---

## 4. ¿Qué es CSS y cómo se utiliza para el diseño web?  
CSS (Cascading Style Sheets) es un lenguaje que se usa para dar estilo y formato a los elementos HTML, como colores, fuentes, tamaños, márgenes y la disposición de los elementos en la página.

---

## 5. ¿Qué es una propiedad en CSS y cuáles son las más comunes?  
Una propiedad en CSS define el aspecto de un elemento.  

**Ejemplos comunes:**  
`color`, `background-color`, `font-size`, `margin`, `padding`, `border`, `width`, `height`.

---

## 6. ¿Qué es un selector en CSS y qué tipos existen?  
Un selector es la forma de elegir qué elementos HTML se van a estilizar.  

**Tipos de selectores:**  
- **Básicos:** etiqueta (`p`), clase (`.clase`), id (`#id`).  
- **Combinadores:** descendiente, hijo (`>`), adyacente (`+`).  
- **De atributo:** (`[type="text"]`).  
- **Pseudoclases:** (`:hover`, `:first-child`).  
- **Pseudoelementos:** (`::before`, `::after`).

---

## 7. ¿Qué es JavaScript y cómo añade interactividad a las páginas web?  
JavaScript es un lenguaje de programación que permite añadir interactividad y dinamismo a las páginas web, como validación de formularios, animaciones, actualización de datos sin recargar la página, entre otros.

---

## 8. ¿Cuáles son los tipos de datos primitivos en JavaScript?  
Los tipos primitivos en JavaScript son:  
- `string` → cadenas de texto  
- `number` → números  
- `boolean` → verdadero o falso  
- `undefined`  
- `null`  
- `symbol`  
- `bigint`

---

## 9. ¿Cómo funcionan las estructuras de control de flujo en JavaScript?  
- **if / else:** ejecutan bloques de código dependiendo de una condición.  
- **switch:** ejecuta diferentes bloques según el valor de una variable.  
- **Bucles:** (`for`, `while`, `do...while`) permiten repetir un bloque de código mientras una condición se cumpla.  

---

## 10. ¿Por qué es importante usar nombres significativos para variables y métodos?  
Porque facilita la lectura, el mantenimiento y la comprensión del código tanto para el programador como para otros que lo revisen.

---

## 11. ¿Qué es una variable de entorno y por qué son importantes?  
Una variable de entorno es un valor externo definido en el sistema operativo o en la configuración de un programa que influye en su ejecución.  

Son importantes porque permiten configurar credenciales, rutas, claves API y parámetros sin tener que escribirlos directamente en el código.

---

## 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?  
Son un conjunto de utilidades integradas en el navegador Chrome para inspeccionar, depurar y optimizar aplicaciones web.  

Se accede con **F12** o con clic derecho → **"Inspeccionar"**.

---

## 13. ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?  
Permite inspeccionar y modificar en tiempo real el código HTML y CSS de una página, para ver cómo afectan los cambios al diseño.

---

## 14. ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?  
Se usa para ejecutar código JavaScript directamente, mostrar mensajes, advertencias, errores y resultados de `console.log()`.  

Es útil para depuración y pruebas rápidas.

---

## 15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?  
Permite ver todas las solicitudes que hace la página (archivos cargados, APIs, tiempos de carga, estados de respuesta).  

Es importante porque ayuda a identificar problemas de rendimiento, errores en peticiones y optimizar la carga de recursos.  
