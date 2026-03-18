# Fundamentos de Visualización para el Análisis de Datos — UNIR

Materiales interactivos de la asignatura, publicados como sitio estático en GitHub Pages.

🔗 **Sitio:** `https://TU_USUARIO.github.io/fundamentos-visualizacion-unir/`

---

## Estructura del repositorio

```
fundamentos-visualizacion-unir/
├── index.html               ← Página de índice principal
├── ilusiones-opticas.html   ← Material 1: ilusiones ópticas
└── README.md
```

Cuando haya más materiales, se añaden en la raíz y se registran en `index.html`.

---

## Añadir un nuevo material

1. Coloca el archivo `.html` en la raíz del repositorio.
2. Abre `index.html` y localiza el bloque `<!-- ── PRÓXIMOS -->`.
3. Añade una nueva tarjeta siguiendo esta plantilla:

```html
<a class="material-card" href="NOMBRE-ARCHIVO.html">
  <div class="card-meta">
    <span class="card-tag highlight">Interactivo</span>
    <span class="card-tag">TEMA</span>
  </div>
  <div class="card-title">TÍTULO DEL MATERIAL</div>
  <div class="card-desc">
    Descripción breve de qué cubre y para qué sirve.
  </div>
  <div class="card-footer">
    <span>DATO 1</span>
    <span>DATO 2</span>
  </div>
</a>
```

4. Si quieres dejar un placeholder "Próximamente", usa `class="material-card coming-soon"` y cambia `<a>` por `<div>`.

---

## Tags disponibles para las tarjetas

| Tag | Uso |
|---|---|
| `highlight` (rojo) | Material completado y disponible |
| Sin clase | Categoría temática, duración, formato |
| `coming-soon` en la card | Placeholder no clicable |

---

UNIR · Fundamentos de Visualización para el Análisis de Datos
