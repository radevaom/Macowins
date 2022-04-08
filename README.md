# Macowins
Ejercicio Macowins dds

Requerimientos:
  *Funcionales:
              -Conocer precio de venta de una prenda
              -Conocer los tipos de una prenda
              -Conocer las ganancias de un determinado día
              -Registrar cada venta
  *No Funcionales:
              -El calculo del precio de una prenda:
                .Si es nueva no se modifica su precio base
                .Si esta en promocion se le resta un valor fijo puesto por el user
                .Si esta en liquidacion es un 50% del valor base
               -Se puede pagar en tarjeta o en efectivo:
                .Efectivo no modifica precio
                .arjeta aplica recargo (cantidad de cuotas * un coeficiente fijo + 0.01 del valor de cada prenda)
               -La venta esta conformada por las prendas que se vendieron, su cantidad y la fecha de la misma
