`` ## Tablas de Multiplicacion ``

Algoritmo TablasDe_Multiplicacion
	Imprimir "=====Tablas de multiplicacion====="
	Imprimir "ingrese tabla a calcular"
	leer tabla
	Imprimir ' @ Tabla de ' + ConvertirATexto(tabla) ' * ' + '@'
	iterador <- 1
	Mientras iterador <= 10 Hacer
		iterador <-1
		Mientras iterador <=10 Hacer
			Imprimir ConvertirATexto(tabla) ' * ' + ConvertirATexto(iterador) +'=' ConvertirATexto(tabla*iterador)
			
			iterador <- iterador +1
		FinMientras
		FinMientras
`` FinAlgoritmo ``


`` =====Tablas de multiplicacion===== `` 
ingrese tabla a calcular
> 5
 @ Tabla de 5 * @
5 * 1=5
5 * 2=10
5 * 3=15
5 * 4=20
5 * 5=25
5 * 6=30
5 * 7=35
5 * 8=40
5 * 9=45
5 * 10=50
``  *** Ejecución Finalizada. *** `` 
