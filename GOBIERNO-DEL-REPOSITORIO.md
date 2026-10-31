# Gobierno y control de cambios

## Roles

- **Propietario del proyecto:** decide qué se acepta como versión oficial.
- **Colaborador:** puede proponer cambios y experimentos.
- **Revisor:** analiza cambios, evidencia, riesgos y reproducibilidad.

## Flujo recomendado

1. El trabajo experimental se realiza en la rama `experimentos` o en ramas derivadas.
2. Los cambios se presentan mediante Pull Request hacia `main`.
3. El Pull Request explica objetivo, diferencias, pruebas y posibles efectos sobre el núcleo.
4. El propietario revisa y decide.
5. Solo los cambios aprobados se integran en `main`.

## Ajustes técnicos pendientes en GitHub

Activar reglas de protección para `main`:

- exigir Pull Request antes de integrar;
- exigir al menos una aprobación;
- descartar aprobaciones obsoletas cuando cambie el contenido;
- exigir que las conversaciones de revisión estén resueltas;
- bloquear force-push y borrado de la rama;
- limitar quién puede hacer bypass de las reglas al propietario.

Si el plan de GitHub o la configuración de la cuenta no permite alguna regla, dejar constancia y aplicar el control disponible más estricto. La existencia de este documento no activa por sí sola las protecciones.

## Protección especial de los originales

Los originales de `00_ORIGINALES/` no se editan en experimentos. Una corrección del original requiere una nueva copia fuente verificable, registro de procedencia y aprobación expresa. Las versiones anteriores deben conservarse en el historial.
