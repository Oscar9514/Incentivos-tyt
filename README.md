# Plataforma de incentivos TYT

Plataforma de incentivos de marcas para aliados: metas volantes, días de marca y ofertas específicas. Los datos se guardan en Firebase (proyecto `incentivos-tyt`, plan gratuito Spark).

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La plataforma, conectada a Firebase |
| `firestore.rules` | Reglas de seguridad para pegar en Firestore > Reglas |
| `instructivo.pdf` | Instructivo de uso, se abre desde la pantalla de ingreso |
| `.nojekyll` | Le indica a GitHub Pages que publique los archivos tal cual |

## Puesta en marcha (una sola vez)

1. **Reglas:** en Firebase, Firestore Database > Reglas, borra todo, pega el contenido de `firestore.rules` y pulsa Publicar.
2. **Primer jefe:** en Authentication > Usuarios > Agregar usuario, crea `j.gina@incentivos-tyt.app` con una contraseña.
3. **Dominio:** en Authentication > Configuración > Dominios autorizados, agrega `oscar9514.github.io`.
4. **Resto de usuarios:** entra a la plataforma como Gina Bermúdez, pestaña Usuarios, y pulsa "Crear usuarios que falten". Copia la lista de contraseñas y entrégala a cada usuario por un canal privado.

## Cómo ingresa cada perfil

- Marcas, jefes y aliados: eligen su nombre y escriben la contraseña que les entregó el jefe.
- Especialistas (5): solo consultan. Eligen un aliado, ven sus incentivos aprobados y descargan PDF.

## Si alguien olvida su contraseña

En Firebase, Authentication > Usuarios, elimina su usuario. Luego el jefe pulsa "Crear usuarios que falten".

## Correos internos

Los usuarios no usan correo, pero Firebase los identifica así: marcas `m.oppo@incentivos-tyt.app`, aliados `a.cos-bogota@incentivos-tyt.app`, jefes `j.gina@` y `j.cesar@incentivos-tyt.app`, especialistas `e.zapata-gonzalez-vladimir@incentivos-tyt.app`.
