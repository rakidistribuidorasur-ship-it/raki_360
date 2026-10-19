# Arquitectura propuesta de Raki 360

## Capas
1. Sitio web público actual (HTML/CSS/JS), sin migración inmediata a React.
2. Capa de integración/API con autenticación, autorización y validaciones.
3. Odoo Community: contactos, catálogo, ventas e inventario según módulos y versión seleccionados.
4. PostgreSQL: almacenamiento persistente administrado por Odoo.

## Módulos personalizados candidatos
- **raki_packaging**: composición de tablas gourmet o packs con cantidades y unidades, cálculo de costo, precio y disponibilidad.
- Exportaciones programables de listados de productos, pedidos e inventario; la periodicidad se definirá con Javier.
- Reglas de comisiones: por definir, sin porcentajes supuestos.

## Seguridad y operación
No exponer credenciales ni la base de datos en el Front-end. Separar entornos de desarrollo y producción. Controlar permisos por rol, validar entradas, registrar cambios relevantes y respaldar datos.

## Decisiones pendientes
Versión exacta de Odoo; hosting; método de API; flujo de compras/abastecimiento; precios por kilo; reglas de comisiones; impuestos, despacho y periodicidad de exportación.
