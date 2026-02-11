Un **StatefulWidget** sí tiene estado interno que puede cambiar en tiempo real.

Se usa cuando:

- Hay interacción del usuario.
    
- Cambia la información en pantalla.
    
- Hay timers, animaciones, inputs, etc.
    

Ejemplo típico: contador.

`class Contador extends StatefulWidget {`
  `@override`
  `_ContadorState createState() => _ContadorState();`
`}`

`class _ContadorState extends State<Contador> {`
  `int contador = 0;`

  `void incrementar() {`
    `setState(() {`
      `contador++;`
    `});`
  `}`

  `@override`
  `Widget build(BuildContext context) {`
    `return Column(`
      `children: [`
        `Text('$contador'),`
        `ElevatedButton(`
          `onPressed: incrementar,`
          `child: Text("Sumar"),`
        `)`
      `],`
    `);`
  `}`
`}`

Aquí ocurre algo clave:

### `setState()`

- Le dice a Flutter: “el estado cambió, vuelve a dibujar”.
    
- Sin `setState`, la UI no se actualiza.
    

---

## Diferencia mental importante

|Concepto|Idea clave|
|---|---|
|Widget|Bloque de construcción de la UI|
|Scaffold|Estructura base de una pantalla|
|Stateless|No cambia internamente|
|Stateful|Tiene datos que cambian y actualizan la UI|

---

## Cómo pensarlo como desarrollador

Cuando diseñas una pantalla en Flutter, te haces esta pregunta:

1. ¿Es parte de la interfaz? → Widget
    
2. ¿Es estructura de pantalla completa? → Scaffold
    
3. ¿Nunca cambia? → Stateless
    
4. ¿Cambia por interacción o lógica? → Stateful