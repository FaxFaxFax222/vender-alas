# Vender alas · Informe Red Bull

Resumen interactivo del informe de branding sobre Red Bull. Trabajo académico UADE · FACE · TPO 2026, no afiliado a Red Bull GmbH.
Arrambide Félix · Trentín Matías.

Sitio estático: todo vive en `index.html` (HTML, CSS y JS), sin dependencias ni build.

| Ruta | Contenido |
|---|---|
| `index.html` | Página completa |
| `assets/logo/` | Isotipo del TP (`isotipo.svg`) y sus capas para la animación de entrada (`sol.svg`, `toros.svg`) |
| `assets/video/` | Un clip por capítulo, de `00-portada` a `06-visual` |

El clip de la Conclusión todavía es provisorio y se carga desde internet. Para cambiarlo, guardá el definitivo como `assets/video/07-conclusion.mp4` y en `index.html` reemplazá el valor de `PH_CONCLUSION` por `` `${V}/07-conclusion.mp4` ``.

## Verlo localmente

```bash
python3 -m http.server 8000
```

Después abrí http://localhost:8000.

## Figma

Para clonar el repo en Figma (Make o capa de código), elegí este repositorio. Figma abre el `index.html` de la raíz; no hace falta configurar nada.
