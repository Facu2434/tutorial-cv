# Tutorial CV

Presentación de 10 pantallas más 4 anexos cortos sobre cómo armar un currículum vitae. Un solo archivo (`index.html`), con el estilo de las clases de Geniso.

## Contenido

Recorrido principal (10 pantallas, el contador muestra "n / 10"):

1. Portada, con un CV de ejemplo
2. Un CV mal hecho y uno bien hecho, con los errores numerados
3. Las 4 partes, marcadas sobre el CV (se pueden tocar para resaltarlas)
4. Qué va y qué no en los datos personales, sobre el CV
5. Cómo escribirlo: la sección Experiencia del CV con marcas y un antes/después
6. El ATS, con un ejemplo ilustrado
7. Una columna o dos, lado a lado
8. Paso a paso del CV a dos columnas: una pantalla elige Google Docs o Word y siete pantallas más muestran un paso cada una (barra "Paso n de 6", captura grande, botón Siguiente)
9. Cuatro modelos para copiar
10. Cierre con el menú de anexos

Anexos, fuera del recorrido: se abren desde el menú de la pantalla 10 y tienen el botón "Volver al menú". Direcciones: `#a` foto, `#b` perfil online, `#c` carta de presentación, `#d` mejorar el CV con IA.

Cada pantalla tiene su dirección, por ejemplo `#s-parts`, `#st3` (paso 3) o `#st3.word` (paso 3 en Word).

## Publicar

En GitHub: Settings > Pages > Deploy from a branch > `main` / `(root)`.

## Capturas reales del paso a paso

La pantalla 8 usa capturas reales de Google Docs y de Word para la web (CV de ejemplo de Juan Pérez, noviembre 2026). Si una captura falta, se muestra un esquema dibujado en su lugar. Para reemplazar una, guardá la nueva con el mismo nombre dentro de `img/`, sin tocar el HTML:

- Google Docs: `img/docs-1.png` a `img/docs-6.png`
- Word: `img/word-1.png` a `img/word-6.png`

El número es el paso (1 nombre y puesto, 2 insertar tabla, 3 ancho, 4 contenido, 5 color, 6 bordes).

## Fuentes

- Google Docs, tablas: https://support.google.com/docs/answer/1696711?hl=es
- Word, insertar una tabla: https://support.microsoft.com/es-es/office/insertar-una-tabla-a138f745-73ef-4879-b99a-2f3d38be612a
- Word, quitar bordes: https://support.microsoft.com/es-es/word/remove-borders-from-a-table-in-word-for-mac
- Modelos de CV (`img/cv-*.png`): repo TIN, clases 29 y 29 bis.
- Contenido de CV, ATS, foto y perfil online: Geniso (`comparacion.html`, `guia.html`, `foto.html`) y TIN (clases 27, 29, 29 bis, 30 y 31).
