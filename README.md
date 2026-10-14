# PetMarket
**Curso:** Componentes de Lógica de Negocio  
**Profesor:** Miguel Ángel Gómez Marroquín  
**Facultad de Ingeniería Mecánica y Eléctrica (FIME), UANL**  

## Integrantes del Equipo 3:
* **Osmel De Jesús Pérez Carrizales** (Matrícula: 2157401)
* **José Osvaldo Barcenas González** (Matrícula: 2158657)
* **Gerzayn Flores Rodriguez** (Matrícula: 2160879)

## Descripción del Proyecto
Este repositorio contiene el diseño arquitectónico de **PetMarket**, una plataforma de comercio electrónico de comestibles y artículos para mascotas. En esta etapa (Unidad 3), convertimos los requerimientos del BRD y las 21 historias de usuario de la Unidad 2 en un diseño robusto basado en **Domain Model**, aplicando separación estricta de capas (Dominio, Aplicación e Infraestructura), patrones de persistencia (`Repository` y `Unit of Work`), CQRS básico y principios SOLID.

## Estructura del Repositorio
```text
PetMarket-Arquitectura/
│
├── docs/                      # Informes, ADRs, Matriz de Trazabilidad y Bitácoras de IA
├── diagrams/                  # Archivos fuente PlantUML (.puml) y diagramas gráficos
├── src/                       # Código fuente organizado por capas (Domain, Application, Infrastructure)
├── tests/                     # Casos de prueba e validación de reglas de negocio
└── README.md                  # Descripción general del repositorio
