# core-code-from-scratch-readme-week2-
# Week 2 of Core Code Bootcamp

## Logic Problem

  //Solo los alumnos que estudiaron van a decir la verdad, validar cada proposicion y verificar que no hayan contradicciones.
  
    1. CASO 1: Alice
    
      * Proposicion: Nadie estudio matematicas ayer
      * Validacion: Solo los alumnos que estudiaron dicen la verdad
      * Resultado: Si Alice dice la verdad existiria contradiccion entre su proposicion y la validacion.
    
    2. CASO 2: Bob
      
      * Proposicion: 1 persona estudio matematicas ayer
      * Validacion: Solo los alumnos que estudiaron dicen la verdad
      * Resultado: Si Bob dice la verdad NO existiria contradiccion entre su proposicion y la validacion.
      
    3. CASO 3: Charlie
      
      * Proposicion: 2 personas estudio matematicas ayer
      * Validacion: Solo los alumnos que estudiaron dicen la verdad
      * Resultado: Si Charlie dice la verdad  existiria contradiccion entre su proposicion y las proposiciones de los otros estudiantes.
      
    4. CASO 4: Dan
      
      * Proposicion: 3 personas estudio matematicas ayer
      * Validacion: Solo los alumnos que estudiaron dicen la verdad
      * Resultado: Si Dan dice la verdad  existiria contradiccion entre su proposicion y las proposiciones de los otros estudiantes.
      
    5. CASO 5: Eva
      
      * Proposicion: 4 personas estudio matematicas ayer
      * Validacion: Solo los alumnos que estudiaron dicen la verdad
      * Resultado: Si Eva dice la verdad  existiria contradiccion entre su proposicion y las proposiciones de los otros estudiantes.
      
  RESULTADO: BOB dice la verdad
  
  
  ## Cereal vrs Milk
  
  ### ALGORITMO
  
    1. Sacar bowl y cereal de la alacena
    2. Sacar leche de la refrigeradora
    3. Abrir recipiente de leche
    4. Vertir leche en el bowl hasta que este lleno
    5. Cerrar recipiente de leche
    6. Abrir caja de cereal
    7. Servir cereal sobre la leche al gusto
    8. Cerrar caja de cereal
    9. Comer cereal con leche
    10. FIN
    
  ### PSEUDOCODIGO
  
    ALGORITMO (Servir leche con cereal)
    
    VARIABLES
    
      * Cereal
      * Leche
      
    INICIO
    
      ESCRIBIR("Sacar bow y cereal de la alacena")
      ESCRIBIR("Sacar leche de la refrigeradora")
      PROCESO("Vertir leche en el bowl hasta que este lleno")
      PROCESO("Cerrar recipiente de leche")
      PROCESO("Abrir caja de cereal")
      PROCESO("Servir cereal sobre la leche al gusto")
      PROCESO("Cerrar caja de cereal")
      ESCRIBIR("Comer leche con cereal")
      
    FIN
 
 ![image](https://user-images.githubusercontent.com/117783981/204408942-0623b3e5-3d43-4c20-bef3-a9a15755fae8.png)
 
 ## PRINT MY NAME & AGE
 
 Algoritmo ImprimirNombreEdad
 
	Imprimir "David Gil"
	Imprimir 28
			
FinAlgoritmo

## ALGORITHM GAME

![image](https://user-images.githubusercontent.com/117783981/204685629-5b223c82-638f-4938-81a2-ca940bf8aaf4.png)

## REGISTER FORM

Algoritmo RegisterForm
	
	Imprimir "--------- USER FORM -----------"
	Imprimir "Ingrese su primer nombre"
	Leer nombre
	Imprimir "Ingrese su apellido"
	Leer apellido
	Imprimir "Ingrese su edad"
	Leer edad
	Imprimir "Ingrese su e-mail"
	Leer email
	Imprimir "Ingrese su direccion"
	Leer dir
	Imprimir ""
	Imprimir "Su información es:"
	Imprimir ""
	Imprimir "Nombre y apellido:", " ", nombre, " ", apellido
	Imprimir "Edad:", " ", edad, " ", "años"
	Imprimir "Correo electronico:", " ", email
	Imprimir "Direccion:", " ", dir
			
FinAlgoritmo

## MODULO

Algoritmo Modulo
	
	Imprimir "Ingrese un numero para verificar si es par o impar"
	Leer num
	Imprimir "Verificando si es par o impar"
	Imprimir ""
	Imprimir ""
	x <- num % 2
	Si x > 0 Entonces
		Imprimir "El numero ", num, " es impar"
	SiNo
		Imprimir "El numero ", num, " es par"
	Fin Si
	Imprimir ""
	
FinAlgoritmo


## TRUTH TABLES

	1. T & T = T ✅
	2. T & F = F ✅
	3. F & T = T ❌
	4. F & F = F ✅
	5. T | T = T ✅
	6. T | F = F ❌
	7. F | T = T ✅
	8. F | F = F ✅
	9. ~T = T ❌
	10. ~F = T ✅
	11. (T & F) | (~F) = T ✅
	12. (T | F ) & (F | F) = T ❌
	13. ~((T | F ) & (F | F)) & F = T ❌
	14. ~((T | F ) & (F | F)) & T = F ❌
	
## BOOLEAN RESULTS

Algoritmo boolean

	a. <- 5 == 3 // FALSO, porque 5 no es igual a 3
	b. <- 4 <> 3 // VERDADERO, porque 4 no es igual a 3
	c. <- 7 > 7 // FALSO, porque 7 no es mayor que 7
	d. <- 4 < 4 // FALSO, porque 4 no es menor que 4
	e. <- 100 <= 90 // FALSO, porque 100 no es menor o igual que 90
	f. <- 40 >= 40 // VERDADERO, porque 40 si es mayor o igual a 40
	
FinAlgoritmo


## IDENTIFY ODD AND EVEN NUMBERS

Algoritmo Modulo
	
	Imprimir "Ingrese un numero para verificar si es par o impar"
	Leer num
	Imprimir "Verificando si es par o impar"
	Imprimir ""
	Imprimir ""
	x <- num % 2
	Si x > 0 Entonces
		Imprimir "El numero ", num, " es impar"
	SiNo
		Imprimir "El numero ", num, " es par"
	Fin Si
	Imprimir ""
	
FinAlgoritmo


	

    
    
      
