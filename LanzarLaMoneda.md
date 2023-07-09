## LanzarLaMoneda.
Algoritmo LanzarLaMoneda
	
	Escribir "Ingresa el nombre del primer jugador"
	leer player1
	Escribir "Ingresa la cantidad a jugar"
	leer amount1
	Escribir "Ingresa el nombre del segundo jugador"
	leer player2
	Escribir "Ingresa la cantidad a jugar"
	leer amount2
	
	SI amount1<=0 | amount2 <=0 Entonces
		SI amount1<=0 & amount2 <=0 Entonces
			Imprimir "Juego Cancelado"
		SiNo
			SI amount1<=0 Entonces
				Imprimir "Jugador que gana: ", Mayusculas(player2), " cantidad ganada: 0"
			SiNo
				Imprimir "Jugador que gana: ", Mayusculas(player1), " cantidad ganada: 0"
			FinSi
		FinSi
	SiNo
		SI Aleatorio(1,2) = 1 Entonces
			Imprimir "Jugador que gana: ", Mayusculas(player1), " cantidad ganada: ", amount2
		SiNo
			Imprimir "Jugador que gana: ", Mayusculas(player2), " cantidad ganada: ", amount1
		FinSi
	FinSi


 *** Ejecución Iniciada. ***
Ingresa el nombre del primer jugador
> Samuel!
Ingresa la cantidad a jugar
> 5
Ingresa el nombre del segundo jugador
> Carlos
Ingresa la cantidad a jugar
> 4
Jugador que gana: SAMUEL! cantidad ganada: 4
*** Ejecución Finalizada. ***
