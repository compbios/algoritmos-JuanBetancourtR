
Algoritmo sin_titulo
	Definir a Como Entero
	Leer a
	Si a MOD 2 = 0 Entonces
		Escribir "es par"
	SiNo
		Escribir "es impar"
	Fin Si
FinAlgoritmo

Algoritmo sin_titulo
	Escribir "Cálculo de volumen y área de superficie de un cilindro"
	escribir "Ingrese el valor de la altura del cilindro en cm"
	leer altura
	Escribir "Ingrese el valor del radio en cm"
	leer radio
	Escribir "Ingrese el valor de la altura del cilindro en cm"		
	Volumen<-3.1416*radio*radio*altura
	Area<-3.1416*radio*radio*2+(altura*2*3.1416*radio)
	Escribir "El volumen del cilindro es ",Volumen, "cc", "y el área de superficie es ", Area, "cm cuadrados"
FinAlgoritmo
