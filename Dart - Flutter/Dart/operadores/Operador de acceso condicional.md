El **" ? "** es un operador que permite a las variables declararlas como el tipo de variables que son o dejar la posibilidad de ser null;

`String? name; // da la posibilidad de dejarla vacia osea null`

Con ?? permite dejar un valor predeterminado en caso de dejar vacio alguna expreción por ejemplo.
```
print( name ?? 'Invitado') //  si por ejemplo en la variable que habiamos designado anteriormente como name la dejamos null sera por defecto el string Invitado.
```

 Permite llamar a métodos o propiedades solo si el objeto no es nulo, evitando errores de "null pointer exception
 
```
print(nombre?.length); // Imprime null si 'name' es nulo
```

El operador condicional tambien se puede usar para confirmar una respuesta de alguna condicional ejemplo, con la ayuda del operador **" : "** y **" == "** 
`(name == null) ? print("Name couldn't be null") : print("Your name is $name")` 

