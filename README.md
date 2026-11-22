# Plataforma de incentivos TYT (boceto)

Boceto navegable de la plataforma de incentivos de marcas para aliados: metas volantes, días de marca y ofertas específicas.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La plataforma completa en un solo archivo |
| `presentacion.pdf` | Presentación de la plataforma (se abre desde el botón de la pantalla de ingreso) |
| `.nojekyll` | Le indica a GitHub Pages que publique los archivos tal cual |

## Publicar en GitHub Pages

1. Entra a github.com y crea un repositorio nuevo, por ejemplo `incentivos-tyt`.
2. Pulsa **Add file > Upload files** y sube los tres archivos de esta carpeta.
3. Pulsa **Commit changes**.
4. Ve a **Settings > Pages**.
5. En **Source**, elige **Deploy from a branch**. En **Branch**, elige `main` y la carpeta `/ (root)`. Pulsa **Save**.
6. En uno o dos minutos la página queda publicada en `https://TU-USUARIO.github.io/incentivos-tyt/`.

Para actualizar la página, vuelve a subir el `index.html` nuevo en el mismo repositorio.

## Cómo probarlo

- Elige un usuario (marca, jefe de canal o aliado). La contraseña de prueba es `1234`.
- Los incentivos precargados son datos de ejemplo.

## Limitaciones del boceto

- Los datos se guardan solo en el navegador de cada persona. Lo que aprueba un jefe no lo ve un aliado en otro computador.
- Las contraseñas no son seguras: están dentro del código de la página.
- En una cuenta gratuita de GitHub, el repositorio y la página son públicos. No subas datos reales de metas o pagos.

Para la versión final hace falta un servidor con base de datos y usuarios reales (servidor de TYT o Firebase).
