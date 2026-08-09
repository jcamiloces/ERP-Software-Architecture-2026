# ERP Software Architecture - Víveres y Licores La 74

## 📌 Descripción del Proyecto

Este proyecto se enfoca en el análisis y diseño de la arquitectura de software para un sistema **ERP (Enterprise Resource Planning)** destinado a **Víveres y Licores La 74**.

Actualmente, el negocio no cuenta con un sistema centralizado para la gestión de inventario, ventas, costos, gastos y empleados. Esta situación puede generar errores de inventario, pérdidas económicas, falta de visibilidad financiera y decisiones de compra basadas en intuición y no en datos confiables.

El sistema ERP propuesto busca centralizar los principales procesos del negocio en una sola aplicación, brindando mejor control y acceso a información relevante para la toma de decisiones.

---

## 🎯 Objetivo del Proyecto

Diseñar una solución de software que permita a Víveres y Licores La 74 centralizar y mejorar la gestión de su inventario, ventas, costos, gastos y empleados.

El sistema busca reducir las pérdidas operativas, optimizar los procesos del negocio y brindar información confiable que soporte la toma de decisiones.

---

## ⚠️ Problema

Víveres y Licores La 74 maneja distintas categorías de productos con diferentes rotaciones, entre ellas:

- Víveres
- Bebidas alcohólicas (licores)
- Cigarrillos
- Gaseosas y jugos
- Mecatos

Actualmente, el negocio no cuenta con un sistema centralizado para el control de inventario, costos, gastos y nómina.

Esto puede generar problemas como:

- Desconocimiento del stock real disponible.
- Dificultad para identificar pérdidas de productos.
- Problemas causados por vencimiento, mal conteo o robo hormiga.
- Falta de visibilidad sobre los gastos totales del negocio.
- Decisiones de compra basadas en intuición y no en datos.
- Dependencia de cuadernos o archivos de Excel dispersos.

---

## 💡 Solución Propuesta

La solución propuesta es un sistema ERP que centraliza los principales procesos del negocio a través de diferentes módulos.

### Módulo de Inventario

- Registro de entradas y salidas de productos.
- Categorización de productos.
- Control de inventario.
- Alertas de stock mínimo.

### Módulo de Ventas y Costos

- Registro de precios de compra y venta.
- Gestión de ventas.
- Cálculo del margen de ganancia por producto y categoría.

### Módulo de Empleados

- Registro de empleados.
- Turnos y horarios de trabajo.
- Control de horas trabajadas.
- Gestión de costos asociados a la nómina.

### Módulo de Gastos

- Registro de gastos operativos.
- Gestión de gastos como arriendo, servicios, transporte y otros costos del negocio.

---

## 👥 Usuarios Finales

Los principales usuarios del sistema propuesto son:

### Dueños del negocio

Podrán monitorear:

- Ventas.
- Gastos.
- Ganancias.
- Inventario.
- Desempeño general del negocio.

### Empleados y encargados de caja o bodega

Usarán el sistema para actividades diarias como:

- Registrar ventas.
- Registrar movimientos de inventario.
- Consultar disponibilidad de productos.

### Usuarios futuros

Los proveedores podrían interactuar con el sistema en el futuro si se implementa una funcionalidad de pedidos automáticos basada en niveles mínimos de stock.

---

## 📈 Beneficios Esperados

Se espera que el sistema propuesto brinde los siguientes beneficios:

- Reducción de pérdidas de inventario.
- Mejor control de productos de alto valor y perecederos.
- Mejores decisiones de compra.
- Mejor negociación con proveedores.
- Reducción del tiempo dedicado al control manual de inventario.
- Mayor visibilidad de las finanzas del negocio.
- Mejor toma de decisiones basada en datos confiables.
- Posibilidad de ampliar progresivamente el sistema con nuevas funcionalidades.

---

## 📂 Documentación del Proyecto

La documentación del proyecto está organizada de la siguiente manera:

```text
Docs/
│
├── 01-definicion-proyecto/
│   └── Definicion_proyecto.md
│
└── 02-requerimientos/
    ├── Arbol_Funcional.md
    ├── Requerimientos_funcionales.md
    └── Requerimientos_no_funcionales.md
```

A medida que el proyecto avance, se irá agregando documentación adicional según las actividades y requerimientos del laboratorio.

---

## 🛠️ Estado del Proyecto

**Etapa actual:** Definición del proyecto y análisis de requerimientos.

La documentación actual incluye:

- Evaluación de ventajas y desventajas.
- Definición del problema.
- Solución propuesta.
- Justificación del proyecto.
- Usuarios finales.
- Utilidad esperada y retorno de inversión.
- Descomposición funcional.
- Requisitos funcionales.
- Requisitos no funcionales.

---

## 👨‍💻 Proyecto

**Proyecto:** ERP para Víveres y Licores La 74
**Asignatura:** Arquitectura de Software
**Curso:** A1
**Repositorio:** ERP-Software-Architecture-2026

### Integrantes

- Brayhan Alexander Suárez Merchán
- Juan Camilo Céspedes Correal
- Juan Camilo Zabala Cerón
- David Felipe Moreno García