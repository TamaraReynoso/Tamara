### Precio Total.
funcion  valor <- TotalPrecio (precio, iva)
	Definir valor como real;
	SI precio > 3000 Entonces
		valor = (precio + (precio/100*iva) ) /100*90
	SiNo 
		valor = (precio +(precio/100*iva) )
		FinSi
Fin Funcion

Algoritmo example_TotalPrecio
	Imprimir TotalPrecio(5000,21)
	FinAlgoritmo
 

*** Ejecución Iniciada. ***
5445
*** Ejecución Finalizada. ***
