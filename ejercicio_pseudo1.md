# Ejercicio 1:
Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

## Variables de entrada:

1. Cantidad de lápices

## Variables de salida:

1. Precio total

Inicio
Mostrar "Indique la cantidad de lápices"
Leer cantidad

Si cantidad <=1000
     precio_total = cantidad * 90
Si no:
     precio_total = cantidad * 85
Mostrar "El precio de [cantidad] de lápices es $[precio_total]"
Fin

# Ejercicio 2
Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.

## Variables de entrada:

1. Compra

## Variables de salida:

1. Precio total con descuento
2. Dinero ahorrado

Inicio
Mostrar "Indique el total de la compra para aplicar el descuento"

Si compra>=250000
    dinero_ahorrado = compra * 0,15
    precio_total = compra - dinero_ahorrado
Si no
    dinero_ahorrado = compra * 0,08
    precio_total = compra - dinero_ahorrado

Mostrar "El total de su compra es [precio_total] y ahorró un total de [precio_ahorrado]
fin

# Ejercicio 3
El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

## Variables de entrada:

1. Alumnos

## Variables de salida:

1. Precio

Inicio
Mostrar "Indique la cantidad de alumnos inscritos al viaje"

Si alumnos>=100
   precio = alumnos * 65
Si no:
    si alumnos >= 