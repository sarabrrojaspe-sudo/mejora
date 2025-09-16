# mejora
# Actividad: Estilización de Enlaces con CSS

## Descripción
En esta actividad se mejoró la apariencia e interactividad de una lista de enlaces utilizando **selectores**, **pseudoclases** y **pseudoelementos** en CSS.  
El objetivo fue aplicar estilos dinámicos y visuales para mejorar la **experiencia de usuario** y la **accesibilidad** de la página.

---

##  Selectores Utilizados

- **Selector de etiqueta**  
  `a { ... }` → aplica estilos base a todos los enlaces.

- **Pseudoclases de estado**  
  - `a:focus { ... }` → resalta el enlace al recibir foco (accesibilidad).  
  - `a:hover { ... }` → cambia estilo al pasar el ratón.  

- **Pseudoclases estructurales**  
  - `li:first-child a { ... }` → primer enlace de la lista.  
  - `li:last-child a { ... }` → último enlace de la lista.  
  - `li:nth-child(odd) a { ... }` → enlaces impares.  
  - `li:nth-child(even) a { ... }` → enlaces pares.  

- **Pseudoelementos**  
  - `a::before { ... }` → agrega un icono antes de cada enlace.  
  - `a::after { ... }` → agrega contenido extra al pasar el ratón.  
  - `a::first-letter { ... }` → resalta la primera letra de cada enlace.  

---

##  Cómo mejoran la experiencia de usuario
- El **hover con ::after** añade feedback inmediato al pasar el cursor.  
- El **focus** ayuda a la accesibilidad al navegar con teclado.  
- **First y Last child** permiten destacar enlaces clave.  
- **Alternancia con nth-child()** hace que la lista sea más legible y atractiva.  
- **First-letter y before** agregan detalles visuales sin modificar el HTML.  

---

##  Conclusión / Aprendizaje
Con esta actividad aprendí a:  
- Usar **pseudoclases** para detectar estados de los elementos.  
- Usar **pseudoelementos** para añadir contenido extra sin tocar el HTML.  
- Alternar estilos con **nth-child()** para dar un diseño más dinámico.  
- Mejorar la **usabilidad** y **accesibilidad** con pequeños detalles visuales.  

Este ejercicio demostró cómo el CSS no solo embellece, sino que también aporta a la **experiencia del usuario**.
