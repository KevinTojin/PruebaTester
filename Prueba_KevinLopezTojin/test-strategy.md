Kevin ALberto Lopez Tojin - 03/21/2022 - version 1.0.0

Listado de errores y soluciones:

1. La etiqueta </body> estaba cerrada antes del <script> dejandolo excluido
	Solucion:
	Colocar la etiqueta de cerradura </body> antepenultima, justo antes de la etiqueta de cierre </html>

2. El boton no tenia Listener o escuchador de eventos de click  -- (2) Dos errores de este tipo
	Solucion:
	Agregar antes de las funciones y sintaxis correcta "addEventListener" guessSubmit.addEventListener('click', checkGuess);
	Agregar antes de las funciones y sintaxis correcta "addEventListener" resetButton.addEventListener('click', resetGame);
 
3. Operador incorrecto  -- (2) Dos errores de este tipo
	solucion:
	Agregar el operador correcto_ let randomNumber = Math.floor(Math.random() * 100) + 1;
 
4. Fallo al asignar una igualdad.
	Solucion:
	Agregar "Number" a la igualdad_ let userGuess = Number(guessField.value);
 
5. Error de sintaxis
	solucion:
	Agregar "." antes de la constante ".lowOrHi" const lowOrHi = document.querySelector('.lowOrHi');
 
6. Mensajes cambiados en respuesta de funciones
	Solucion:
	Agregar las salidas correctas en las condicionales if
 
 7. Constante con valor que no correspondia al caso de uso
	Solucion:
	Agregar valor correcto_ const ATTEMPS = 10;
 
 Resumen:
 -Errores de sintaxis corregidos.
 -Errores de etiqueta corregidos.
 -Logica de programa arreglada y funcionando acorde a las directrices del caso de uso.
 -Funcionalidad y restricciones en orden.
 -Codigo debidamente documentado.
 