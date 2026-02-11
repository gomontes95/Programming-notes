Las listas son como los array de otros lenguajes y se declaran con la palabra reservada List<> seguida de unos corchetes angulares donde pondremos el tipo de lista que vamos a usar por ejemplo string

Las List siempre se declaran en mayuscula.

void listExamples(){

  List<String> names = ["Aris", "Peper", "Manolo"];
  var names2 = ["Peach", "Wario", "Daisy"];
  names[2] =  "Mario";
  names.add("Luigi");
  names.addAll(names2);
  names.remove("Aris");
  names.removeAt(1);
  names.clear();
  names.insert(0, "Diego");
  print(names[names.length-1]);
  
}

var hay usar los square brackets se convertira en una lista porque infiere que tipo de variable es lo que estamos usando y si alteramos su contenido se podria convertir en una lista de objeto u otra cosa.

Igual que los array las listas tiene un indice interno que comienza con 0 hasta la cantidad de argumentos internos que tenga la lisata menos la cantidad de 1 porque comienza con 0.

Por ejemplo: En el codigo que esta anteriormente escrito tendria un length de 3 pero un maximo de indice de 0 a 2.