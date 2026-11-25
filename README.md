# Opinión sobre Química para Todos

Página para que quienes prueban [Química para Todos](https://gerardobenceno.github.io/quimica-para-todos/) dejen su opinión. Al terminar se genera un PDF con sus respuestas en su propio dispositivo y la persona se lo manda al autor. No se envía nada a ningún servidor.

Link para compartir: https://gerardobenceno.github.io/opinion-quimica-para-todos/

## Publicar

Settings, Pages, Source: "Deploy from a branch", rama `main`, carpeta `/ (root)`.

## Archivos

- `index.html`: la página completa (preguntas, estilos y generación del PDF).
- `vendor/jspdf.umd.min.js`: jsPDF 2.5.2 (licencia MIT, `vendor/jspdf-LICENSE.txt`), que arma el PDF en el navegador.
- `logo.png` y `favicon.png`: logo de Química para Todos.

Para cambiar una pregunta se edita `index.html` en dos lugares: el bloque `<fieldset>` del formulario y la lista `QUESTIONS` del script, que define el texto que sale en el PDF.
