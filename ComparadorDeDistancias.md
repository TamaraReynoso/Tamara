## Comparador De Distancias !!

`` pcs Funcion resultado <-  compareDistances ()
	Definir  resultado Como Logico;
	Definir  numeroNegativo, numeroPositivo Como Real;
	numeroNegativo = 0;
	numeroPositivo = 0;
	para count=1 Hasta 5 con paso 1 Hacer
		Escribir "escribe un numero"
		leer num
		SI num  > 0 Entonces
			numeroPositivo = numeroPositivo + num;
		SiNo
			numeroNegativo = numeroNegativo + num;
			
		FinSi
	FinPara
	
		resultado = numeroPositivo > Abs(numeroNegativo)
	Fin Funcion
	
Algoritmo exampleCompareDistances
	Imprimir compareDistances()
FinAlgoritmo``
