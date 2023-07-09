## DistanciaACero.
Algoritmo DistanciaACero
	Escribir "Escribe un numero"
	leer maxDistancia
	para count =1 hasta 4 Con Paso  1 Hacer
		Escribir "Escribe un numero"
		leer num
		Si Abs(num) > Abs(maxDistancia) Entonces
			maxDistancian = num
			
			FinSi
		FinPara
	Imprimir  trunc(maxDistancia)
	FinAlgoritmo


*** Ejecución Iniciada. ***
Escribe un numero
> -60
Escribe un numero
> 50
Escribe un numero
> -10
Escribe un numero
> 20
Escribe un numero
> -10
-60
*** Ejecución Finalizada. ***
