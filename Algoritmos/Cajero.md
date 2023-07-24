Funcion balance <- cashier ()
	Definir balance Como Real;
	balance = 1000;
	Repetir
		Imprimir "Selecciona una Opción:";
		Imprimir "a. Depositar.";
		Imprimir "b. Retirar.";
		Imprimir "c. Salir.";
		leer Option
		si option = 'a' Entonces
			balance = balance + deposit()
		FinSi
		Si option = 'b' Entonces
			 balance = balance - withdraw()
			FinSi
		Mientras Que option = "a" | option = "b"
	fin funcion
	Funcion value <- deposit()
		Imprimir  "¿cuánto deseas depositar?:";
		leer value
FinFuncion
Funcion value <- withdraw()
	Imprimir "¿Cuánto deseas retirar?:";
	leer value
	
FinFuncion
Algoritmo exampleCashier
	Imprimir cashier()
FinAlgoritmo


*** Ejecución Iniciada. ***
Selecciona una Opción:
a. Depositar.
b. Retirar.
c. Salir.
> b
¿Cuánto deseas retirar?:
> 800
Selecciona una Opción:
a. Depositar.
b. Retirar.
c. Salir.
> c
200
*** Ejecución Finalizada. ***
