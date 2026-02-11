Las variables dentro de las pueden tener valores por defecto y si se quieren alterar se tiene que especificar la variable al momento de llamar la función

`void optionalFunction({String name = "Unknow", int age = -1}) {`
  `print ("You're $name and have $age years old");`
`}`

`optionalFunction(age: 32); // Esto haria a printa You're Unknow and have 32 years old`

también podriamos tener una opción por defecto y otra no.

`void optionalFunction({String name, [int age = -1]) {`
  `print ("You're $name and have $age years old");`
`}`

En este caso forzadamente tendriamos que ingresar un name en al llamar la función pero no es necesario para age aun que también se puede, cuando son varios se usa corchete y cuando solo es una por defecto se usa las llaves.