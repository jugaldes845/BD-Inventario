# BD-Inventario

| Supuesto | Nombre               | Tipo | Intensión | Extensión | Obligatorio | Pertenece a |
|----------|----------------------|------|-----------|-----------|-------------|-------------|
| 1        | IDproveedor          | AIP  | NUMBER    | 1-N       | Sí          | Proveedor   |
| 2        | nombre               | A    | VARCHAR2  | A-Z       | Sí          | Proveedor   |
| 3        | contacto             | A    | NUMBER    | A-Z       | Sí          | Proveedor   |
| 4        | categoría            | A    | VARCHAR2  | A-Z       | Sí          | Proveedor   |
| 5        | cuenta               | A    | VARCHAR2  | A-Z       | Sí          | Proveedor   |
| 6        | estado               | A    | VARCHAR2  | A-Z       | Sí          | Proveedor   |
| 7        | fecha_inicio         | A    | DATE      | A-Z       | Sí          | Proveedor   |
| 8        | IDcompra             | AIP  | NUMBER    | 1-N       | Sí          | Compra      |
| 9        | fecha_compra         | A    | DATE      | A-Z       | Sí          | Compra      |
| 10       | total                | A    | NUMBER    | A-Z       | Sí          | Compra      |
| 11       | método_pago          | A    | VARCHAR2  | A-Z       | Sí          | Compra      |
| 12       | estado               | A    | VARCHAR2  | A-Z       | Sí          | Compra      |
| 13       | factura              | A    | VARCHAR2  | A-Z       | Sí          | Compra      |
| 14       | fecha_entrega        | A    | DATE      | A-Z       | Sí          | Compra      |
| 15       | observación          | A    | VARCHAR2  | A-Z       | No          | Compra      |
| 16       | IDbodega             | AIP  | NUMBER    | 1-N       | Sí          | Bodega      |
| 17       | nombre               | A    | VARCHAR2  | A-Z       | Sí          | Bodega      |
| 18       | tipo                 | A    | VARCHAR2  | A-Z       | Sí          | Bodega      |
| 19       | responsable          | A    | VARCHAR2  | A-Z       | Sí          | Bodega      |
| 20       | código_barras        | A    | NUMBER    | A-Z       | Sí          | Bodega      |
| 21       | regulaciones         | A    | VARCHAR   | A-Z       | No          | Bodega      |
| 22       | historial_reabast    | A    | VARCHAR   | A-Z       | No          | Bodega      |
| 23       | fecha_vencimiento    | A    | DATE      | A-Z       | Sí          | Bodega      |
| 24       | rotación_inventario  | A    | VARCHAR2  | A-Z       | Sí          | Bodega      |
| 25       | registro_salidas     | A    | VARCHAR2  | A-Z       | Sí          | Bodega      |
| 26       | registro_devoluciones| A    | VARCHAR2  | A-Z       | Sí          | Bodega      |
| 27       | nivel_stock_mínimo   | A    | NUMBER    | A-Z       | Sí          | Bodega      |
| 28       | código               | AIP  | NUMBER    | 1-N       | Sí          | Inventario  |
| 29       | lote                 | A    | NUMBER    | A-Z       | Sí          | Inventario  |
| 30       | descripción          | A    | VARCHAR2  | A-Z       | Sí          | Inventario  |
| 31       | cantidad             | A    | NUMBER    | A-Z       | Sí          | Inventario  |
| 32       | precio_u             | A    | NUMBER    | A-Z       | Sí          | Inventario  |
| 33       | fecha_vencimiento    | A    | DATE      | A-Z       | Sí          | Inventario  |
| 34       | ubicación            | A    | VARCHAR2  | A-Z       | Sí          | Inventario  |
| 35       | IDbodega             | A    | NUMBER    | A-Z       | Sí          | Inventario  |
| 36       | IDcompra             | A    | NUMBER    | A-Z       | Sí          | Inventario  |
| 37       | IDmovimiento         | AIP  | NUMBER    | 1-N       | Sí          | Movimiento  |
| 38       | código               | A    | NUMBER    | A-Z       | Sí          | Movimiento  |
| 39       | lote                 | A    | NUMBER    | A-Z       | Sí          | Movimiento  |
| 40       | tipo_movimiento      | A    | VARCHAR2  | A-Z       | Sí          | Movimiento  |
| 41       | fecha_salida         | A    | DATE      | A-Z       | No          | Movimiento  |
| 42       | fecha_entrada        | A    | DATE      | A-Z       | Sí          | Movimiento  |
| 43       | fecha_devolución     | A    | DATE      | A-Z       | No          | Movimiento  |
| 44       | destino              | A    | VARCHAR2  | A-Z       | Sí          | Movimiento  |
| 45       | existencia           | A    | NUMBER    | A-Z       | Sí          | Movimiento  |
| 46       | proveedor            | A    | VARCHAR2  | A-Z       | Sí          | Movimiento  |
| 47       | responsable          | A    | VARCHAR2  | A-Z       | No          | Movimiento  |
| 48       | estado               | A    | VARCHAR2  | A-Z       | Sí          | Movimiento  |
| 49       | motivo               | A    | VARCHAR2  | A-Z       | Sí          | Movimiento  |
