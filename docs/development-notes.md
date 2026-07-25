# Notas de desarrollo

## 23/7/2026

### Layout

Elegí CSS Grid para dividir el CV en dos columnas.

Flexbox quedó reservado para componentes internos.

### HTML

Decidí utilizar:

- article para proyectos.
- article para experiencias.
- section para agrupar contenido.

### Clases

Las listas reutilizan las clases:

tech-list
tech-item

Así si requieren estilos distintos se utiliza la descendencia.

.project .tech-list

aside .tech-list

---

## 24/7/2026

### CSS

Algunos criterios de unidades

- px → tamaños físicos de elementos (foto, borde, iconos, etc.).
- rem → espaciados y tamaños de texto que quiero que escalen con la tipografía.
- mm → cuando realmente quiero representar medidas de impresión (como el ancho de la hoja A4).
- % → tamaños relativos al contenedor.
- fr → distribución de columnas y filas en Grid.

---

### Próximas tareas

Definir una escala tipográfica
   - Niveles de títulos
   - Texto principal
   - Metadata (`time`, enlaces, información secundaria)

Definir un sistema de espaciados.
   - Espacio chico (elementos relacionados).
   - Espacio medio (título => contenido).
   - Espacio grande (entre componentes).

Revisar la ubicación de "Experiencia académica".

Revisar nombres de algunos componentes.
   - Analizar si `project` representa correctamente el concepto o si conviene un nombre más específico

Revisar posibles patrones repetidos
