# Control de evolución del proyecto

Este documento permite seguir la evolución sin confundir cambios documentales, hipótesis y resultados comprobados.

## Ramas

- `main`: referencia estable del repositorio.
- `experimentos`: documentación y desarrollo de variantes en curso.

No se ha configurado protección técnica efectiva de ramas. La separación de ramas y el historial de commits ayudan a revisar cambios, pero **no impiden por sí solos** que alguien escriba directamente en ellas.

## Registro de cada evolución

Cada cambio relevante debe dejar constancia de:

- fecha;
- identificador;
- rama y commit;
- archivos añadidos o modificados;
- motivo del cambio;
- estado: propuesta, documentado, en prueba, evaluado, aprobado o descartado;
- evidencia disponible;
- limitaciones y siguiente paso.

## Estados permitidos

| Estado | Significado |
|---|---|
| Propuesta | Idea pendiente de formalizar |
| Documentado | Descrita en el repositorio, aún sin prueba |
| En prueba | Se están ejecutando tareas definidas |
| Evaluado | Hay resultados registrados y revisables |
| Aprobado | El propietario autoriza su incorporación estable |
| Descartado | Se conserva el registro, pero no continúa |

## Criterios de integridad

- No sobrescribir ni reconstruir los textos originales.
- No presentar hipótesis, razonamientos o simulaciones como resultados empíricos.
- Mantener los cambios experimentales fuera de los originales.
- Usar commits descriptivos para que cada evolución sea localizable.
- Comparar ramas y commits antes de integrar cambios.
- La incorporación a `main` requiere decisión expresa del propietario.

## Estado documentado en esta evolución

- DF-IMIA: formulación compacta registrada; validación sistemática pendiente.
- Secuencias 1321 y 3231: registradas como arquitecturas distintas por explorar; significado detallado y evaluación pendientes.
- Textos íntegros de MI LEY, Ley 2 y Ley 3: no incorporados todavía en el repositorio; no reconstruirlos.
- Protección automática de ramas: no disponible con la configuración/plan mostrado por GitHub; el ruleset creado no se aplica al repositorio privado según el aviso de GitHub.
