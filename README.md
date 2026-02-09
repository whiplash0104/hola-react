# Creación de proyecto

```
npx create-react-app hola-react
```
Dar "y" o Enter

```
felipe_bas@cloudshell:~ (sa-santiago-1)$ npx create-react-app hola-react
⠴
Need to install the following packages:
create-react-app@5.1.0
Ok to proceed? (y) 
```

Una vez creado el proyecto, modificar el archivo src/App.js y dejar este contenido
```
cd hola-react
import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div style={{ textAlign: "center", marginTop: "40px" }}>
      <h1>Hola React</h1>
      <h2>Felipe Basso, eres el mejor CXM de todos :D</h2>
    </div>
  );
}

export default App;
```

SOLO el archivo Dockerfile debe quedar dentro de la carpeta "hola-react"

