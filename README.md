# MI-LEY-IA

Proyecto para conservar el núcleo original de las tres leyes y experimentar con procedimientos y arquitecturas sin perder ni sustituir los originales.

## Organización

- `00_ORIGINALES/`: textos fuente. Se conservan literalmente; no se usan como espacio de experimentación.
- `experimentos/`: registro de variantes, hipótesis, pruebas, resultados y errores.
- `versiones/`: documentación de versiones que hayan superado la evaluación y recibido aprobación.
- Rama `main`: referencia estable; solo incorpora cambios aceptados.
- Rama `experimentos`: espacio de trabajo para desarrollar y probar variantes.

## Flujo de trabajo

1. Partir de una copia de referencia de las leyes originales.
2. Crear una variante experimental identificada.
3. Registrar qué cambia, qué se mantiene y qué hipótesis se evalúa.
4. Probarla con tareas comparables y criterios definidos antes de la prueba.
5. Registrar resultados, fallos y limitaciones, sin presentar hipótesis como resultados.
6. Comparar con la referencia.
7. Proponer la incorporación mediante Pull Request.
8. Incorporar a `main` únicamente después de revisión y aprobación.

## Protección del núcleo

Los archivos de `00_ORIGINALES/` no se modifican durante los experimentos. Toda adaptación se guarda en otra ruta y con identificación de versión. La protección técnica de la rama `main` debe activarse en GitHub (reglas de rama); la documentación por sí sola no impide escrituras.

## Estado actual

- Estructura inicial publicada.
- Los textos íntegros de las tres leyes siguen pendientes de incorporación desde fuentes verificables.
- La estructura experimental se está preparando.
- No hay secuencias validadas todavía.

## Principio rector

**Conservar el original; permitir experimentar; medir antes de aceptar; aprobar antes de integrar.**
