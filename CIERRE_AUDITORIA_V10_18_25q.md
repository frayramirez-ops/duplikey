# CIERRE DE DESARROLLO — V10.18.25q

Fecha de revisión: 2026-10-21
Repositorio: frayramirez-ops/duplikey
Base de producción protegida: main, commit 1f3617a3389dc54cd4844cf5d26c02c1f58ab8e6
Rama candidata: desarrollo

## Cambios incluidos
- Corrección de cabecera fija y espaciado superior del hero móvil (texto > motocicleta > familias).
- Contraste de desplegables de recepción de módulos y aviso FAQ.
- Recuadros CTA editoriales claros en subpáginas.
- Carrusel ampliado de 3 a 6 casos reales, conservando los casos 001–003.
- Tres imágenes de casos 004–006 y tres ambientaciones técnicas nuevas.
- Actualización de referencias y parámetros de caché CSS.

## Evidencias de control
- La comparación GitHub main...desarrollo indica main como ancestro, sin commits de main pendientes por integrar.
- assets/compat-public.js tiene el mismo SHA de blob en ambas ramas: cf8045e5fb5fe97babd3396e9b58ee5201853c6e.
- assets/casos-reales.js conserva los tres casos iniciales y contiene 004, 005, 006.
- Las tres imágenes de casos y los tres fondos ambientales existen en assets/casos y assets/ambient.
- El usuario confirmó visualmente la corrección del hero, los casos y los controles de contraste revisados.

## Límites de validación
- No se obtuvo acceso desde el entorno de auditoría al sitio servido por Netlify; no se ejecutó una prueba automatizada E2E.
- El último commit no devolvió un estado GitHub de publicación de Netlify.
- Conservar main sin modificaciones y no fusionar sin autorización separada.
- Existen archivos de imágenes duplicados en otras rutas no utilizadas; se preservaron para evitar borrados no auditados.

## Política de promoción
La rama desarrollo es candidata para revisión final. Requerir aprobación expresa antes de fusionar a main.
