# Examen Final: SQL — 15 de junio de 2026

**Universidad de Las Américas (UDLA)** · Facultad de Ingeniería y Negocios
Instituto de Matemáticas, Física y Estadística — Área de Estadística
**Estudiante:** Pablo Villegas
**Dialecto:** T-SQL (SQL Server)

## Descripción

Resolución completa del Examen Final de SQL. El examen abarca cuatro problemas:

1. **SQL: JOIN y agregaciones** — sobre las tablas `CLIENTES` y `VENTAS`:
   - a) Mostrar nombre, ciudad y monto con `INNER JOIN`.
   - b) Total vendido por cliente (`SUM` + `GROUP BY`).
   - c) Cliente con la venta más baja (subconsulta con `MIN`).
2. **Data Warehouse y SQL analítico** — modelo en **esquema estrella**
   (`FACT_VENTAS`, `DIM_TIEMPO`, `DIM_PRODUCTO`) con ejemplo propio:
   ventas totales por año y ventas por categoría.
3. **Divisores de 21** — pseudocódigo, diagrama de flujo e implementación en SQL
   mediante un **CTE recursivo**, un procedimiento con bucle `WHILE` (`SP_DIVISORES`)
   y una **función con valores de tabla** (`FN_DIVISORES`).
4. **Esquema estrella vs. copo de nieve** — ejemplo propio (plataforma de
   *streaming* de música), ventajas/desventajas y consultas de alta complejidad
   con `SUM`, `AVG`, `MAX`, `MIN`, `HAVING` y **funciones de ventana**
   (`SUM() OVER (PARTITION BY ...)`).

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `Examen_Final_Pablo_Villegas.sql` | Script T-SQL completo con la solución de los 4 problemas (incluye `CREATE`, `INSERT` y todas las consultas). |
| `Examen_Final_Pablo_Villegas_Reporte.pdf` | Reporte del examen: enunciados, código, resultados esperados, diagrama de flujo y anexo con el SQL. |

> Nota: la sintaxis del script fue validada con el analizador de T-SQL (sqlglot).
> Los ejemplos de los problemas 2 y 4 son de elaboración propia, según lo pedido en el enunciado.
