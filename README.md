# CineplusJas
aplicacion basica de cobro para un cine creada en python con wxglade.consta de 4 ventanas:inicio de sesion,taquilla,dulceria y ticket
ventana de inicio de sesion (login)
Esta ventana aparece antes de entrar al sistema de taquilla.
Su función principal es pedir los datos al usuario para autenticarlo.
Orden	Ventana	Función principal
Inicio de sesión	Controlar el acceso al sistema
Taquilla	Elegir película, boletos y subtotal
Dulcería	Elegir comida, bebidas y subtotal
Confirmación	Revisar todo antes del ticket
Ticket final	Mostrar toda la compra completa

venta de boletos (Taquilla)
Es la primera pantalla del programa.
Es la encargada de:
Mostrar las películas disponibles.
Mostrar horarios, salas, formatos, imágenes de cada película.
Permitir al usuario elegir cantidad de boletos:
Menores
Adultos
Adultos mayores
Calcular el subtotal de boletos seleccionado.
Crear un resumen de compra de taquilla (película, horario, cantidad, total).
Para que el usuario seleccione qué película quiere ver y cuántos boletos necesita antes de pasar a la dulcería.

venta de productos(Dulceria)
Aparece después de comprar boletos.
Esta ventana permite:
Mostrar las imágenes y precios de:
Palomitas
Refrescos
Elegir la cantidad de cada producto mediante spinners.
Calcular el subtotal de dulcería.
Generar el resumen de compra de dulcería.
Para que el usuario agregue comida y bebidas a su orden antes de generar el ticket final.

ventana de todo(Ticket)
Es una ventana intermedia entre Dulcería y el Ticket.
En esta ventana:
Se muestra el resumen de taquilla (datos recibidos de Ventana1).
Se muestra el subtotal de taquilla.
Se muestra el resumen de dulcería (datos recibidos de Ventana2).
Se muestra el subtotal de dulcería.
Ofrece dos opciones:
Volver a la dulcería (si el usuario quiere cambiar algo).
Continuar al ticket final.
sirve para:Para confirmar que el usuario está de acuerdo con:
Película seleccionada
Boletos elegidos
Productos de dulcería
Precios y subtotales
Es un filtro para evitar errores antes de generar el ticket.
🧾 VENTANA 4 – Ticket Final (ventana4)
Muestra un ticket completo con:
Información de taquilla (película, boletos, horario).
Subtotal de taquilla.
Información de dulcería.
Subtotal de dulcería.
TOTAL FINAL A PAGAR
Permite cerrar el ticket y terminar el programa.
Para que el usuario pueda ver su ticket final, revisarlo y finalizar la compra.
