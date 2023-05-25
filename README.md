# Maco Wins

## Enunciado

Se requiere:
- Identificar los requerimientos
- Presentar una solución usando el paradigma de objetos (pseudocódigo, diagrama de clases).
- Explicar todo lo que considere necesario en prosa.
- Si se descarta alguna alternativa durante el desarrollo de la solución, o si se tiene otra solución, explicarla brevemente.

La conocida empresa de ropa formal para caballeros, Macowins, es capaz de darle soporte a la
venta de prendas. Un fragmento de la grabación del analista con el cliente:

    “Queremos saber el precio de venta de una prenda y sus tipos, los tipos de prenda son: sacos, pantalones, camisas.”

El cálculo del precio de una prenda es, el precio propio de la prenda modificado según el
estado de la prenda, que pueden ser:
- Nueva: en este caso no modifican el precio base.
- Promoción: Le resta un valor fijo decidido por el usuario.
- Liquidación: Es un 50% del valor del producto.

Ah, un requerimiento más: Macowins registra las ventas de estas prendas y necesita saber las
ganancias de un determinado día.

    “Cada venta tiene asociada las prendas que se vendieron, su cantidad y la fecha de venta.
    Las ventas pueden ser en efectivo o con tarjeta. En el caso que sea con tarjeta, tienen el
    mismo comportamiento que en efectivo (el cual no modifica el precio), sólo que se le aplica un
    recargo según la cantidad de cuotas seleccionadas (cantidad de cuotas * un coeficiente fijo +
    0.01 del valor de cada prenda).”

## Solución

![](./classDiagram.png)
![](https://user-images.githubusercontent.com/38950204/240790237-cf1599b9-913f-430b-9489-658ef9016743.svg)
