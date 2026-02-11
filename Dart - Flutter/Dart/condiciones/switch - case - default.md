El condicional switch sirve en aquellas situaciones en que hay demasiados casos que un [[else]] [[if]] se repite demasiadas veces, usando case y un valor que represente la condición que se estaria cumpliendo terminado por un break para terminar el proceso, igual si ningun efecto aplicaría usamos un default para cuando ninguno de los casos existente se usaría.

Se pone break si no hay contenido.

  `int numberOfTheWeek = int.parse(stdin.readLineSync()!);`
  
  `switch (numberOfTheWeek) {`
    `case 1:`
      `print("Monday");`
    `case 2:`
      `print("Tuesday");`
    `case 3:`
      `print("Wednesday");`
    `case 4:`
      `print("Thursday");`
    `case 5:`
      `print("Fruday");`
    `case 6:`
      `print("Saturday");`
    `case 7:`
      `print("Sunday");`
    `case 8:`
      `break;`
    `default:`
      `print("not a valid number");`
  `}`

}