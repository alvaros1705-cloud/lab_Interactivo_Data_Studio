LABORATORIO INTERACTIVO DATA STUDIO + HUELLA TECNOLÓGICA

Versión bilingüe Español / English.
Abra index.html en un navegador moderno. Use los botones con banderas de Colombia y el Reino Unido para cambiar el idioma. Las banderas están dibujadas como SVG dentro del HTML, por lo que no dependen de que el equipo tenga una fuente de emojis instalada. La selección se guarda localmente en el navegador cuando el almacenamiento está disponible.

Contenido educativo, cuestionarios, navegación entre módulos y ejercicios incluidos.
Para publicar en GitHub Pages, suba index.html (y la carpeta assets, si aplica) al repositorio.

Autoría académica: Alvaro Salamanca Landínez · Universidad Simón Bolívar, Campus Cúcuta.

Correcciones técnicas de esta versión:
- Las cinco preguntas requieren seleccionar una opción antes de comprobar.
- Una vez evaluada una pregunta, todas sus opciones quedan bloqueadas; si la respuesta fue incorrecta, se muestra y resalta la correcta.
- Las respuestas evaluadas, listas de verificación, notas, formularios, rúbrica y módulos visitados se guardan localmente entre sesiones cuando localStorage está disponible.
- La auditoría solo confirma preparación completa cuando se marcan todos sus puntos; si se desmarca alguno, el aviso se actualiza.
- El laboratorio no se marca como completado hasta visitar los siete módulos, responder las cinco preguntas, completar las dos listas de verificación y rellenar los cuatro campos de interpretación.
- El diseño original se conserva. Se ajusta el salto de nombres largos solo en espacios estrechos para evitar desbordamiento en móvil.
- La versión base tenía pruebas de navegación y responsive en Chromium. Para esta ampliación se validaron la sintaxis JavaScript, la estructura HTML, los siete criterios y la suma de ponderaciones. La unión de PDFs depende de que el navegador pueda cargar las bibliotecas desde sus CDNs; debe verificarse en el sitio publicado.



Actualización del centro de evidencias (versión ampliada):
- Incluye identificación de la entrega para la práctica de Huella Tecnológica o el proyecto del segundo parcial.
- Permite documentar cinco KPI, cuatro visualizaciones, segmentadores y tres hallazgos.
- Permite adjuntar capturas reales (PNG/JPG/WebP) y un PDF exportado desde Looker Studio; los archivos adjuntos se guardan en IndexedDB del navegador cuando está disponible.
- La rúbrica tiene siete criterios con calificaciones individuales de 1,0 a 5,0 y ponderaciones que suman 100 %. La nota ponderada también se expresa sobre 5,0 y es solo una propuesta revisable por el docente.
- Botón de informe integral: genera el PDF del laboratorio y, si se ha adjuntado el PDF original de Looker Studio, intenta unir ambos archivos en un PDF final. Para la generación y unión automática, el navegador debe tener acceso a los scripts de html2pdf.js y pdf-lib desde sus CDNs; si fallan, la página abre una versión imprimible como alternativa y explica la limitación. Los archivos del estudiante se procesan en el navegador, sin enviarlos a un servidor externo.
- Exportación de matriz KPI/visualizaciones como CSV y descarga independiente de las capturas en ZIP.
- Copia de seguridad ZIP que incorpora el estado local y archivos adjuntos; permite restaurar el trabajo en el mismo navegador o en otro.
- localStorage/IndexedDB dependen del navegador, perfil y origen del sitio. Si se borran los datos del navegador, usa la copia de seguridad ZIP.


Flujo recomendado para la entrega final:
1. Completar la identificación, registrar los cinco KPI, describir al menos cuatro visualizaciones y documentar tres hallazgos.
2. Adjuntar capturas reales y exportar el informe de Looker Studio desde Compartir → Descargar → PDF.
3. Adjuntar ese PDF al centro de evidencias y pulsar «Generar informe PDF e integrar PDF de Looker Studio». Si las bibliotecas se cargan correctamente, el navegador descarga un único PDF con el informe del laboratorio primero y el PDF original después.
4. Si la biblioteca PDF no se puede cargar por falta de conexión o por una política del navegador, el laboratorio ofrece la impresión como alternativa; en ese caso no se afirma que los dos PDF se hayan unido.
5. Usar «Descargar capturas del dashboard (ZIP)» para conservar las capturas aparte y «Crear copia de seguridad ZIP» para respaldar formularios, avance, rúbrica y archivos adjuntos.

Privacidad en equipos compartidos:
- El progreso, los formularios, las notas propuestas y los adjuntos se guardan en el perfil local del navegador, no en una cuenta institucional. En computadores compartidos, descarga la entrega y elimina los datos locales al finalizar, o usa perfiles de navegador separados. El botón «Borrar datos guardados de este navegador» elimina el progreso y los adjuntos locales después de una confirmación.


Alineación con la guía del segundo parcial:
- La entrega empresarial documenta cinco KPI, cuatro visualizaciones informativas además de tarjetas KPI cuando corresponda, tabla de detalle, segmentadores, fuentes y tres hallazgos con evidencia, interpretación y decisión/limitación.
- El centro de evidencias sirve tanto para Huella Tecnológica como para el proyecto empresarial del segundo parcial.
- El aviso sobre datos simulados está visible en el centro y se incluye en el informe exportado. El estudiante debe reproducir la advertencia dentro de su propio dashboard cuando use datos simulados.
- La autoevaluación usa siete criterios con pesos de 15, 20, 20, 15, 15, 10 y 5 %. Las calificaciones por criterio y la nota propuesta se mantienen entre 1,0 y 5,0. La nota del navegador es una propuesta revisable por el docente.
- El respaldo/restauración incluye también los campos del centro de evidencias y archivos adjuntos cuando IndexedDB está disponible.
