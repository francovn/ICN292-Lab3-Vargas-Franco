# ICN292-Lab3-Vargas-Franco

# Laboratorio 3 - Automatización de procesos con n8n

**Asignatura:** ICN-292 - Sistemas de Información para la Gestión

**Estudiante:** Franco Vargas Nieto

**RUT sin dígito verificador:** [216266544]

**Fecha:** Septiembre de 2026

## Descripción del laboratorio

El presente laboratorio tiene como objetivo desarrollar un sistema de automatización para el proceso de devoluciones de AndesHogar, utilizando la plataforma n8n.
Para ello, se implementaron tres workflows que permiten recibir y clasificar solicitudes, registrar los resultados y generar un resumen diario de las solicitudes procesadas.
Adicionalmente, se realizaron pruebas para verificar el funcionamiento de las reglas de negocio e identificar las limitaciones del sistema.

## Estructura del repositorio

- `ICN292-Lab3-Vargas-Franco.pdf`                    |  Informe del laboratorio con el desarrollo, los resultados y las conclusiones.                
- `ICN292-Lab3-Vargas-Franco.tex`                    |  Código fuente LaTeX del informe.                                                             
- `Workflows/ICN292-Lab3-Vargas-Franco-triage.json`  |  Workflow principal encargado de recibir, evaluar y clasificar las solicitudes de devolución. 
- `Workflows/ICN292-Lab3-Vargas-Franco-emisor.json`  |  Workflow encargado de enviar las solicitudes de prueba al flujo principal.                   
- `Workflows/ICN292-Lab3-Vargas-Franco-resume.json`  |  Workflow encargado de generar el resumen diario de las solicitudes procesadas.               
- `Capturas/`                                        |  Capturas de pantalla de los workflows y de las pruebas realizadas.                                               
## Instrucciones de ejecución

Para reproducir el laboratorio, se debe acceder a la plataforma n8n e importar los archivos `.json` disponibles en la carpeta `Workflows`.
Posteriormente, se deben configurar las conexiones utilizados en el flujo principal, junto con el Webhook correspondiente.
Una vez configurados los workflows, se debe ejecutar el flujo *triage* y enviar las solicitudes mediante *emisor*.
Finalmente, se puede ejecutar el workflow *resumen* para generar los indicadores correspondientes a las solicitudes registradas.
Las evidencias de ejecución y los resultados obtenidos se encuentran disponibles en el informe y en la carpeta `Capturas/`.

