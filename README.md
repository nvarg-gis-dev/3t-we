# 3T Consultores · Sitio web

Sitio de 3T Consultores (ingeniería MEP y protección contra incendios, Ciudad de Panamá).
Es un solo archivo `index.html`, sin dependencias ni compilación. Se publica con GitHub Pages.

## Configuración

Al inicio del bloque `<script>` de `index.html`:

| Variable | Para qué sirve |
|---|---|
| `FORM_ENDPOINT` | Servicio que recibe el formulario (Web3Forms por defecto) |
| `FORM_KEY` | Access key de Web3Forms (es pública por diseño) |
| `WHATSAPP` | Número para el botón de WhatsApp, sin "+" ni espacios |

## Actualizar el sitio

Edite `index.html` y haga commit en la rama `main`. GitHub Pages publica el cambio en uno o dos minutos.
