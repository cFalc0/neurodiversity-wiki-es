# Wiki de Neurodiversidad (ES) — Esquema

Este repo es la traducción al español de [neurodiversity-wiki](https://github.com/cFalc0/neurodiversity-wiki).
Los artículos siguen el repo en inglés — no se editan directamente aquí.

---

## Publicación

Esta wiki se publica con [Quartz 4](https://quartz.jzhao.xyz/) en GitHub Pages.

| Configuración | Valor |
|---------------|-------|
| Directorio de contenido | `wiki/` (no estándar; configurado con `--directory wiki`) |
| Comando de build | `npx quartz build --directory wiki` |
| Deploy | Automático al hacer push a `main` |
| URL | `https://cfalc0.github.io/neurodiversity-wiki-es` |
| Config de deploy | `.github/workflows/deploy.yml` |

### Notas de Quartz

- **`wiki/index.md` es la página de inicio** — actualizar al agregar artículos nuevos
- **Wikilinks funcionan nativamente** — `[[nombre-articulo]]` y `[[carpeta/articulo|Texto]]` se resuelven correctamente
- **Artículos con `status: draft` no se publican** — el plugin `RemoveDrafts` los excluye del build
- **Las `aliases` generan redirecciones automáticas**
- **Las carpetas generan páginas índice automáticamente**

---

## Mapa de contenido

```
wiki/
├── tdah/
│   ├── rasgos-comunes-tdah.md
│   ├── disfuncion-ejecutiva.md
│   └── disforia-sensibilidad-al-rechazo.md
├── dislexia/
│   ├── que-es-la-dislexia.md
│   ├── procesamiento-fonologico.md
│   └── dislexia-en-la-adultez.md
├── enmascaramiento/
│   ├── enmascaramiento.md
│   └── desenmascaramiento.md
├── agotamiento/
│   └── agotamiento-neurodivergente.md
├── identidad/
│   └── diagnostico-tardio.md
├── habilidades-sociales/
│   └── navegar-espacios-neurotypicos.md
├── sobrecompartir/
│   └── por-que-las-personas-neurodivergentes-sobrecomparten.md
├── autodivulgacion/
│   └── autodivulgacion.md
├── estrategias-de-afrontamiento/
│   └── autodefensa.md
└── index.md
```
