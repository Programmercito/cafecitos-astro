# Cafecitos System

Página de presentación de Cafecitos System, una herramienta de gestión para cafeterías y restaurantes.

## Desarrollo

Requiere Node.js 22.23.4 o superior y pnpm 11.

```sh
pnpm install
pnpm dev
```

La página de desarrollo está disponible en `http://localhost:4321`.

| Comando | Acción |
| --- | --- |
| `pnpm build` | Genera el sitio de producción en `dist/`. |
| `pnpm preview` | Previsualiza el sitio generado. |
| `pnpm astro --help` | Muestra las opciones de Astro. |

## Publicación

El sitio publicado se mantiene en `docs/`. Después de compilar, actualiza esa carpeta con el contenido de `dist/` y conserva `docs/CNAME` y `docs/.nojekyll`.
