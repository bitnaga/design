# Bitnaga · contenido web (`bitnaga/design`)

Contenido público que alimenta [web.bitnaga.es](https://web.bitnaga.es). La web lo lee directamente de este repositorio: al subir un cambio a `main`, aparece en la web en unos minutos (GitHub cachea los ficheros ~5 min).

| Carpeta | Contenido | Se muestra en |
|---|---|---|
| [`empleo/`](empleo) | Una oferta de empleo por fichero `.md` | Página Empleo |
| [`prensa/`](prensa) | `prensa.md` con todas las publicaciones + `imagenes/` | Página Prensa |
| [`diseno/`](diseno) | Logotipos y recursos gráficos de marca | Enlace "Recursos gráficos" en Prensa |

Solo los mantenedores de Bitnaga pueden publicar cambios.

## Publicar una oferta de empleo
1. Copia `empleo/_plantilla.md` a `empleo/nombre-del-puesto.md` (sin espacios ni tildes en el nombre del fichero).
2. Rellena las cabeceras y la descripción.
3. Para retirarla: pon `activa: no` o borra el fichero.

## Añadir una publicación de prensa
Añade un bloque nuevo al **principio** de `prensa/prensa.md` (separado del anterior por una línea `---`). Las imágenes van en `prensa/imagenes/`.

## Recursos gráficos
Todo lo que haya en `diseno/` queda disponible para descarga desde la web.
