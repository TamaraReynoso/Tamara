## NombreCompleto. 

````psc
Algoritmo Nombre_Completo
	Escribir "Escribe un nombre"
	leer first_nombre
	Escribir "Escribir un apellido"
	leer last_nombre
	corrected_first_nombre = Mayusculas(Subcadena(first_nombre,0,0)) + Minusculas(Subcadena(first_nombre,1,Longitud(first_nombre)-0))
	corrected_last_nombre = Mayusculas(Subcadena(last_nombre,0,0)) + Minusculas(Subcadena(last_nombre,1,Longitud(last_nombre)-0))
	Imprimir corrected_first_nombre, " ", corrected_last_nombre 
	
FinAlgoritmo
````

*** Ejecución Iniciada. ***
Escribe un nombre
> heber
Escribir un apellido
> lopez
heber lopez
*** Ejecución Finalizada. ***
