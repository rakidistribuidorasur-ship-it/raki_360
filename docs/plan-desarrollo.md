# Plan incremental de desarrollo

## Fase 0 — Validación
Confirmar versión de Odoo Community, compatibilidad de módulos, hosting, roles y alcance con Javier. Revisar el repositorio y preservar la web actual.

## Fase 1 — Base operativa
Configurar Odoo + PostgreSQL en entorno de desarrollo; productos, categorías, unidades de medida, proveedores y clientes. Probar registros y permisos.

## Fase 2 — Paquetización
Prototipo de packs gourmet: componentes, cantidades por kilo/unidad, cálculo de costos, precio de venta y validación de disponibilidad.

## Fase 3 — Pedidos e inventario
Vincular packs con pedidos, reservas y movimientos de inventario. Probar cambios de estado, cancelaciones y devoluciones.

## Fase 4 — Integración y panel
Definir API segura para la web existente y panel administrativo; diseñar flujos UX/UI en Figma. No migrar a React sin decisión explícita.

## Fase 5 — Reportes y automatizaciones
Exportar listas CSV/XLSX con filtros; definir periodicidad. Comisiones solo después de acordar las reglas comerciales.

## Criterios de avance
Pruebas con datos ficticios, permisos correctos, cálculos reproducibles y respaldo antes de desplegar. No se ha realizado instalación ni despliegue.
