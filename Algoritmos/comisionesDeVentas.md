## COMISIONES DE VENTAS!!
Algoritmo ComisionesDeVentas
	escribir "ingresar el numero total de ventas"
	leer cantidaddeventas
	ingresostotales =0
	para venta=1 Hasta cantidaddeventas con paso 1 Hacer
		Escribir "el valor de la venta numero: " , venta
		leer cantidad
		ingresostotales = ingresostotales + cantidad 	
	FinPara
	promedio = ingresostotales / cantidaddeventas
	Escribir "el promedio de ventas es: " , promedio

	
	Si importedeventas < 5 Entonces
		Escribir "la comision que recibe el vendedor es: ", ingresostotales * 0.10 // total/100*15
	SiNo
		Escribir "la comision que recibe el vendedor es: ", ingresostotales * 0.15 //total/ 100*15
		
  FinSi
	FinAlgoritmo

 
 *** Ejecución Iniciada. ***
ingresar el numero total de ventas
> 3
el valor de la venta numero: 1
> 54
el valor de la venta numero: 2
> 52
el valor de la venta numero: 3
> 84
el promedio de ventas es: 63.3333333333
la comision que recibe el vendedor es: 19
*** Ejecución Finalizada. ***
