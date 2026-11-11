# Control de asistencia FP 

MicroApp HTML/CSS/JavaScript sin dependencias ni servidor. Permite pasar lista sobre identificadores ficticios, contabilizar presentes/faltas/retrasos/justificadas, imprimir y descargar un CSV separado por punto y coma (compatible con LibreOffice Calc).

## Uso

Abrir `index.html` en el navegador, o publicarlo en GitHub Pages desde `main` y `/(root)`.

## Seguridad y privacidad

**No es un sistema de asistencia oficial.** No tiene autenticación ni almacenamiento persistente. No recopila, envía ni guarda automáticamente información; todo se mantiene en memoria del navegador hasta cerrar o recargar la página. El CSV descargado sí queda almacenado en el dispositivo del usuario y debe protegerse si se utiliza en otro contexto. No introducir datos personales reales. Para uso docente real, migrar a una solución institucional autorizada con control de accesos, trazabilidad, conservación y protección de datos.

## Estructura

- `index.html`: página completa, estilos y JavaScript.
- `README.md`: instrucciones y límites.

## Publicación

Crear repositorio `control-asistencia-fp`, subir ambos archivos y activar **Settings > Pages > Deploy from a branch > main > /(root)**.
