Es un widget que maneja un stack de pantallas, conocidas como rutas. Trabaja como si fuera una baraja de cartas: la pantalla que estas viendo actualmente es la que carta(pantalla) que esta encima de la baraja, y utiliza funciones especificas para añadir o remover las pantallas de la baraja

Navigator.push(context, builder:); 
para que la nueva pantalla se ponga encima.

Navigator.pop(context); 
para que retira la pantalla actual y presente la pantalla anterior

Navigator.pushNamed();
se utiliza cuando hay demasiadas pantallas y necesitas llamar a una pantalla en especifico.

Navigator.pushReplacement();
Suele usarse en escenarios como una pantalla de inicio de sesion, remplaza la ruta actual con una nueva para no volver a esta misma porque ya no se va a usar por conveniencia o seguridad.

Navigator.popUntil();
Esto retirara rutas del stack hasta que una condicion se cumpla como por ejemplo el retorno a la home screen