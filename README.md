# APEX Summit — Landing page (demo)

Landing page estática de **APEX Summit**: expediciones de alta montaña, trekking y aventura para principiantes, organizadas desde Honduras.

> Versión demo. Los textos entre corchetes (`[PRECIO USD]`, `[POR DEFINIR]`, `[Foto: …]`, `[CORREO DE CONTACTO]`, perfiles del staff) son marcadores pendientes de completar con datos confirmados.

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
:root{--accent:#A9C4A0}
```

La versión actual usa la paleta verde (fondos verde bosque, acento salvia `#A9C4A0`). Alternativas: crema `#E4DCC3`, plata `#C9CDD2`, ocre `#D2A866`.

## Pendientes antes de publicar

- Reemplazar el isotipo provisional (SVG en línea) por el logo vectorial definitivo de APEX Summit.
- Completar precios, duraciones, fotos y datos de contacto.
- Completar los perfiles del staff (rol, experiencia, certificaciones) y los datos de las charlas técnicas.
- Conectar el formulario de contacto a un servicio de envío (actualmente no envía datos).
