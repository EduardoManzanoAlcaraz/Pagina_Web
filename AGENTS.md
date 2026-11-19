# Instrucciones para agentes — Pagina_Web

Se aplica a todo el repositorio. Codex debe leer este archivo; con Claude u otra herramienta, incluirlo explícitamente si no lo carga automáticamente.

## Antes de cambiar archivos

Lee `README.md`, `Indice/index.html` y `Manual/Manual.html`; después la página que vayas a editar y sus enlaces de entrada/salida.

Comprueba `git status --short` y la rama. Conserva cambios ajenos y lee las instrucciones de cualquier subdirectorio afectado. Contrasta los documentos con el código: un plan o resultado antiguo no demuestra una función actual. Limita cada cambio al encargo recibido.

## Reglas del proyecto

- Mantén HTML estático y navegación relativa. No introduzcas npm, un framework o un servidor de aplicación para este ejercicio.
- No cambies tildes/capitalización de rutas sin actualizar todas las referencias; un enlace que tolera Windows puede fallar en otro host.
- No conviertas datos deportivos presentes en afirmaciones verificadas o actuales. Si el encargo es corregir contenido, consulta fuentes primarias y registra su fecha.
- Conserva el manual y contenido útil; no reescribas las páginas durante una tarea solo documental.

## Validación y entrega

No existe compilación ni suite de tests. Verifica que cada `href` local resuelva a un archivo y recorre índice, cinco secciones y tres fichas. Un servidor HTTP de Python es opcional; detén solo el proceso que hayas iniciado. Distingue comprobación de enlaces de revisión visual y auditoría factual.

En cambios solo de documentación, comprueba rutas, enlaces relativos y comandos contra los archivos reales; no hace falta repetir toda la suite si no cambia el comportamiento. No inventes pruebas ausentes ni marques como aprobado un comando que no ejecutaste. Informa comando, resultado y alcance pendiente.

Revisa el diff antes de hacer commit. No incluyas dependencias instaladas, archivos generados, datos personales, credenciales, cookies, tokens ni archivos de entorno privados. Mantén los documentos útiles existentes y actualiza el estado si cambia una decisión o una limitación. Los commits deben explicar el resultado y su validación; separa documentación y cambios funcionales.
