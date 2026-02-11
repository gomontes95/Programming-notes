Un **StatelessWidget** es un widget **sin estado interno mutable**.

Eso significa:

- No cambia por sí solo.
    
- Solo se redibuja si recibe nuevos datos desde afuera (props).
    

Ejemplo:

`class Saludo extends StatelessWidget {   @override   Widget build(BuildContext context) {     return Text("Hola");   } }`

Ese texto:

- No cambia.
    
- No depende de eventos internos.
    
- Solo se renderiza.
    

Úsalo cuando la UI es estática.

## Error común

Intentar usar `StatelessWidget` para cosas que cambian:

- contadores
    
- inputs
    
- listas dinámicas
    
- toggles
    

Eso termina obligándote a reescribir el widget.