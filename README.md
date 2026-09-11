# Liga Dominical — Sistema de campeonato

Panel de organización para un campeonato amateur de fulbito y vóley: inscripción de equipos,
fixture todos contra todos, planilla en vivo, resultados con doble firma, tabla, estadísticas y pagos.

## Ver la app

`index.html` es la aplicación completa en un solo archivo. Se abre con doble clic, sin instalar nada.

## Publicar con GitHub Pages

1. Sube este repositorio a GitHub (rama `main`).
2. En el repo: **Settings → Pages**.
3. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
4. En uno o dos minutos GitHub te da el link público:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Archivos

- `index.html` — aplicación lista para publicar (todo incluido).
- `Liga Dominical - Panel.dc.html` — fuente del panel de escritorio, para seguir editando.
- `Liga Dominical - Movil.dc.html` — fuente de la vista móvil.
- `support.js`, `image-slot.js`, `ios-frame.jsx` — soporte que usan las fuentes.
- `_ds/` — sistema de diseño (tipografía, colores, componentes).

Para actualizar `index.html` hay que volver a compilarlo desde la fuente; editarlo a mano no es recomendable.

## Nota sobre los datos

Los datos viven en el navegador de cada dispositivo: sirve para mostrar y probar el sistema,
pero lo que carga una mesa no le llega al organizador. Para datos compartidos hace falta
una base de datos (Firebase Firestore o Supabase, ambos con plan gratuito) y login por rol.

PIN de administración del prototipo: **1230**.
