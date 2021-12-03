Cambie const y let a var para poder cambiar su valor 

var lastResult = document.querySelector('lastResult'); le faltaba un punto (".lastResult');

let randomNumber = Math.random() * 10; el problema que tenia era que si se hacia de esta manera el numero que generaría tendria decimales, pero si se le pone floor se redondea al numero entero mas cercano, se multiplica por 100 + 1 ya que es el rango que se le dará para generar los numeros random 

(guessField.value); le faltaba number para poder convertir el valor a numeros

El texto de ganaste y perdiste estaban al revez.

guessSubmit.addEventListener('click', checkGuess); no se ejecutaba la accion porque el evento no estaba declarado
