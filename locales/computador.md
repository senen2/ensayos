CICLOS

HARDWARE

Lectura del programa

    1. Conecta el bus de datos al CPU para que reciba la instrucción
    2. Envía una dirección a la memoria para que ponga en el bus de datos la información que hay ahí
    3. Incrementa la dirección
    4. Espera por el CPU

Ejecución del programa

    1. Decodifica la instrucción enviada por la memoria
    2. Ejecuta la instrucción. Puede,
        ◦ Conectar el bus de datos con los registros o con el acumulador
        ◦ Escribir la posición del programa
        ◦ Leer la memoria
        ◦ Escribir la memoria
        ◦ Escribir los registros
        ◦ Leer los registros
        ◦ Ejecutar operaciones con el acumulador y los registros
    3. Espera por el programa

Leer la memoria significa que se envía una dirección a la memoria y esta devuelve la información que se encuentra en esa dirección

Escribir la memoria significa que la memoria pasa la información que se encuentra en el bus de datos a la dirección que le indican.

SOFTWARE

Consiste en escribir instrucciones en la memoria y luego escribir en la dirección de lectura del programa la posición de la primera instrucción.

Compilador

Convierte instrucciones en un lenguaje de alto nivel en instrucciones del procesador

Python

Lee instrucciones en lenguaje de alto nivel y las compila en instrucciones en bytecode para que luego los ejecute una Máquina Virtual.

Cómo funciona la máquina virtual? Parece que interpreta los bytecode y los traduce a instrucciones de máquina – esto no me suena mucho. Vamos a leer.

