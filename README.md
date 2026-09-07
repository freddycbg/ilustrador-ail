# Ilustrador AIL

Generador de resúmenes de beneficios para agentes de American Income Life.
El agente llena los datos del cliente, marca las coberturas y descarga la
ilustración en PDF para entregársela al cliente.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub (por ejemplo `ilustrador-ail`).
2. Subir el archivo `index.html` a la raíz del repositorio.
3. Ir a **Settings → Pages**.
4. En *Source* elegir **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
5. Guardar. En un par de minutos la página queda en:
   `https://<usuario>.github.io/ilustrador-ail/`

Cualquier agente con ese enlace puede usarla. No hace falta servidor ni base
de datos: es un solo archivo HTML.

## Cómo sale el PDF

- **En GitHub Pages:** el botón *Descargar PDF* abre el diálogo de impresión
  del navegador. Se elige "Guardar como PDF". Sale en calidad vectorial.
- **Publicado como artefacto de Claude:** el botón descarga el PDF directamente.

## Datos del agente

Cada agente escribe su nombre, teléfono, correo y número de licencia una sola
vez y pulsa *Guardar agente*. Quedan guardados en su propio navegador para las
siguientes cotizaciones.

## Aviso

Este generador produce un **resumen informativo preparado por un agente
autorizado**. No es el contrato de seguro y no lo sustituye. Las cifras las
escribe el agente; el generador no cotiza primas. Solo las cláusulas de la
póliza emitida por American Income Life Insurance Company determinan los
beneficios pagaderos.
