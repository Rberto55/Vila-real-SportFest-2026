# Vila-real-SportFest-2026
Vila-real SportFest 2026 es un evento deportivo abierto a todas las edades que reúne torneos, exhibiciones y actividades saludables en las instalaciones deportivas municipales de Vila-real. Su objetivo es fomentar el deporte, el compañerismo y un estilo de vida activo en un ambiente festivo y participativo.
# Vila-real SportFest 2026

## Descripción del proyecto
Página web informativa del Vila-real SportFest 2026, evento deportivo con torneos de fútbol 7, basket 3x3, carrera 5K, pádel y fitness. Organizado por el Ayuntamiento de Vila-real para el 10-12 abril 2026.

## Secciones y columnas Bootstrap
- Navbar: container (1 fila completa)
- Hero: container (1 columna)
- "Qué es": row + col-md-6 + col-md-6 (2 columnas)
- Modalidades: row + 4x col-lg-3 (4 columnas)
- "Programa e info": row + col-lg-7 + col-lg-5 (2 columnas)
- Contacto: container + col-lg-8
- Footer: container + flex-md-row

## Componentes Bootstrap usados
Navbar, grid system (row/col-*), cards, botones (btn), list-group, badges, utilidades (py-5, text-center, shadow-sm).

## Historial de commits
1. feat: estructura inicial (navbar, hero, footer)
2. feat: sección "Qué es" con grid 2 columnas
3. feat: sección programa con grid + cards y badges
4. style: CSS propio con efectos hover
5. feat: fusión rama diseno-hero vía pull request

## Mayor dificultad
Hacer las cards de igual altura en móvil. Solucionado con h-100 en cards y object-fit: cover en imágenes CSS. Probado con F12 modo responsive.

## Capturas
📁 [CAPTURAS](./CAPTURAS/)
- captura-home.png
- captura-modalidades.png  
- captura-movil.png
