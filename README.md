# reto_4

## El siguiente reto consiste en

**1.Hacer diagrama de flujo**
  
**2.Hacer pseudocódigo**

Para encontrar los números primos hasta un número n y para sacar la raíz cuadrada de cualquier número

## Diagrama de flujo para encontrar los números primos hasta n:

![image](https://github.com/isabellam242006/reto_4/assets/142249384/d08b6160-eb16-4efc-b7a1-be89958149f6)

##  Pseudocódigo

```
Inicio
    n = Número natural  --> El número hasta donde encontraremos los números primos
    P = 1  --> Inicialización de P
    i = 2  --> Inicialización de i
    
    Mientras P < n Y P=! i
        Si módulo (P, i) == 0 
            escribir("P no es primo")
            P= P+1  --> Avanzar al siguiente número en la secuencia
        Sino
            escribir("P es primo")
            i = i + 1  --> Avanzar al siguiente número en la secuencia
    Fin mientras
Fin
```

## Diagrama de flujo para encontrar la raíz cuadrada de cualquier número n

![image](https://github.com/isabellam242006/reto_4/assets/142249384/33786dd7-284e-42ad-b9c2-35ee23bfe95a)

## Pseudocódigo (Utilizando el método Newton Raphson)

```
Inicio
   Variable = n

 Mientras n >= 0
         A = n/2
         A2 = 0.5 * (A + n/A)

      Si (A - A2 < 0.0001)
     Escribir ("La raíz cuadrada de n con un margen de error de 0.0001 es A2)

     Sino A = A2  --> Volver a aplicar la fórmula

 Sino escribir ("No se puede calcular la raíz cuadrada")
 Fin mientras
Fin

```

