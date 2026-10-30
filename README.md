# Laboratorio: evaluación de riesgos y controles de TI

Laboratorio práctico para identificar, valorar y tratar riesgos de TI en una pequeña empresa ficticia. Está pensado para practicar y publicar como repositorio educativo en GitHub.

> **Aviso:** la empresa, las personas, los activos, las evidencias y los resultados incluidos son totalmente ficticios. No representan una evaluación real ni deben usarse como evidencia de auditoría.

## Caso

**NubeNorte Tienda**, tienda ficticia de artículos para oficina con 12 personas. Usa una plataforma de comercio electrónico en la nube, correo corporativo, una aplicación de inventario y notebooks Windows. La dueña también administra usuarios; no hay equipo formal de TI. La tienda procesa datos de contacto y direcciones de clientes, además de pedidos y pagos gestionados por el proveedor de la plataforma.

## Objetivos de aprendizaje

- Describir activos, amenazas, vulnerabilidades y consecuencias.
- Valorar probabilidad e impacto con una escala común.
- Priorizar riesgos inherentes y residuales.
- Proponer controles preventivos, detectivos y correctivos.
- Documentar evidencia ficticia y comunicar hallazgos ejecutivos.

## Archivos

- `matriz_riesgos.csv`: matriz editable que abre en Excel. Incluye cinco riesgos obligatorios y fórmulas de puntuación/nivel para Excel en español.
- `plantilla_informe.md`: estructura para entregar el informe ejecutivo.
- `evidencias-ficticias/`: muestras inventadas para practicar el análisis documental.

## Instrucciones

1. Lee el caso y las evidencias. Mantén presente que son simuladas.
2. Revisa los cinco riesgos precargados: contraseñas débiles, falta de copias de seguridad, permisos excesivos, equipos desactualizados y ausencia de registros.
3. Ajusta las descripciones, probabilidad e impacto usando la escala del apartado siguiente. Justifica cada valoración con la evidencia del caso.
4. Propón controles concretos, un responsable y una fecha objetivo. Estima el riesgo residual después del control propuesto.
5. Completa el informe y explica qué riesgos requieren atención inmediata.
6. Si subes cambios a GitHub, conserva la etiqueta de datos ficticios. No agregues secretos, datos personales ni capturas de sistemas reales.

## Escala de valoración

Asigna probabilidad e impacto de 1 a 5. Puntuación = probabilidad × impacto.

| Valor | Probabilidad | Impacto |
|---|---|---|
| 1 | Rara | Insignificante; interrupción menor a 1 hora o efecto limitado |
| 2 | Improbable | Menor; recuperación sencilla y sin efecto material en clientes |
| 3 | Posible | Moderado; interrupción de varias horas o exposición limitada |
| 4 | Probable | Mayor; pérdida de ventas, exposición relevante o recuperación compleja |
| 5 | Casi segura | Crítico; interrupción prolongada, pérdida importante o impacto legal/reputacional |

**Bandas sugeridas:** 1–4 Bajo, 5–9 Moderado, 10–16 Alto, 17–25 Crítico. El nivel es una guía de priorización; documenta cualquier excepción. Riesgo inherente es antes del control nuevo. Riesgo residual es el estimado una vez implementado y operando el control.

## Entregables del estudiante

1. Matriz completada con valoración inherente y residual.
2. Evidencia citada por nombre de archivo y observación; no se exige evidencia real.
3. Informe ejecutivo con alcance, método, resultados, acciones priorizadas y limitaciones.
4. (Opcional) Un README actualizado con decisiones y aprendizajes.

## Criterios de evaluación (100 puntos)

- Identificación y descripción de cinco riesgos (20).
- Valoraciones coherentes y justificadas (20).
- Controles específicos, viables y asociados a responsables (25).
- Estimación residual razonada (15).
- Informe claro, priorizado y con limitaciones explícitas (15).
- Manejo correcto de la naturaleza ficticia de los datos (5).

## Cómo usar en GitHub

Crea un repositorio público o privado, agrega estos archivos y publica el README como página inicial. No incluyas información real de una organización. Para trabajo colaborativo, cada participante puede proponer cambios mediante una rama y un pull request.

## Limitaciones

Este ejercicio simplifica la gestión de riesgos y no reemplaza una evaluación profesional, una revisión de cumplimiento ni un análisis técnico. Las escalas y bandas son didácticas, no un estándar obligatorio.
