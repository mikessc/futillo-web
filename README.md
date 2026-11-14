# Futillo — sitio web

Sitio estático (HTML + CSS, sin build) publicado con GitHub Pages en https://futillo.com.

Para ver cambios: edite `index.html` o `styles.css`, haga commit y push a `main`. GitHub Pages lo publica en uno o dos minutos.

## Links pendientes

Todo está en `index.html`. Use **Buscar y reemplazar** (Ctrl+H) en todo el archivo:

| Buscar | Reemplazar por | Dónde aparece |
|---|---|---|
| `href="#reservar"` | `href="https://...link-de-reservas..."` | Nav, hero, precios |
| `href="#youtube"` | `href="https://www.youtube.com/@...canal..."` | Redes flotantes, En vivo, footer |
| `href="#facebook"` | `href="https://www.facebook.com/...pagina..."` | Redes flotantes, footer |

**Horario** — en el footer, busque `[hora]` y ponga las horas reales:

```html
<span>Lunes a viernes: 7:00 a.m. – 11:00 p.m.<br>Sábados y domingos: 8:00 a.m. – 10:00 p.m.</span>
```

**Waze** — en el footer, busque `waze.com/ul?q=Futillo`. Lo más exacto es usar coordenadas:
abra Futillo en Waze → Compartir → copiar link, o use

```
https://www.waze.com/ul?ll=LATITUD,LONGITUD&navigate=yes
```

## Transmisión en vivo

En la sección "En vivo", reemplace el bloque `<div class="live__screen">…</div>` por el `<iframe>` que da YouTube (Compartir → Insertar) cuando haya transmisión.

## Imágenes

Van en `assets/`, con los mismos nombres que usa `index.html`. Si cambia una foto, mantenga el nombre del archivo.
