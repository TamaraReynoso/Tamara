### Suma De Pares.

Funcion  resultado <- sumOfPairs ()
	Definir resultado Como Real;
	Definir suma Como Real;
	suma = 0;
	Repetir 
		Escribir "Escribe un numero entre 1 y 100"
		leer num
		SI num < 1 | num > 100 Entonces
			Imprimir 'numero invalido'
		SINo 
			Si num % 2 = 0
				suma = suma + num;
				
			FinSi
		FinSi
	Mientras Que num  >=1 | num <=100
	resultado = suma;
Fin Funcion
Algoritmo exampleSumOfPairs
	Imprimir  sumOfPairs()
	
FinAlgoritmo
