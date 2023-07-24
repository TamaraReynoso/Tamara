Funcion result <- compareDistances ()
	Definir result Como Logico;
	Definir negativeNumber, positiveNumber Como Real;
	negativeNumber = 0;
	positiveNumber = 0;
	Para count=1 Hasta 5 Con Paso 1 Hacer
		Escribir "Escribe un numero"
		leer num
		SI num > 0 Entonces
			positiveNumber = positiveNumber + num;
		SiNo
			negativeNumber = negativeNumber + num;
		FinSi
	FinPara
	result = positiveNumber > Abs(negativeNumber)
Fin Funcion

Algoritmo exampleCompareDistances
	Imprimir compareDistances()
FinAlgoritmo


*** Ejecución Iniciada. ***
Escribe un numero
> 10
Escribe un numero
> 10
Escribe un numero
> 10
Escribe un numero
> 10
Escribe un numero
> -41
FALSO
*** Ejecución Finalizada. ***
