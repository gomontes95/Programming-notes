
Puedes crear un archivo de CSS con .module.css para poder crear algo paracido a funciones para poder aplicar css al codigo en JSX. El join tiene que tener por fuerza un espacio entre las comillas.
También en vez de escribir directamente los estilos css en la className puedes agregarlo en una variable

`className={[styles.button, styles.padded].join(" ")}`

`const btnStyle = [styles.button, styles.padded].join(" ");`
`className={btnStyle}`


`.button {`
  `background-color: red;`
`}`

`.padded {`
  `padding: 1rem;`
`}`