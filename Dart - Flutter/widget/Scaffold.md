`Scaffold` es un widget de estructura que te da la “base” de una pantalla tipo Material Design.

Sirve para no tener que construir manualmente elementos típicos de una app.

Incluye cosas como:

- `AppBar` (barra superior)
    
- `body` (contenido principal)
    
- `FloatingActionButton`
    
- `Drawer` (menú lateral)
    
- `BottomNavigationBar`
    

Ejemplo conceptual:

Scaffold(
  appBar: AppBar(title: Text("Mi app")),
  body: Center(child: Text("Hola mundo")),
  floatingActionButton: FloatingActionButton(
    onPressed: () {},
    child: Icon(Icons.add),
  ),
)

Piensa en `Scaffold` como el “esqueleto” de la pantalla.
