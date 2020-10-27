import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <p>
         APP para organizar evento de torneo de futbol.
        </p>
        <div className="menu">
        <ul>
            <li><a href="Menu">Menu</a></li>
            <li><a href="Historia" target="_blank">Historia</a></li>
            <li><a href="Categorias" target="_blank">Categorias</a></li>
            <li><a href="Resultados" target="_blank">Resultados</a></li>
            <li><a href="Proximos encuentros" target="_blank">Proximos encuentros</a></li>
          </ul>
        </div>
          
       </header>
    </div>
  );
}

export default App;
