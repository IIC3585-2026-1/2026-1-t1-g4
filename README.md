# 2026-1-t1-g4: Pokémon CSS Arena 

**Curso:** IIC3585 – Diseño Avanzado de Aplicaciones Web 
**Grupo:** 4  


**[Ver el proyecto en vivo (Deploy en Render)](https://pokemon-css.onrender.com)**

---

## Integrantes

| Nombre |
|--------|
| Moisés Andrés Barraza Aguilera | 
| Ian Franco Fuenzalida Gallardo |
| Matías Ossul Corbalán | 
| Vicente José Rodríguez Acevedo | 

---

## Requisitos Técnicos Implementados

- **Media queries y container queries:** Adaptabilidad en toda la página y en componentes aislados (cartas).
- **Flexbox & Grid:** Layout principal, barra de navegación y galería fluida.
- **Variables y funciones (`calc`):** Centralización de tokens de diseño en `:root` y cálculos dinámicos de tamaño.
- **Anidación de reglas (Nesting):** Código CSS modular, limpio y jerárquico.
- **Transformaciones y Transiciones:** Efectos 3D en hover y transiciones de estado complejas.
- **Animaciones:** Secuencias temporales inmersivas (caída de rocas, drenado de HP, loader inicial).

---

## Declaración de Uso de IA y Autoevaluación Crítica

Durante el desarrollo de este proyecto, utilizamos herramientas de IA (Gemini / Copilot) estrictamente como asistentes de codificación y *brainstorming*, manteniendo el control total sobre la arquitectura y la integración.

### 1. Asistencia Técnica
* **Transformaciones y Grid:** Utilizamos la IA para entender la interacción entre `perspective` y `transform-style: preserve-3d` en elementos anidados, y para estructurar la lógica base de las Media Queries complementando nuestro Grid nativo (`auto-fit`).
* **Animaciones y Transiciones:** La IA nos asistió en la sintaxis de los `@keyframes` complejos (batalla de Mewtwo vs Tyranitar) y en la lógica base del "Checkbox Hack" para las evoluciones.

### 2. Autoevaluación Crítica y Correcciones Manuales
Al evaluar el código entregado por la IA, notamos limitaciones que corregimos manualmente:
* **Manejo de rutas:** La IA falló al sugerir rutas relativas para las imágenes desde los submódulos. Reestructuramos y corregimos manualmente todos los enlaces en el HTML.
* **Sincronización:** El código crudo para las animaciones de batalla causaba superposición. Ajustamos a mano los `animation-delay` y `transition-duration` (ej. `1.8s ease-in-out`) para lograr fluidez.
* **Diseño Responsivo:** La IA sugería tamaños estáticos (`px`) que rompían la UI en móviles. Intervenimos reemplazándolos por `calc()` y medidas relativas (`rem`, `%`).

### 3. Conclusión
El uso de la IA aceleró la escritura de sintaxis repetitiva, pero el diseño modular, la unificación de los estilos y la cohesión visual del proyecto fueron logrados enteramente mediante nuestro trabajo colaborativo y revisión manual, cumpliendo a cabalidad con los objetivos del curso.