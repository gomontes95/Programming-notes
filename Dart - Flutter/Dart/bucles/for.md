En los cycles o bucles for se pueden usar de diversas maneras una de las más comunes es para iterar cada uno de los elementos dentro de alguna lista o para crear ciclos que se repiten basados en una condicional tenemos los for clasicos que serian

`for(variable, condición, acción al repetir)`

Los for in, que ciclan a traves de todos los elementos de una estructura de datos

`for(variable in estructuraDeDatos)`

y los forEach, que igual pueden ciclar a traves de ciertos elementos de una estructura de datos.

`miMaps.forEach((Variable1, variable2) {` 
	`metodo a realizar por varable1 y metodo a realizar por variable 2`
`});`

Cada tipo de ciclo for tiene sus fortalezas y diferentes velocidades de operación

`// Loops`

`void listLoop() {`
  `List<int> numbers = [2, 4, 6, 8, 9, 5];`
  
  `for (var i = 0; i < numbers.length; i++) {`
    `print("With basic for we have: ${numbers[i]}");`
  `}` 

  `for (var element in numbers) {`
    `print("With for in we have $element");`
  `}`

  `numbers.forEach((item){`
    `print("The number s $item");`
  `});`
  
  `numbers.forEach(print);`
`}`

`void setLoop() {`
  `Set<int> numbers = {3, 4, 6, 8, 5};`

  `for (var element in numbers) {`
    `print("With for in we have $element on SETS");`
  `}`

  `numbers.forEach(print);`
`}`

  
`void settLoop() {`
  `Map<String, int> numbers = {"favnumber": 13, "birthday": 12, "address": 4};`
  
    `for (var element in numbers.entries) {`
    `print("With for in we have ${element.key} and the value is ${element.value} on MAPS");`
  `}`

  `numbers.forEach((key, value) {`
    `print("The key is $key and the value is $value");`
    `});`
`}`