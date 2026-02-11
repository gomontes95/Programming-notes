Los maps son una estructura de datos que esta construida a partir de una clave y un valor, la forma en se puede acceder al valor es llamando a la clave. El Map siempre se declara en mayuscula como las otras estructuras de y se escribe entre corchetes angulares primero la clave y despues el valor.

`Map<String, int>`
`// Map<Clave, Valor>`

`void mapExamples() {`

  `Map<String, int> people = {"Aris": 32, "Pepe": 64, "MaureDev": 128};`
  
  `people["Aris"] = 8;`
  `people.addAll({"David": 16, "Miguel": 32});`
  `people.remove("Pepe");`
  `people.containsKey("Aris");`
  `people.containsValue(32);`
  `print(people["Aris"]);`

`}`

Los maps son más parecidos a los Sets en como se organizan porque estos se buscana por su clave e igual al agregar alguno se le tiene que poner su clave o para modificarlo tambien se tiene que escribir su clave.

Para los maps tenemos dos funciones que nos dan [[Boolean]] que serian .containsKey() y .containsValue() que nos van a verificar si en el maps existe el valor o la key.

Tambien al momento de llamar un maps se pueden llamar de la siguiente forma

`mapExamples.entries // Este llamaria a tanto las key como los values`
`mapExamples.value // solo lo llama los value`
`mapExamples.key // solo llama las key`
