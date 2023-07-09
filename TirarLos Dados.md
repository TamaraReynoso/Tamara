## TirarLos Dados.
Algoritmo Tirar_Dados
	Definir Dice1, Dice2 Como Entero
	para count = 1 Hasta 10 Con Paso  1 Hacer
		Dice1 = Aleatorio(1,6)
		Dice2 = Aleatorio(1,6)
		SI Dice1 = Dice2 Entonces
			Imprimir Dice1, " ", Dice2, " los dados son los mismos"
		siNo 
			Imprimir  Dice1, " ", Dice2
		FinSi
	FinPara
	FinAlgoritmo

 
 ** Ejecución Iniciada. ***
3 3 los dados son los mismos
6 4
3 2
7 5
3 5
5 6
4 4 los dados son los mismos
2 2 los dados son los mismos
3 2
3 6
*** Ejecución Finalizada. ***

 
