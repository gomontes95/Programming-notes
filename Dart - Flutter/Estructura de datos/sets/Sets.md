Los sets son como las listas pero no pueden tener valores repetidos y que no tienen un indice. Los Set se declaran con mayuscula siempre igual que las List

void setExamples(){
  Set<String> names = {"Aris", "Pepe"};
  Set<String> names2 = {"Aris", "Pepe"};
  names.add("Aris");
  names.add("aris");
  names.add("Bimbo");
  names.remove("aris");
  names.clear();
  names.removeAll(names2);
  bool result = names.contains("Aris");
  if(result) {
    print("Aris esta invitada");
  } else {
    print("Aris no esta invitada");
  }
  List<String> newNames = ["Aris", "Aris", "Juan"];
  Set<String> newNamesSet = Set.from(newNames);
  print(newNamesSet);
}

Se puede usar el from para crear un nuevo set basandonos en otra estructura de datos