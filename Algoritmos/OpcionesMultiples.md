## Programa'Opciones_Multiples.
Algoritmo Programa_OpcionesMultiples
	Imprimir 'Opciones Disponibles'
	Imprimir '1.sumar de dos numeros'
	Imprimir '2.imprimir dia de la semana'
	Imprimir 'Calcular Longitud de texto'
	imprimir 'ingrese la Opcion:'
	leer Op 
	Segun Op hacer 
		1:
			Imprimir 'Op 1. sumar de dos numero'
			Imprimir 'Ingrese primer numero'
			leer No1
			Imprimir 'Ingrese segundo numero'
			leer No2
			Imprimir 'Resultado:' + ConvertirAtexto(No1 + No2)
			
		2:
			Imprimir 'Op 2. Imprimir dia de la semana'
			Imprimir 'Ingrese el dia de la semana en numeros (1-7)'
			Leer  dia
			Segun  dia Hacer
				1:
					Imprimir  'Lunes'
				2:
					Imprimir 'Martes'
				3:
					Imprimir 'Miercoles'
				4:
					Imprimir 'Jueves'
				5:
					Imprimir 'Viernes'
				6:
					Imprimir 'Sabado'
				7:
					Imprimir 'Domingo'
				De Otro Modo:
					
					Imprimir 'Dia Incorrecto!!'
					
			Fin Segun
			Imprimir 'Op 3. Calcular la Longitud de texto'
			Imprimir 'Ingrese un texto'
			leer cadena
			Imprimir 'Resultados: ' + ConvertirATexto(Longitud(cadena))
		De Otro Modo:
			Imprimir 'Op Incorrecta!!'
			
			FinSegun
	FinAlgoritmo
  


1.sumar de dos numeros
2.imprimir dia de la semana
Calcular Longitud de texto
ingrese la Opcion:
> 2
Op 2. Imprimir dia de la semana
Ingrese el dia de la semana en numeros (1-7)
> 2
Martes
Op 3. Calcular la Longitud de texto
Ingrese un texto
> Cumpleaños
Resultados: 10
*** Ejecución Finalizada. ***

