# Codificador_rotatorio

# Explicación

Este codigo maneja un modulo llamado ky-040, el cual es un codificador rotativo.
para el funcionamiento se crearon 2 variables (A, B, Anterior, Posicion) 

Basicamente, funciona por medio de interrupciones en el pin que va al A, cuando este detecta un cambio a "LOW".

En el Loop del codigo, se verifica si la posicion cambia desde la ultima interrupcion, determina si el giro fue en sentido manecillas del reloj, o antihorario (mediante el pin B) y posteriormente imprime la posicion entre 0 y 100.

