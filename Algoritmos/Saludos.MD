##SALUDOS
Algoritmo Saludos
	Imprimir "===Saludos==="
	definir contaor Como Entero
	Definir continuar Como Caracter
	contador <-0
	continuar <- "si"
	Mientras continuar = "si" Hacer
		contador <- contador +1
		Imprimir "Ingrese la hora actual (0:00):"
	leer hora
	si hora <=12 Entonces
		Imprimir "Buenos Dias!"
	siNo 
		si hora <=18 Entonces
			Imprimir "Buenas Tardes!"
		SiNo 
			Imprimir "Buenas Noches!"
			
		FinSi
	FinSi
	Imprimir "¿Desea continuar? SI/NO"
	leer continuar
FinMientras
Imprimir "cantidad de saludos:" + ConvertirATexto(contador)
	FinAlgoritmo


===Saludos===
Ingrese la hora actual (0:00):
> 20
Buenas Noches!
¿Desea continuar? SI/NO
> si
Ingrese la hora actual (0:00):
> 16
Buenas Tardes!
¿Desea continuar? SI/NO
> si
Ingrese la hora actual (0:00):
> 8
Buenos Dias!
¿Desea continuar? SI/NO
> no
cantidad de saludos:3
*** Ejecución Finalizada. ***



