# Control de integridad de los originales

**Estado general:** clasificación actualizada el 31-10-2026. Las dos leyes se trabajaron en conversaciones anteriores, pero sus copias literales aún no están incorporadas aquí. No reconstruirlas.

## Procedimiento al recuperar cada original

1. Recuperar el mensaje o archivo fuente completo.
2. Registrar conversación o procedencia, fecha, formato y alcance.
3. Copiar el texto sin corregirlo ni normalizarlo.
4. Comparar carácter por carácter la copia archivada con la fuente recuperada.
5. Calcular SHA-256 sobre los bytes exactos del archivo fuente conservado.
6. Registrar nombre, tamaño, codificación y SHA-256.
7. Volver a calcular SHA-256 y comprobar coincidencia.
8. Mantener cualquier versión corregida o derivada en una ruta separada.

## Registro de originales

| Número | Original | Procedencia conocida | SHA-256 de la fuente | Cotejo literal |
|---|---|---|---|---|
| 1 | MI LEY | El propietario confirma que estaba completa el 27-10-2026. Falta recuperar el texto íntegro. | Pendiente | Pendiente |
| 2 | LEY DE EFICACIA, RIGOR Y RESOLUCIÓN | Fue aportada y trabajada; consta referencia a 13 apartados y «PRINCIPIO SUPREMO». Falta recuperar el texto íntegro. | Pendiente | Pendiente |

## DF-IMIA y código numérico

DF-IMIA es el componente operativo número 3, no un original legal. Su formulación documentada se conserva en `../experimentos/DF-IMIA.md`. La confirmación del código numérico de aplicación se atribuye al propietario con fecha 31-10-2026; el literal exacto debe transcribirse desde su confirmación original, sin deducirlo de códigos anteriores.

## Advertencia

El SHA de objeto GitHub (Git blob SHA) no debe etiquetarse como SHA-256 del archivo: son identificadores distintos. La huella SHA-256 debe calcularse sobre los bytes exactos del archivo conservado.

No declarar verificados los originales hasta completar el cotejo literal y la comprobación de sus huellas.
