---
cssclasses:
  - recurso-portafolio
---
# Mapa del módulo

[[index|← Volver a inicio]]

El módulo se divide en dos partes: primero se revisan los fundamentos, la evolución de las metodologías y RUP; después se profundiza en las etapas del **modelo en cascada**. Este esquema permite ubicar cada tema y pasar directamente a su ficha.

```mermaid
flowchart TB
 subgraph A["Fundamentos y evolución"]
  C01["01 Introducción"] --> C02["02 Modelos"]
  C02 --> C03["03 Enfoques"]
  C03 --> C04["04 RUP: inicio"]
  C04 --> C05["05 RUP: fases"]
 end
 subgraph B["Modelo en cascada"]
  C06["06 Requisitos"] --> C07["07 Diseño y UML"]
  C07 --> C08["08 Implementación"]
  C08 --> C09["09 Pruebas"]
  C09 --> C10["10 Despliegue y mantenimiento"]
 end
 C05 -.-> C06
```

## Relación conceptual entre bloques

Las primeras cinco fichas permiten comparar distintas formas de organizar el desarrollo. Las últimas cinco muestran, con mayor detalle, cómo se estructura uno de esos modelos: **cascada**, desde la definición de requisitos hasta el mantenimiento.
