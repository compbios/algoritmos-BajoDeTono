
Algoritmo sin_titulo
	Definir a Como Entero
	Leer a
	Si a MOD 2 = 0 Entonces
		Escribir "es par"
	SiNo
		Escribir "es impar"
	Fin Si
FinAlgoritmo

Algoritmo CILINDRO
	Escribir "Bienvenido a la calculadora de área y volumen de cilindros"
	Escribir "Por favor escriba la unidad de medida que vamos a usar (Se sugiere m o cm)"
	Leer Unidad
	Escribir "Por favor escriba la altura del cilindro en centimetros y presione ENTER" 
	Leer Altura
	Escribir "Por favor escriba el radio del cilindro en centimetros y presione ENTER"
	Leer Radio
	Escribir "Area del cilindro = " 2*PI*Radio*(Radio+Altura) " " Unidad "2"
	Escribir "Volumen del cilincro = " PI*(Radio*Radio)*Altura " " Unidad "3"
Fin Algoritmo
