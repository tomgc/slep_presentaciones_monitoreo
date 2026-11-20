# Presentaciones del Área de Monitoreo (SLEP Costa Central)

Galería de presentaciones autocontenidas del Área de Monitoreo y Seguimiento de Procesos y Resultados Educativos. Se publica con GitHub Pages en:

https://tomgc.github.io/slep_presentaciones_monitoreo/

## Estructura

```
index.html                 galería (página de inicio)
presentaciones/            un .html autocontenido por presentación
miniaturas/                portada 16:9 (.jpg) de cada presentación, mismo nombre que su .html
assets/                    logo y fuentes gobCL usados solo por la galería
.nojekyll                  publica los archivos tal cual, sin procesarlos con Jekyll
```

## Agregar una presentación

1. Copiar el `.html` en `presentaciones/` (nombre en minúsculas, con guion bajo, sin tildes).
2. Copiar su portada en `miniaturas/` con el mismo nombre y extensión `.jpg` (opcional: sin miniatura, la tarjeta muestra el título).
3. Agregar una entrada al inicio de la lista `presentaciones` en `index.html` (título, tema, fecha, láminas, descripción, archivo, miniatura).
4. Hacer commit y push a `main`; Pages se actualiza en uno o dos minutos.

## Requisito de las presentaciones

Cada `.html` debe funcionar sin conexión: scripts, fuentes, imágenes y datos embebidos (sin llamadas a CDN, a teselas de mapas ni a APIs).
