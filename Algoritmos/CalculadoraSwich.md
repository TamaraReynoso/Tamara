### CalculadoraSwich 
Algoritmo Calculadora_Swich
	Imprimir 'calculadora simple'
	Imprimir "Ingrese el primer numero"
	leer No1
	Imprimir "Ingrese el segundo numero"
	leer No2
	Imprimir "ingrese una operacion:+,-,*,/"
	Leer Op
	Si Op == '+' | Op =='-' | Op == '*'| Op == '/' Entonces
	Imprimir 'Procesando: ' + ConvertirATexto(n1) + ' ' + op + ' ' + ConvertirATexto(n2)
		Segun Op Hacer
			'+' :
					Imprimir 'Resultado: ' ConvertirATexto(No1 + No2)
				'-' :
					Imprimir 'Resultado: ' ConvertirATexto(No1 - No2)
				'*' :
					Imprimir 'Resultado:' ConvertirATexto(No1 * No2)
				'/' :
					Imprimir 'Resultado: ' ConvertirATexto(No1 / No2)
			
			Fin Segun
		SiNo
			Imprimir 'Operacion no es valida'
	FinSi
FinAlgoritmo



calculadora simple
Ingrese el primer numero
> 10
Ingrese el segundo numero
> 2
ingrese una operacion:+,-,*,/
> /
Procesando: 0 / 0
Resultado: 5
*** Ejecución Finalizada. ***


