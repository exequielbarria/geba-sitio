# GEBA · Maintenance Engineering

Sitio web de GEBA, ingeniería de mantenimiento para PyMEs industriales (Córdoba y alrededores).

Es un sitio estático de una sola página: `index.html` contiene la estructura, los estilos y el código. Las imágenes están en `Imagenes/`, el logo en `Logo/` y el video de la portada en `Video/`.

## Ver el sitio en la PC

Abrir `index.html` con doble clic, o levantar un servidor local desde esta carpeta, por ejemplo:

```bash
npx serve .
```

## Configuración

Los datos de contacto y las integraciones se editan en el objeto `CONFIG`, al principio del `<script>` de `index.html`:

- `whatsapp`, `email`, `linkedin`: datos de contacto.
- `FORM_ENDPOINT`: disparador HTTP de Power Automate que recibe el formulario (pendiente).
- `AGENDA_URL`: página de reservas de Google Calendar (pendiente).

## Publicación

Publicado con GitHub Pages en https://exequielbarria.github.io/geba-sitio/. Cuando el dominio geba.com.ar esté registrado, se agrega un archivo `CNAME` con `geba.com.ar` y se configura el dominio en Settings → Pages.
