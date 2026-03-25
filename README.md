Proceso control_de_temperatura 
	Definir  n Como Caracter;
    Definir  S Como Caracter;
	Definir  temperatura Como Real;
	
	Repetir
	
	Escribir  "ingresa la temperatura actual ";
	Leer temperatura;
	
	si temperatura <= 9 Entonces
		Escribir "temperatura baja ";
	FinSi
	
	si temperatura  >= 10 Entonces
		si temperatura <= 25 Entonces
			Escribir "temperatura normal";
		FinSi
		
	FinSi
	
	si temperatura > 25 Entonces
		Escribir "temperatura alta ",": se recomienda activar el sistema de enfriamiento";
	
	FinSi
	
	Escribir  "desea continuar? ";
	Escribir  "s/n";
    Leer s;
	
Hasta Que s = "n";
	
	
FinProceso


