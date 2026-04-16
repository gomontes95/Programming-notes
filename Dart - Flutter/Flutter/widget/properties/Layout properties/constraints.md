Sirve para:

- Forzar tamaño mínimo
    
- Limitar crecimiento
    
- Evitar que widgets se expandan infinitamente

BoxConstraints(
  minWidth: 100,
  maxWidth: 300,
  minHeight: 50,
  maxHeight: 200,
)

se usa en 

ConstrainedBox(constraints: ...)
Container(constraints: ...)


Ejemplo 

constraints: BoxConstraints.tightFor(width: 200, height: 80)
