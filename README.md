# ECG Learning Hub

Un solo enlace con las 3 ventanas del proyecto:

| Ventana | Contenido | Ubicación |
|---|---|---|
| 1 | Curso de aprendizaje (Coursebox) | enlace externo |
| 2 | Simulador de ritmos y 27 cardiopatías | `simulador/index.html` |
| 3 | Juego de 3 niveles + ranking | `game/index.html` |

La página principal es `index.html`. Las direcciones se cambian en la constante `VENTANAS`.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (público), por ejemplo `ecg-hub`.
2. Sube **el contenido** de esta carpeta (no la carpeta en sí): `index.html`, `game/`, `simulador/`, `.nojekyll`, `README.md`.
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. En 1-2 minutos tu enlace será `https://TU-USUARIO.github.io/ecg-hub/`.

Enlaces directos: `.../#v1`, `.../#v2`, `.../#v3`.

## Alternativa: Vercel
Importa el mismo repositorio en vercel.com (framework: *Other*) y se publica solo en cada commit.
