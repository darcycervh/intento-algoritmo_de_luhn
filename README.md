# Programa: validar tarjeta de credito.
Entorno: Aplicar el algoritmo de Luhn.

Algoritmo:
1. Preguntar por medio de un prompt el n° de la tarjeta
2. Utilizar for para poner en orden inverso el n° de la tarjeta.
3. Recorrer la longitud del array.
4. Extraer los elementos de cada índice par(i%2===0).
5. Multiplicar los elementos que estan en la posición paa
	SI el resultado de la multiplicación es >= 10
	entonces, sumar cada dígito
	el resultado será el nuevo elemento
	SI NO 
	dejar el resultado;
6. Ahora, sumar todos los elementos.
7. dividir el resultado entre 10 y si el residuo es 0, es una tarjeta 	válida.
Fin del Programa.
