# Ejecución del Sprint 1 — ERP La 74

## Resumen

Este documento presenta la documentación del Sprint 1 del proyecto ERP La 74, ejecutado bajo la metodología Scrum. El sprint tuvo una duración de dos semanas (23 de agosto – 6 de septiembre de 2026) y se enfocó en la base funcional del sistema: registro de categorías, productos, precios, movimientos de inventario, compras a proveedores y gastos operativos.

Se ejecutaron ocho historias de usuario, con un total de 29 Story Points estimados mediante Planning Poker. La ejecución integró Jira como gestor de proyecto y tablero Scrum, y GitHub para control de versiones del código Laravel/MySQL del sistema.

## Introducción

Este proyecto se desarrolla en el contexto del curso de Arquitectura de Software de la Facultad de Ingeniería de la Universidad Manuela Beltrán. El ERP La 74 centraliza los procesos de inventario, ventas, costos, gastos y empleados de la empresa Víveres y Licores La 74, siguiendo la metodología Scrum en ciclos cortos (sprints) de dos semanas.

### Objetivos principales del Sprint 1

1. **Implementar la base funcional del sistema**: categorías, productos, precios de venta, entradas y salidas de inventario, compras a proveedores y gastos operativos — el MVP del módulo de inventario y costos.
2. **Aplicar el patrón MVC de Laravel** y los estándares de codificación acordados por el equipo.
3. **Documentar la arquitectura del sistema** (vistas lógica, física y de desarrollo, y árbol de descomposición funcional), ya disponible en la documentación del proyecto.
4. **Garantizar calidad mediante pruebas**: casos de prueba definidos para cada historia de usuario, con revisión de código antes de integrar cambios.
5. **Aplicar prácticas de colaboración**: uso de GitHub para control de versiones, revisión por pares (pull requests) y documentación técnica actualizada en Jira y en el repositorio.

## Fase 0: Preparación y Configuración

### Jira — Gestor de Proyecto

Se configuró un proyecto de Jira ("Mi equipo de trabajo") con tablero Scrum, donde se documentó el Product Backlog completo (23 historias de usuario) y se organizó el Sprint 1 con sus ocho historias correspondientes.

### GitHub — Control de Versiones

Se creó el repositorio del proyecto, con todos los integrantes del equipo vinculados como colaboradores. El código del backend en Laravel y la base de datos en MySQL se versionan mediante commits regulares, con revisión de código (pull request aprobado por al menos un integrante distinto al autor) antes de integrar cambios a la rama principal.

### Documentación de Arquitectura

La documentación arquitectónica del proyecto (vista lógica, vista física, vista de desarrollo y árbol de descomposición funcional) se mantiene en formato Markdown dentro del repositorio y se publica en la página de documentación del proyecto (GitHub Pages), cumpliendo con el requisito de trazabilidad y acceso a la documentación.

## Fase 1: Sprint Planning

Del Product Backlog se seleccionaron ocho historias de usuario correspondientes a la base funcional del sistema, sumando 29 Story Points — alcance considerado adecuado para la capacidad del equipo durante las dos semanas del sprint.

![Sprint 1 - Resumen del backlog en Jira](../images/sprint1-backlog-resumen.png)

| Historia | Descripción | Story Points |
|---|---|---|
| US02 | Registrar categorías de producto | 2 |
| US01 | Registrar productos | 3 |
| US09 | Definir precios de venta | 3 |
| US03 | Registrar entradas de inventario | 5 |
| US04 | Registrar salidas de inventario | 5 |
| US05 | Consultar stock actual | 3 |
| US07 | Registrar compras a proveedores | 5 |
| US16 | Registrar gastos operativos | 3 |
| **Total** | | **29** |

Cada historia fue especificada siguiendo la estructura *"Como \<tipo de usuario\>, quiero \<objetivo\>, para que \<beneficio\>"*, con mínimo 5 criterios de aceptación medibles y verificables, y descompuesta en tareas técnicas concretas (diseño, modelado, migración de base de datos, lógica de negocio, validaciones, pruebas e integración) registradas como subtareas en Jira.

## Fase 2: Ejecución del Sprint

Durante la ejecución se aplicaron las siguientes prácticas de forma continua:

- **Desarrollo en Laravel**: cada historia se implementó siguiendo el patrón MVC, con modelos, migraciones, controladores y vistas Blade correspondientes.
- **Control de versiones en GitHub**: los cambios de cada historia se integraron mediante commits descriptivos y revisión de código antes del merge a la rama principal.
- **Seguimiento diario**: avance de las historias reflejado en el tablero de Jira, según el cronograma del sprint (ver responsabilidades y cronograma en la documentación de gestión ágil del proyecto).
- **Pruebas**: ejecución de los casos de prueba definidos para cada historia (ver Plan de Pruebas), validando tanto los flujos correctos como los casos de error (validaciones de campos obligatorios, valores negativos, duplicados, etc.).

El detalle completo de las historias, sus criterios de aceptación, tareas y evidencia de ejecución se encuentra documentado en Jira y en el repositorio del proyecto.