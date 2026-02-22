# Desafío 8 — Layout Ecommerce con CSS Grid

Resumen rápido
- Proyecto ubicado en: `index.html` y `css/style.css`.
- Objetivo: implementar un layout de ecommerce responsivo usando solo HTML y CSS.

Cómo abrir
1. Abrir `index.html` en un navegador moderno (doble clic o `Archivo → Abrir`).

Características implementadas
- Diseño responsivo con CSS Grid (3→2→1 columnas).
- Sidebar de filtros (CSS-only) por categoría usando checkboxes.
- Tarjetas de producto con imagen placeholder, título, precio y CTA.
- Quickview accesible con `<details>`/`<summary>`.
- Toast visual al añadir (implementado con `:target`).
- Navegación móvil CSS-only (toggle con checkbox + label).
- Mejoras de accesibilidad: skip-link, roles ARIA básicos, focus-visible.

Verificación / Checklist
- [x] Layout Grid responsivo para productos y sidebar
- [x] Header y navegación responsive
- [x] Filtros funcionales por categoría (CSS-only)
- [x] Tarjetas de producto completas (imagen, título, precio, CTA)
- [x] Interacciones accesibles (`details`, `:target`, focus-visible)
- [x] Placeholders de imagen añadidos
- [x] README creado y documentación mínima

Limitaciones conocidas
- Búsqueda por texto, ordenamiento avanzado y carrito persistente requieren JavaScript (no implementado por petición).
- El toast y "Agregar" son visuales; no hay persistencia de carrito.

Siguientes pasos recomendados
- Añadir un pequeño `main.js` para: búsqueda en tiempo real, filtrado combinado, y carrito con localStorage.
- Reemplazar placeholders por imágenes reales y optimizarlas (webp, tamaños adecuados).
- Ejecutar pruebas de accesibilidad con Lighthouse o axe-core.

Archivos relevantes
- `index.html`
- `css/style.css`

Si quieres, añado la versión con JavaScript para completar la funcionalidad (búsqueda, filtrado por texto y carrito persistente). Indica si autorizas JS.
