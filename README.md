# Pepe Paz — Actopan Primero

Landing page estática para presentar la trayectoria, los valores y la visión ciudadana de José Antonio Paz Ugalde para Actopan, Hidalgo.

## Versión de presentación

- El sitio se publica con GitHub Pages al ejecutar el workflow `Deploy static site to GitHub Pages` en la rama `main`.
- En GitHub, habilita **Settings → Pages → Build and deployment → Source: GitHub Actions** si Pages aún no está activado.
- El formulario está deshabilitado en esta versión y no recopila ni transmite datos. Para contacto se pueden usar los enlaces de WhatsApp y correo; el correo configurado es temporal para pruebas.
- El aviso de privacidad y algunos contenidos siguen siendo preliminares. Completa los datos marcados entre corchetes y revisa la información con el cliente antes de presentarlo como sitio definitivo.
- `logo-pepe.png`, `retrato-jose-antonio-paz.png` y las imágenes `trayectoria-*.png` son los recursos gráficos de la página.

## Plantillas de correo para una etapa posterior

Los diseños HTML para EmailJS están en [`email-templates/`](./email-templates/):

- [`notificacion-contacto.html`](./email-templates/notificacion-contacto.html) muestra nombre, correo y mensaje para el equipo.
- [`agradecimiento.html`](./email-templates/agradecimiento.html) es el borrador de respuesta para quien envíe el mensaje.

Las plantillas todavía no están conectadas a un proveedor: no se enviarán correos hasta configurar EmailJS y volver a habilitar el formulario. Antes de activar esa función, confirma el correo de destino y actualiza el aviso de privacidad con el flujo real de datos.
