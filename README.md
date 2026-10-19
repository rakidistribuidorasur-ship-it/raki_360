# Raki 360

Sistema de gestión comercial y operativa de Raki Distribuidora. **Estado: planificación técnica; no hay Back-end implementado todavía.**

## Arquitectura propuesta
- Odoo Community como núcleo de gestión y lógica de negocio.
- PostgreSQL como base de datos de Odoo (sin MySQL).
- Web existente HTML/CSS/JavaScript: mantener sin cambios por ahora.
- Integración mediante API autenticada; nunca conectar el navegador directamente a PostgreSQL.

## Alcance
Productos, proveedores, clientes, pedidos, inventario, paquetización gourmet, exportaciones periódicas y reportes. Comisiones: estructura pendiente de definición.

## Documentación
- [Arquitectura](docs/arquitectura.md)
- [Modelo de datos](docs/modelo-entidad-relacion.md)
- [Plan de desarrollo](docs/plan-desarrollo.md)

> Las entidades descritas son conceptuales. Antes de crear tablas o módulos se revisarán los modelos estándar de la versión de Odoo elegida.
