# reto_4
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
    Sino
        escribir("Fin de la búsqueda de números primos hasta " + n)
```
