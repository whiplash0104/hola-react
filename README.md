# Creación de proyecto

```
npx create-react-app hola-react
cd hola-react
npm start
```

Modificar el archivo src/App.js y dejar este contenido
```
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
