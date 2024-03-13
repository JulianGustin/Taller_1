# Ingenieros Megatróficos 
![logo](https://camo.githubusercontent.com/a12903c4e2f58575622e5cc1222df41a66748bec5311fb8b769d680428dbb9ff/68747470733a2f2f692e6962622e636f2f767652785072622f412d616469722d756e2d742d74756c6f2e706e67)
***
# Taller 1
Desarrollo del taller 1 de la clase "programación de computadores"
## Integrantes del equipo: 
- Lucas Garcia Alvarez
- Kevin Daniel Castellanos Peña
- Julian Jacobo Gustin Moreno
***
## Lista de contenidos 
1.  [Python Beginner Quiz](#quiz)
2.  [Mayor de 3 números](#mayordetres)
3.  [Determinar si es par o impar](#paroimpar)
4.  [Determinar si a es multiplo de b](#multiplos)
5.  [Programa que lee tres números reales y determina si la suma de los dos primeros es mayor, menor o igual que el tercer número](#punto5)
6.  [Vocal o consonante](#vocaloconsonante)
7.  [Operaciones](#operaciones)
8.  [Frecuencia de onda](#frecuencia)
9.  [Capitales](#capitales)
10. [Operaciones con distancias](#distancias)
***
## Quiz

Se adjunta la captura del resultado del quiz
![image](https://github.com/JulianGustin/Taller_1/assets/158980531/5ae9f7ea-5a1e-40ff-aede-3a0575512f1a)
***
## MayorDeTres
***
## ParOImpar
Para este programa, se usó el operador módulo (%) y con condicionales se determinaba si el número era par o impar (si el modulo es 0, es impar)  
Para números con decimales, se usó la función math incluida en python para la determinar la función piso del número ingresado por el usuario. 
## flowchart del ejercicio 
```mermaid
flowchart TD;
   A(Inicio)-->B{"Ingresará un número decimal o uno entero?(d/e)"}--d-->C(Asignar N)
   C-->D[Asignar a m la función piso de n]-->E[Calcular divisionSobreDos = m%0 ]-->F 
   F{divisionSobreDos es igual a 0?}--si-->G("Imprimir ´El número m es par´")-->M
   F--no-->H("Imprimir ´El número m no es par´")-->M
  B--e-->I[Calcular divisionSobreDos = n%0 ]-->J
   J{divisionSobreDos es igual a 0?}--si-->K("Imprimir ´El número n es par´")-->M
   J--no-->L("Imprimir ´El número n no es par´")-->M[Fin]
