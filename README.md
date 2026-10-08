# Proyecto 1 · Analítica académica ITACA (origen XML)


## Descripción y objetivo

Construir un dashboard de análisis académico en Power BI a partir de datos reales de la plataforma ITACA de la Conselleria de Educación, extraídos como ficheros XML.

## Arquitectura

*Diagrama del pipeline completo. Empieza con uno provisional en el Bloque 0 y actualízalo al terminar cada bloque.*

```mermaid
graph LR
    A[XML ITACA] --> B[Ingesta]
    B --> C[BDD MongoDB]
    C --> D[Spark]
    D --> E[Power BI]

```
