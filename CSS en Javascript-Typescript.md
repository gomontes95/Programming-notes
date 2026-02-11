Se tiene que instalar: pnpm i styled-components

Ya una vez instalado se importa bajo una variable de un archivo jsx o tsx para que todo lo que sea el css y el codigo este en un solo archivo

Al momento de crear los elementos html tendremos que crear una variable con el nombre que le dimos a la variable de styled-components y con eso podemos crear un elemento html 


import styles from "styled-components";

const Btn = styles.button`

    background-color: red;

    padding: 1rem;

`
    <Btn
      onClick={onClick}
      type="button"
    >
      {children}
    </Btn>
