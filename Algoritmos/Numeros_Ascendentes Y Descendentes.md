##NUMEROS ASCENDENTES Y DESCENDENTES


Algoritmo Ascendente_Descendentes
	Imprimir ' Numeros Ascendentes y Descendentes'
	Imprimir 'Ingrese un numero'
	Leer numero
	Imprimir 'Operaciones disponibles:'
	Imprimir  '1. Imprimir en orden Ascendente'
	Imprimir '2. Imprimir en orden Descendente'
	Imprimir 'ingrese operacion a ejecutar'
	leer op
	Segun  op Hacer
		1:
			Para iterador <- 0 Hasta numero Con Paso 1 Hacer
				Imprimir ConvertirATexto(iterador)
				
			FinPara
		2:
			para iterador <- numero hasta 0 con paso -1 Hacer
				Imprimir ConvertirATexto(iterador)
			FinPara
		De Otro Modo:
			Imprimir 'Opcion incorrecta!'
	FinSegun
	
FinAlgoritmo


Numeros Ascendentes y Descendentes
Ingrese un numero
> 8
Operaciones disponibles:
1. Imprimir en orden Ascendente
2. Imprimir en orden Descendente
ingrese operacion a ejecutar
> 2
8
7
6
5
4
3
2
1
0
*** Ejecución Finalizada. ***











