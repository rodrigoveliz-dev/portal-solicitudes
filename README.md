# Portal de Solicitudes — Netlify

Este paquete incluye:
- `index.html`: Portal con acceso a **Solicitud de Vehículos** y **Solicitud de Insumos**.
- `solicitud-vehiculos.html`: Formulario con validaciones, previsualización (modal) y Netlify Forms.
- `solicitud-insumos.html`: Formulario con previsualización (modal) y Netlify Forms.
- `success.html`: Página de confirmación.
- `netlify.toml`: Redirección `/success` → `success.html` y cabeceras de seguridad.

## Publicación
1. Crea un sitio en Netlify → *Add new site* → *Deploy with drag and drop*.
2. Arrastra **el contenido** de esta carpeta (no la carpeta en sí).
3. En *Site settings → Forms* verás los formularios **solicitud-vehiculo** y **solicitud-insumos** al recibir el primer envío.

## Notificaciones
- Activa notificaciones por correo en *Site settings → Forms → Notifications*.
- Puedes integrar con Google Sheets / Zapier si necesitas consolidación adicional.
