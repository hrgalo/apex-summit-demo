# APEX Summit — Landing page (demo)

Landing page estática de **APEX Summit**: expediciones premium de alta montaña para principiantes, organizadas desde Honduras.

> Versión demo. Los textos entre corchetes (`[PRECIO USD]`, `[POR DEFINIR]`, `[Foto: …]`, `[CORREO DE CONTACTO]`) son marcadores pendientes de completar con datos confirmados.

## Contenido

- `index.html` — página completa en un solo archivo (HTML + estilos en línea). No requiere build ni dependencias; las fuentes (Montserrat y Lato) se cargan desde Google Fonts.

## Ver localmente

Abre `index.html` en el navegador.

## Publicar con GitHub Pages

1. En el repositorio, ve a **Settings → Pages**.
2. En **Source**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
3. Guarda; GitHub mostrará la URL pública en unos minutos.

## Personalizar el color de acento

El acento está definido en una sola variable CSS dentro de `index.html`:

```css
:root{--accent:#C9CDD2}
```

Variantes exploradas en los mockups: verde bosque `#8FB59A`, ocre `#D2A866` y azul `#8FB3D9`.

## Pendientes antes de publicar

- Reemplazar el isotipo provisional (SVG en línea) por el logo vectorial definitivo de APEX Summit.
- Completar precios, duraciones, fotos y datos de contacto.
- Conectar el formulario de contacto a un servicio de envío (actualmente no envía datos).
