# Proyecto ERP - Víveres y Licores La 74

## 1. Evaluar Ventajas y Desventajas

| Aspecto | Ventajas | Desventajas |
|---|---|---|
| **Técnico** | Se puede empezar simple (módulos básicos: inventario, ventas, gastos, nómina) e ir creciendo; no requiere integraciones complejas con sistemas externos al inicio | Requiere mantenimiento continuo (actualizaciones, backups, soporte); el equipo debe aprender a usarlo |
| **Relevancia del Problema** | El negocio maneja muchas categorías de producto con rotación distinta (una gaseosa rota rápido, un licor puede quedarse semanas), lo cual hoy probablemente se controla manualmente o en Excel, generando errores de stock y pérdidas | Si el proceso actual "funciona" aunque sea informal, puede haber resistencia al cambio por parte de quien lleva las cuentas hoy |
| **Valor Para el Usuario Final** | Permite saber en tiempo real qué hay en bodega, qué se está por acabar, cuánto se gasta y cuánto se gana por categoría; reduce pérdidas por vencimiento o robo hormiga | Curva de aprendizaje inicial para los empleados que hoy no usan sistemas digitales |
| **Financiero** | Bajo costo de desarrollo (proyecto académico/propio) vs. comprar un ERP comercial (Siigo, Alegra, SAP Business One) que cobra licencia mensual | El desarrollo toma tiempo y no genera valor inmediato hasta que esté terminado y en uso |
| **Control del Negocio** | Al ser un desarrollo propio, se ajusta 100% a cómo trabaja el negocio (venta por unidad, por paquete, por caja; productos con IVA vs. sin IVA como cigarrillos y licores) | Un ERP comercial ya viene probado y con soporte; el propio requiere que alguien lo mantenga después de terminado el curso |

---

## 2. Definición general del proyecto

### A. Definición del problema

La empresa **Víveres y Licores la 74**, dedicada a la venta de víveres, bebidas, licores y cigarrillos, actualmente no cuenta con un sistema centralizado para el control de inventario, costos, gastos y nómina de empleados. Esto genera:

- Desconocimiento del stock real disponible en un momento dado.
- Dificultad para identificar qué productos generan más pérdida (vencimiento, robo, mal conteo).
- Falta de visibilidad sobre los gastos totales del negocio (servicios, nómina, compras) frente a los ingresos.
- Decisiones de compra a proveedores basadas en intuición y no en datos.

### B. Solución ofrecida

Un sistema **ERP (Enterprise Resource Planning)** que centralice:

- **Módulo de inventario:** registro de entradas y salidas de productos por categoría (víveres, licores, cigarrillos, gaseosas/jugos, mecatos), con alertas de stock mínimo.
- **Módulo de costos y ventas:** registro de precio de compra vs. precio de venta, cálculo de margen por producto/categoría.
- **Módulo de empleados:** control de horarios, turnos y costos de nómina asociados.
- **Módulo de gastos:** registro de gastos operativos del negocio (arriendo, servicios, transporte, etc.).

El producto esperado es una aplicación web/escritorio que permita al dueño (o encargado) del negocio tener, en un solo lugar, el estado real del inventario, las finanzas y el personal, sin depender de cuadernos o Excel dispersos.

### C. Justificación

Este proyecto vale la pena porque ataca un problema real y actual de la empresa familiar, que actualmente no cuenta con control centralizado de su inventario ni de sus finanzas. Al manejar múltiples categorías de producto con dinámicas distintas —víveres y mecatos con alta rotación, licores y cigarrillos de alto valor unitario, gaseosas y jugos perecederos— la falta de un sistema adecuado se traduce directamente en pérdidas económicas por vencimientos, mal conteo o robo hormiga.

Un ERP propio permitiría tomar decisiones basadas en datos reales sobre qué se vende más, qué se debe reabastecer y en qué se está gastando de más, siendo además una solución escalable que puede iniciar con lo esencial (inventario, ventas y gastos) e ir incorporando módulos adicionales, como facturación electrónica, más adelante.

### D. Usuario final

- **Dueños del negocio:** para ver el panorama general del negocio (ventas, gastos, ganancias).
- **Empleados/encargados de caja o bodega:** para registrar ventas y movimientos de inventario en el día a día.
- **Opcionalmente, a futuro:** proveedores, si se integra un módulo de pedidos automáticos según stock mínimo.

### E. Utilidad (retorno de inversión)

El retorno de inversión se logra mediante:

- **Reducción de pérdidas**, ya que productos como licores y cigarrillos (de alto valor) o perecederos (jugos, gaseosas) son fáciles de perder por mal conteo o vencimiento sin control.
- **Mejor negociación con proveedores**, al saber con certeza qué y cuánto se necesita comprar, evitando sobrestock o desabastecimiento.
- **Optimización del tiempo del personal**, que dejaría de hacer conteos manuales o llevar cuentas en papel.
- **Visibilidad financiera real**, permitiendo saber si el negocio está siendo rentable categoría por categoría (por ejemplo, si los licores dejan más margen que los mecatos, y ajustar estrategia de compra).
