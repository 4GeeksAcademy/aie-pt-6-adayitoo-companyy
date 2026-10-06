# Elección de empresa: TrackFlow

## ¿Por qué elegir TrackFlow?

Elijo TrackFlow porque su actividad de logística de última milla y almacén en EEUU y España ofrece procesos concretos donde aplicar automatización.
Sus tareas repetitivas permiten plantear soluciones sencillas, como consultar el estado de los envíos y generar alertas de retraso.
Además, facilita evaluar el impacto de las mejoras mediante indicadores como el tiempo de respuesta y el número de tareas manuales evitadas.

## Dos departamentos y problemas sencillos de solucionar

Los siguientes departamentos y problemas son propuestas a validar con el briefing completo de la empresa, no incidencias confirmadas.

| Departamento propuesto | Problema sencillo | Solución propuesta |
| --- | --- | --- |
| Atención al cliente | Consultar manualmente el estado de un envío para responder preguntas repetitivas. | Centralizar la consulta por identificador de envío y generar una respuesta con su estado actualizado. |
| Operaciones logísticas | Revisar uno a uno los envíos para detectar entregas fuera del plazo previsto. | Filtrar automáticamente los envíos pendientes cuya hora prevista de entrega ya haya pasado y avisar al responsable. |

## Reto de automatización

**Detectar y notificar envíos retrasados automáticamente.**

- **Entrada:** identificador del envío, estado, fecha y hora previstas de entrega y responsable operativo.
- **Flujo:** revisar periódicamente los envíos, detectar los que siguen pendientes después de su hora prevista y enviar una alerta al responsable.
- **Control:** registrar la alerta para evitar avisos duplicados del mismo retraso y dejar las decisiones de intervención al equipo humano.
- **Resultado esperado:** reducir las revisiones manuales y el tiempo entre la detección de un retraso y su comunicación.
- **Comprobación:** con datos de prueba, un envío pendiente fuera de plazo debe generar una única alerta; uno entregado o todavía dentro de plazo no debe generarla.