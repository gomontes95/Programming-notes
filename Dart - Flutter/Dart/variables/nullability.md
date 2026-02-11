Por lo general cuando una variable tiene un vlaor null va a generar un error y puede hacer que la aplicación se cierre. Para este tipo de casos tenemos que que declarar que una variable puede llegar a ser nula.

para esto usamos el [[Operador de acceso condicional]]

void nullability(){
  String? name = "Aris";
  name = "";
  name = null;

  int? example = 13;
  example = null;
}

tambien se puede usar el signo de exclamación para declarar que los más seguro es que va a recibir una variable pero garantiza que se va a romper si en tal caso no llega ninguna variable.

var example2 = name!;

tambien hay formas de usar el operador de acceso condicional para garantizar que una variable tenga un valor.

var name2 = name ?? "invitado";
name2 ??= "Desconocido";

por ejemplo en las dos opciones anteriores podemos garantizar que si a pesar de que name sea null o que name2 quede null vamos a tener garantizado que va a tener algo en la variable aun que sea desconocido.