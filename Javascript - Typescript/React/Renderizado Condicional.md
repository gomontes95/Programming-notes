El renderizado condicional en si es poder renderizar un objeto con una condicion lo normal es que se crea una condición en una constante para poder mostrar algo en el ejemplo siguiente hace que si en una lista esta vacia no muestre nada usando [[Truthy - Falsy]] 
  
  `const contenido = list.length !== 0 && (`
    `<List data={list} onSelect={handleSelect} />`
  `);`
  `return (`
    `<Card>`
      `<CardBody tittle="Hola Mundo" text="Este es el contenido" />`
      `{contenido}`
    `</Card>`
  `);`
`}`
`export default App;`
