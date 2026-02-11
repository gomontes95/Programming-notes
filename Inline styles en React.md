
En React los inlines se escriben con el PascalCase de Javascript dentro de un objeto de javascript. Normalmente tienen menos funcionalidades esto es el legacy para darle soporte a proyectos más antiguos.

const styles = {
    backgroundColor: "red"
}

  

function Button({ children, onClick }: Props) {
  return (
    <button
    style={styles}