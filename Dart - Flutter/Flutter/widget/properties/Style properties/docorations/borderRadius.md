borderRadiu sirve para declarar como va a ser la forma de los bordes del widget al que se le pone este decorador, borderRadius tiene varias opciones para dar forma al borde normalmente redondea los bordes hasta un valor definido.

Eg

Container(
  decoration: BoxDecoration(
    color: Colors.blue,
    // Example: Round all corners
    borderRadius: BorderRadius.circular(20.0),
    // Example: Only round top-left and bottom-right corners
    // borderRadius: BorderRadius.only(
    //   topLeft: Radius.circular(20.0),
    //   bottomRight: Radius.circular(20.0),
    // ),
  ),
  child: ...
)


- **`BorderRadius.all(Radius radius)`**: Applies the same circular or elliptical radius to all four corners.
- **`BorderRadius.circular(double radius)`**: A convenient shortcut for `BorderRadius.all(Radius.circular(radius))`, creating a circular radius for all corners.
- **`BorderRadius.only({...})`**: Allows you to specify different radii for individual corners (`topLeft`, `topRight`, `bottomLeft`, `bottomRight`).
- **`BorderRadius.horizontal({...})`**: Sets the radii for the left and right sides of the rectangle uniformly (e.g., `left: Radius.circular(15.0)`, `right: Radius.circular(30.0)` for all corners on each side).
- **`BorderRadius.vertical({...})`**: Sets the radii for the top and bottom sides uniformly (e.g., `top: Radius.circular(10.0)`, `bottom: Radius.circular(30.0)`