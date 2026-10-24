# Juntos es peor

Sitio de una sola página del grupo de stand-up. HTML, CSS y JS simples, sin build. Publicado en Netlify.

## Cambiar la próxima fecha

Editá `proxima-fecha.md` (en GitHub: abrir el archivo → ícono del lápiz → "Commit changes"). Netlify publica el cambio solo, en un minuto.

```
---
fecha: 2026-10-29          # AAAA-MM-DD
hora: "20:00"              # entre comillas; se muestra "20hs"
lugar: Ícaro Bar
direccion: Jorge Newbery 3549, Chacarita
precio: $15.000
reserva: Solo con reserva por Instagram
link_reserva: https://www.instagram.com/juntosespeor/   # vacío = sin botón "Reservar"
---

Texto libre opcional (se muestra en gris dentro de la entrada).
```

- El show se muestra hasta el día de la función inclusive (hora de Buenos Aires). Desde el día siguiente aparece "Próximamente nuevas fechas".
- Si el archivo está vacío o no existe, también aparece "Próximamente".

## Fotos

En `img/`: `sandra.jpg`, `cynthia.jpg`, `julio.jpg`, `bruno.jpg` (640 px de ancho). Para reemplazar una, subí otra con el mismo nombre.

## Dominio

Si el sitio no queda en `juntosespeor.netlify.app`, cambiá ese dominio en `og:url` y `og:image` de `index.html` para que el link se vea bien en WhatsApp.
