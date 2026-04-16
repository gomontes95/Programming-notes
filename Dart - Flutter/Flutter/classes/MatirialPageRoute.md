Es una class que se usa junto con el [[Navigator]] para definir una nueva pantalla o ruta que es insertada en la pila de pantallas de la aplicación. Es la responsable de proveer una adaptativa animación de transción y manejar el ciclo de vida de la pagina de acuerdo a las guias de Material Design.

`Navigator.push(`
  `context,`
  `MaterialPageRoute(`
    `builder: (BuildContext context) => const DetailScreen(), // The new screen widget`
  `),`
`);`
