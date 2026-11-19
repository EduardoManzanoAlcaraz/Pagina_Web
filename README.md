# Página informativa del Villarreal

Ejercicio web académico: nueve páginas HTML sobre el club, estadio, jugadores y títulos, con índice y manual de navegación. Es contenido estático; no hay JavaScript, CSS, backend, autenticación ni instalación de paquetes.

## Abrir y navegar

Abre `Indice/index.html` en un navegador. Si tienes Python, desde la raíz puedes servirlo en loopback:

```sh
python -m http.server 8080 --bind 127.0.0.1
```

Visita `http://127.0.0.1:8080/Indice/index.html`. No existe `index.html` en la raíz. Con Lynx instalado, `lynx Indice/index.html` abre el índice; el texto original de `Manual/Manual.html` se conserva como material histórico.

El índice enlaza `Información_General/`, `Estadio/`, `Jugadores_Destacados/`, `Titulos_Y_Logros/` y `Manual/`. Las fichas adicionales de jugadores están junto a su página de listado. Conserva las rutas con tildes y su capitalización.

## Estado y mantenimiento

Revisión del 2026-11-19 sobre `af254d19d6830c5a80d8ccecb39a9896bbd3b71d`. Las observaciones del código se distinguen de las pruebas ejecutadas y de los informes históricos. Esta revisión solo modifica documentación.

Se inspeccionaron los nueve HTML y la navegación referenciada. No hay build, suite de tests ni CI. No se realizó un recorrido visual en navegador ni se contrastó el contenido deportivo con fuentes oficiales; los textos son material del ejercicio y pueden contener errores o datos desactualizados. Las páginas tampoco comparten una estructura HTML completa uniforme.

Prueba manual pendiente: abrir el índice, seguir sus cinco enlaces y las tres fichas de jugadores, y comprobar acentos y lectura con navegador/Lynx. Como próximos pasos, revisar primero contenido y semántica/accesibilidad; cualquier corrección de páginas debe ir en un cambio separado de esta documentación.

[Instrucciones para agentes](AGENTS.md).
