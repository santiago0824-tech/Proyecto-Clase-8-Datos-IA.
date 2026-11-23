# Proyecto · Clase 8 · Ana encuentra qué esconde un total estable

**8 · Datos con IA · Rol: Ana (Ventas)**

## 1. Calidad de la tabla

Durante la revisión de los datos de ventas de julio, agosto y septiembre encontré los siguientes problemas:

| Folio / dato | Problema | Acción realizada |
|---|---|---|
| V-3106 | La región aparece como `norte` en minúscula. | Corregí el formato a `Norte` para mantener uniformidad. |
| V-3127 | El monto de la venta está vacío. | Lo dejé por confirmar, ya que no se conoce el monto real. |
| V-3140, V-3144, V-3145, V-3148 y otros | El vendedor aparece como `Sin asignar`. | Lo dejé por confirmar, porque no se conoce quién realizó esas ventas. |
| V-3151 | El monto registrado es de $301,000, muy superior a los demás registros. | Lo dejé por confirmar, ya que podría ser un error de captura. |
| V-3160 | El mismo registro aparece duplicado. | Excluí una copia del análisis para evitar contar la venta dos veces. |

## 2. Gráfica de ventas

Se elaboró una gráfica de barras agrupadas para comparar las ventas de las cuatro regiones durante julio, agosto y septiembre. Se resaltó la región Norte, ya que presenta una caída importante en septiembre.

- **Tipo de gráfica:** Barras agrupadas.
- **Título:** Norte cae fuertemente en septiembre tras depurar registros.
- **Eje vertical:** Ventas en pesos mexicanos (MXN), comenzando desde cero.
- **Qué se resalta:** La disminución de ventas de la región Norte en septiembre respecto a los meses anteriores.

Para la comparación se excluyó provisionalmente el monto de $301,000 del folio V-3151 y una copia del folio V-3160.

## 3. Párrafo para la dirección

Durante julio, agosto y septiembre de 2026, se analizaron las ventas de Distribuidora Solmar a partir de la tabla proporcionada. Aunque los totales pueden parecer relativamente estables, la región Norte pasó de $183,600 en agosto a $46,500 en septiembre, una disminución importante. Se recomienda que Ana revise con el equipo comercial de Norte las causas de esta caída durante la próxima semana y compare los resultados al cierre del siguiente periodo para evaluar si hubo una mejora.

## 4. Dato y suposición

### Datos obtenidos de la tabla
- Norte registró $257,600 en julio.
- Norte registró $183,600 en agosto.
- Norte registró $46,500 en septiembre, después de la depuración provisional.
- El folio V-3151 registra un monto de $301,000.
- El folio V-3160 aparece duplicado.

### Suposiciones
- La caída de Norte podría relacionarse con cambios en la actividad comercial, clientes o vendedores, pero la tabla no explica las causas.
- El monto de $301,000 podría ser un error de captura, aunque no se puede asegurar.
- Los registros con vendedor `Sin asignar` podrían dificultar el seguimiento comercial.

## 5. Revisión de cifras

Para comprobar que la gráfica coincidiera con la tabla, comparé los siguientes datos:

- **Norte en agosto:** $183,600, coincide con la suma de los registros de agosto para esa región.
- **Norte en septiembre:** $46,500, coincide con la suma de los registros de septiembre de Norte.
- **Centro en septiembre:** $292,400, después de excluir provisionalmente el monto de $301,000 y una copia de $33,100.

## Conclusión

En este proyecto pude identificar que un total aparentemente estable puede esconder cambios importantes entre regiones. Al revisar los datos y elaborar una gráfica, encontré que la región Norte presenta una caída considerable en septiembre, por lo que sería importante investigar sus causas. También detecté problemas de calidad en la tabla que deben verificarse antes de tomar decisiones definitivas.

Para realizar este análisis utilicé inteligencia artificial como apoyo para organizar, analizar e interpretar los datos, además de Markdown y GitHub para estructurar y compartir el proyecto.
