# Lista de casos de uso - Sistema de Punto de Venta (Grupo N&N)

## 1) Administración y seguridad

1. **Autenticación y gestión de usuarios**  
   Inicio de sesión, alta/baja/modificación de usuarios con roles y permisos según módulos habilitados.

2. **Configurar organización y sucursales**  
   Alta y mantenimiento de organizaciones (CUIT, rubros, servicios) y sus sucursales con dirección y encargado.

## 2) Clientes

3. **Registrar y gestionar clientes**  
   Alta de cliente con validación de teléfono por API externa, modificación, baja lógica y consulta por DNI/CUIT.

## 3) Productos y stock

4. **Gestionar productos y categorías**  
   Alta/mantenimiento de productos (código, marca, modelo, proveedor, precio) y categorización.

5. **Administrar stock**  
   Registro de recepción de mercadería, actualización de existencias y consulta de histórico de movimientos.

## 4) Ventas y facturación

6. **Registrar venta**  
   Crear transacción con cajero, sucursal, cliente, productos, cantidades y precios.

7. **Aplicar promociones y descuentos**  
   Crear combos, aplicar descuentos con prorrateo proporcional sobre precios base.

8. **Calcular impuestos y total**  
   Determinar alícuota IVA por ítem (21% o 10.5%), prorratear en combos, calcular con precisión de 2 decimales.

9. **Emitir factura**  
   Generar comprobante fiscal (tipo A/B según condición fiscal), registrar medio de pago y versionado de alícuotas.

10. **Emitir nota de crédito**  
    Anular o corregir venta (total o parcial) respetando alícuota e impuesto del comprobante original.

## 5) Créditos a sola firma

11. **Solicitar y gestionar crédito**  
    Solicitud de crédito, integración con sistema externo para validación, registro de resultado (aprobado/rechazado/pendiente).

12. **Generar contrato y seguimiento**  
    Emitir contrato de crédito aprobado y permitir consulta de estado de solicitudes.

## 6) Reportes y análisis

13. **Generar reportes de ventas**  
    Consolidado por sucursal, período, vendedor, tipo de operación y medios de pago utilizados.

14. **Generar reportes de productos**  
    Top vendidos, menos vendidos y rotación de inventario por sucursal y período.

15. **Calcular comisiones y bonos**  
    Bono vendedor (10% ventas + 3% por crédito aprobado) y bono encargado (15% ventas de sucursal).

---

## Resumen

**15 casos de uso esenciales** agrupados en 6 dominios, cubriendo: administración, clientes, stock, ventas/facturación, créditos e impuestos, y análisis comercial.
