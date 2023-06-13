## Calculadora Simple con WHILE

` ` ` pcs Algoritmo Calculadora_con_Do_While
	Imprimir 'Calculadora Con While'
	Repetir
		
           Imprimir 'Ingrese primer numero'
			leer nu1
			Imprimir 'Ingrese segundo numero'
			leer nu2
			Imprimir 'Ingrese operacion: +,-,*,/'
			leer Op
			Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
				Imprimir 'Procesando: ' + ConvertirATexto(nu1) + ' ' + op + ConvertirATexto(nu2)
				finsi
			Segun op hacer 
			
		
		'+':
			Imprimir  'Resultado: ' + convertirAtexto(nu1 + nu2)
		'-':
			Imprimir  'Resultado: ' + ConvertirATexto(nu1 - nu2)
		'*':
			Imprimir  'Resultado: ' + ConvertirATexto(nu1 * nu2)
		'/':
			Imprimir  'Resultado: ' + ConvertirATexto(nu1 / nu2)
		
Fin Segun
  
  Imprimir 'Deseas Continuar con otra Operacion? Si / No'
  leer Continuar
Hasta Que Continuar == 'no' | continuar == 'no' ` ` `
		
FinAlgoritmo


*** Ejecución Iniciada. ***
Calculadora Con While
Ingrese primer numero
> 80
Ingrese segundo numero
> 2
Ingrese operacion: +,-,*,/
> *
Procesando: 80 *2
Resultado: 160
Deseas Continuar con otra Operacion? Si / No
> si
Ingrese primer numero
> 5
Ingrese segundo numero
> 5
Ingrese operacion: +,-,*,/
> +
Procesando: 5 +5
Resultado: 10
Deseas Continuar con otra Operacion? Si / No
> no
*** Ejecución Finalizada. ***







