## Par o Impar
Algoritmo ParOImpar
	Repetir
		Escribir  "escribe un numero entre 1 y 50"
		leer num
		Si num < 1 |num > 50 Entonces
			Imprimir  'Numero invalido'
		FinSi
	Mientras que num <1 |  num >50
	
	par = num % 2 = 0 
	para count=1 hasta num con paso 1 hacer 
		Si count %2 = 0 | par Entonces
			Imprimir count 
		FinSi
		SI count % 2 = 0 & par Entonces
			Imprimir count
			
		FinSi
		SI count % 2 = 1 & ~(par) Entonces
		FinSi

	FinPara
FinAlgoritmo


" *** Ejecución Iniciada. *** "
Escribe un numero entre 1 y 50
> 10
2
4
6
8
10
*** Ejecución Finalizada. ***    = Num Par
> 

*** Ejecución Iniciada. ***
Escribe un numero entre 1 y 50
> 5
1
3
5
*** Ejecución Finalizada. ***  = Num impar
