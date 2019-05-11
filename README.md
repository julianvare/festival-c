# festival-c
Ejercicio en lenguaje C

Se realiza un festival de música durante 3 días y no se pueden vender más de 5000 entradas por día. Los datos a considerar para la venta de cada boleto son los siguientes: día del festival, ubicación, precio y número de ticket.
Día del festival: 1, 2, 3.	
Ubicación: cam (campo 3500 entradas max por día), pla (platea 1000 entradas max por día), pac(palco 500 entradas max por día).		
Precios: cam = $60, pla = $80, pac = $120.		
Numero de Ticket = 1,2,3,4,5, …n.  Números correlativos para cada ticket que se vende arrancando en 1.

Se pide: 
Desarrollar un programa en lenguaje c, que permita vender entradas.
Para cada venta debe solicitar al usuario la ubicación a adquirir y el día, y le devuelve el nro. de ticket y el precio en caso de que haya lugar para esa ubicación, en caso que no haya lugar le devuelve un mensaje indicándoselo.
El programa debe preguntarle al usuario si desea continuar vendiendo entradas o si termina de vender entradas.
Cuando el usuario decida terminar de vender entradas, el programa deberá informar lo siguiente: 
Cantidad de entradas campo vendidas del día 3.
Total de entradas vendidas los tres días y total recaudado.

Nota:
Para obtener el número de ticket se debe efectuar mediante una función que devuelve el nro. de ticket a vender.
Para informar el nro. de ticket y el precio de una venta se debe efectuar mediante una función que primero limpie la pantalla y luego informe.
Para informar cuando no queda más lugar de una ubicación se debe efectuar mediante una función que primero limpie la pantalla y luego informe.

Todos los mensajes que se muestren por pantalla deben estar prolijamente ordenados y distribuidos.
No utilizar variables globales.
