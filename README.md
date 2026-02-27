# Vila-real-SportFest-2026
Vila-real SportFest 2026 es un evento deportivo abierto a todas las edades que reúne torneos, exhibiciones y actividades saludables en las instalaciones deportivas municipales de Vila-real. Su objetivo es fomentar el deporte, el compañerismo y un estilo de vida activo en un ambiente festivo y participativo.
# Vila-real SportFest 2026

## Descripción del proyecto

**Vila-real SportFest 2026** es una página web informativa para un evento deportivo abierto al público organizado por el Ayuntamiento de Vila-real. La web presenta de forma clara y atractiva el evento deportivo que incluye torneos de fútbol 7, basket 3x3, carrera popular 5K, pádel y fitness durante el fin de semana del 10-12 de abril de 2026.

## Secciones usadas con número de columnas Bootstrap

| Sección | Estructura Bootstrap |
|---------|---------------------|
| **Navbar** | `container` (1 fila completa) |
| **Hero** | `container` (1 columna completa) |
| **"Qué es"** | `row` + `col-md-6` + `col-md-6` (2 columnas) |
| **Modalidades** | `row` + 4x `col-lg-3` (4 columnas en desktop) |
| **"Programa e info"** | `row` + `col-lg-7` + `col-lg-5` (2 columnas) |
| **Contacto** | `container` + `col-lg-8` (1 columna centrada) |
| **Footer** | `container` + `flex-md-row` (2 columnas responsive) |

## Componentes prediseñados de Bootstrap usados

- **Navbar** (`navbar-expand-lg`, `navbar-dark`)
- **Grid system** (`row`, `col-md-6`, `col-lg-7`, `col-lg-5`, `col-lg-3`)
- **Cards** (`card`, `card-img-top`, `card-body`, `card-footer`)
- **Botones** (`btn`, `btn-primary`, `btn-outline-light`)
- **Listas** (`list-group`, `list-group-item`)
- **Badges** (`badge`)
- **Utilidades** (`py-5`, `text-center`, `shadow-sm`, `align-items-center`)

## Descripción de los diferentes commits y mejoras

1. **`feat: estructura inicial de la web`**  
   Creación del navbar, hero básico y footer con Bootstrap 5 CDN.

2. **`feat: primera sección con grid`**  
   Sección "Qué es" usando `row` + 2x `col-md-6`. Enlaces del navbar funcionales.

3. **`feat: segunda sección y componentes`**  
   Sección "Programa e info" (`row` + `col-lg-7` + `col-lg-5`). Añadidos cards, list-group y badges.

4. **`style: mejoras visuales y responsive`**  
   Archivo CSS propio con efectos hover, sombras y optimización móvil.

5. **`feat: pull request desde rama diseno-hero`**  
   Fusionado final con todas las secciones y estilos.

## Mayor dificultad encontrada y cómo se solucionó

**Problema**: Hacer que las imágenes se vieran bien en todas las pantallas (móvil, tablet, PC) y que las cards mantuvieran la misma altura.

**Solución**: 
- Usé `object-fit: cover` en CSS para las imágenes de las cards.
- Clases `h-100` en las cards para igualar alturas.
- Clases responsive del grid (`col-md`, `col-lg`) para adaptarse a cada dispositivo.
- Probé constantemente con F12 → modo responsive del navegador.

## Capturas del resultado final

📁 [Carpeta CAPTURAS](./CAPTURAS/)  
- `captura-home.png` - Vista principal  
- `captura-modalidades.png` - Sección deportes  
- `captura-movil.png` - Vista responsive  

---

**✅ Cumple todos los requisitos técnicos de la práctica**  
**Bootstrap 5** | **Responsive** | **Git workflow completo** | **Estructura obligatoria**
