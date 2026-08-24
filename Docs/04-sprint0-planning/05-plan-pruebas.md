# 5. Plan de Pruebas

Casos de prueba definidos para cada historia de usuario del Sprint 1.

## US02 – Registrar categorías de producto

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Registrar categoría con nombre válido | Se registra correctamente |
| CP02 | Registrar categoría sin nombre | El sistema muestra error de campo obligatorio |
| CP03 | Registrar categoría con nombre repetido | El sistema rechaza el registro |
| CP04 | Registrar categoría con nombre muy largo (ej. 300 caracteres) | El sistema muestra error de validación |
| CP05 | Consultar listado de categorías registradas | Muestra todas las categorías existentes |

## US01 – Registrar productos

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Registrar producto con todos los datos válidos | Se registra correctamente |
| CP02 | Registrar producto sin nombre | El sistema muestra error |
| CP03 | Registrar producto sin categoría asociada | El sistema rechaza el registro |
| CP04 | Registrar producto con precio de compra negativo | El sistema muestra error de validación |
| CP05 | Registrar producto con categoría inexistente | El sistema rechaza el registro |
| CP06 | Registrar producto con datos válidos completos | Muestra mensaje de confirmación |

## US09 – Definir precios de venta

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Asignar precio de venta válido a un producto existente | Se guarda correctamente |
| CP02 | Asignar precio de venta igual a cero | El sistema muestra error |
| CP03 | Asignar precio de venta negativo | El sistema rechaza el valor |
| CP04 | Asignar precio a un producto inexistente | El sistema muestra error |
| CP05 | Actualizar el precio de venta de un producto ya definido | El precio se actualiza correctamente |

## US03 – Registrar entradas de inventario

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Registrar entrada con producto y cantidad válidos | Se registra correctamente y actualiza el stock |
| CP02 | Registrar entrada de un producto inexistente | El sistema muestra error |
| CP03 | Registrar entrada con cantidad igual a cero | El sistema rechaza el registro |
| CP04 | Registrar entrada con cantidad negativa | El sistema muestra error de validación |
| CP05 | Verificar que el stock aumente correctamente tras la entrada | El stock refleja la cantidad ingresada |

## US04 – Registrar salidas de inventario

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Registrar salida con stock suficiente | Se registra correctamente y descuenta el stock |
| CP02 | Registrar salida con cantidad mayor al stock disponible | El sistema muestra error y rechaza el registro |
| CP03 | Registrar salida con cantidad igual a cero | El sistema rechaza el registro |
| CP04 | Registrar salida de un producto inexistente | El sistema muestra error |
| CP05 | Verificar que el stock disminuya correctamente tras la salida | El stock refleja la cantidad descontada |

## US05 – Consultar stock actual

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Consultar stock de un producto existente | Muestra la cantidad actual correctamente |
| CP02 | Consultar stock filtrando por categoría | Muestra solo los productos de esa categoría |
| CP03 | Buscar un producto por nombre | Muestra el producto correspondiente |
| CP04 | Buscar un producto que no existe | El sistema muestra "sin resultados" |
| CP05 | Consultar producto con stock por debajo del mínimo | El sistema muestra indicador visual de alerta |

## US07 – Registrar compras a proveedores

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Registrar compra con proveedor, producto, cantidad y costo válidos | Se registra correctamente |
| CP02 | Registrar compra sin proveedor | El sistema muestra error |
| CP03 | Registrar compra con cantidad igual a cero | El sistema rechaza el registro |
| CP04 | Registrar compra con costo negativo | El sistema muestra error de validación |
| CP05 | Verificar que se genere la entrada de inventario automáticamente | El stock del producto aumenta según la compra |

## US16 – Registrar gastos operativos

| ID | Caso | Resultado esperado |
|---|---|---|
| CP01 | Registrar gasto con concepto, monto y fecha válidos | Se registra correctamente |
| CP02 | Registrar gasto sin concepto | El sistema muestra error |
| CP03 | Registrar gasto con monto negativo | El sistema rechaza el registro |
| CP04 | Registrar gasto con fecha futura | El sistema muestra error de validación |
| CP05 | Registrar gasto con datos válidos completos | Muestra mensaje de confirmación |
