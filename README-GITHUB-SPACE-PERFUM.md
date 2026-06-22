# Space Perfum Updates

Repositorio publico para publicar actualizaciones de Space Perfum.

## Archivos

- `update-manifest.json`: le dice a la app cual es la ultima version disponible.
- `Space-Perfum-App-Segura-Para-Enviar.zip`: se sube en GitHub Releases.

## Proceso para publicar una version

1. Crear un nuevo release en GitHub.
2. Poner como tag algo como `v1.0.2`.
3. Subir el archivo `Space-Perfum-App-Segura-Para-Enviar.zip`.
4. Editar `update-manifest.json` con la nueva version y el enlace del ZIP.

La base de datos del negocio no se sube a GitHub.
