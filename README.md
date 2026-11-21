# Futillo — sitio web

Sitio estático (HTML + CSS, sin build) publicado con GitHub Pages en https://futillo.com.

Para ver cambios: edite `index.html` o `styles.css`, haga commit y push a `main`. GitHub Pages lo publica en uno o dos minutos.

## Cambiar links y datos

Todo está en `index.html`. Use **Buscar y reemplazar** (Ctrl+H) en todo el archivo.

**Redes** — Instagram, Facebook y YouTube aparecen dos veces (redes flotantes y footer), y YouTube también en "En vivo". Para cambiar uno, busque su dirección actual y reemplácela.

**Horario** — en el footer, busque `Lunes a domingo` y cámbielo ahí mismo.

**Reservas** — los 3 botones de reservar apuntan a futcinco.com. Si cambia el link, busque `futcinco.com/book` y reemplácelo.

**Waze** — en el footer, busque `waze.com/ul?q=Futillo`. Lo más exacto es usar coordenadas:
abra Futillo en Waze → Compartir → copiar link, o use

```
https://www.waze.com/ul?ll=LATITUD,LONGITUD&navigate=yes
```

## Transmisión en vivo

En la sección "En vivo", reemplace el bloque `<div class="live__screen">…</div>` por el `<iframe>` que da YouTube (Compartir → Insertar) cuando haya transmisión.

## Imágenes

Van en `assets/`, con los mismos nombres que usa `index.html`. Si cambia una foto, mantenga el nombre del archivo.
