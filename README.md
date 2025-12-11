# agentic-bootcamp-askhr

Repositorio para el laboratorio de creación de un agente AskHR con IBM watsonx Orchestrate. Incluye datos, guías y ejemplos necesarios para completar el hands-on.

## Estructura

- `Datos/`
  - `Employee-Benefits.pdf`: documento base de conocimiento con los beneficios para empleados.
  - `hr.yaml`: especificación OpenAPI usada como toolset para consultar/actualizar datos HR.
  - `users_data.xlsx`: hoja de cálculo con usuarios de referencia para las pruebas.
- `hands-on-lab-askHR.md`: guía paso a paso del laboratorio (instrucciones, prerequisitos, capturas).
- `hands-on-lab-askHR/`: capturas de pantalla referenciadas en la guía.
- `general-questions.md`: ejemplos de preguntas y flujos de prueba para el agente.

## Objetivo

1. Construir un agente HR que responda preguntas sobre beneficios usando el PDF como base de conocimiento.
2. Conectar el agente a la API HR (definida en `hr.yaml`) para leer/actualizar perfiles, balances de vacaciones y solicitudes de time-off.
3. Validar el agente siguiendo el walkthrough de `hands-on-lab-askHR.md` y las preguntas de `general-questions.md`.
