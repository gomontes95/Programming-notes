Es el sistema completo de estilos visuales.

decoration: BoxDecoration(
  color: Colors.white,
  borderRadius: BorderRadius.circular(12),
  border: Border.all(color: Colors.black, width: 2),
  boxShadow: [
    BoxShadow(color: Colors.black26, blurRadius: 8, offset: Offset(0,4))
  ],
  gradient: LinearGradient(
    colors: [Colors.blue, Colors.purple],
  ),
)


Incluye:

| Propiedad              | Función                          |
| ---------------------- | -------------------------------- |
| `border`               | Bordes                           |
| `borderRadius`         | Esquinas redondeadas             |
| `boxShadow`            | Sombras                          |
| `gradient`             | Degradado                        |
| `image`                | Imagen de fondo                  |
| `shape`                | Rectángulo o círculo             |
| Propiedad              | Uso                              |
| `opacity`              | Transparencia                    |
| `elevation`            | Sombra material (Cards, Buttons) |
| `clipBehavior`         | Recortar bordes                  |
| `backgroundBlendMode`  | Mezcla de colores                |
| `foregroundDecoration` | Decoración encima                |
| `shape`                | Forma del widget                 |
| `theme`                | Estilo global                    |
| `textStyle`            | Estilo de texto                  |
| `iconTheme`            | Estilo de íconos                 |