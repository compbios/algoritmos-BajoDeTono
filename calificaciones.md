Algoritmo PROMEDIO
	Escribir "Bienvenido al calculo de promedio de notas"
	Escribir "Por favor introduzca la nota del PARCIAL 1 y presione ENTER"
	Leer Parcial1
	Escribir "Por favor introduzca la nota del PARCIAL 2 y presione ENTER"
	Leer Parcial2
	Escribir "Por favor introduzca la nota de PARTICIPACION EN CLASE y presione ENTER"
	Leer Participacion
	Escribir "Por favor introduzca la nota del EXAMEN FINAL y presione ENTER"
	Leer Examen
	Escribir "Su promedio es = " (Parcial1*0.25)+(Parcial2*0.25)+(Participacion*0.2)+(Examen*0.3)
	 
Si (Parcial1*0.25)+(Parcial2*0.25)+(Participacion*0.2)+(Examen*0.3) >= 3 Entonces
	Escribir "Felicitaciones has pasado la materia :)"
SiNo
	Escribir "Lamentablemente has perdido la materia :("
Fin Si
FinAlgoritmo
