importr React,{useState} from'react';
import'./App.css';
function App(){
const[contor,setContor] = useState(10);
const handleKlik = 0 =>{
setContor(contor +5);
};
return(
<div className="App">
<h1>Valoarea contorului:{contor}<h1>
<button onClick={handleClick}>Apasa-ma</button>
</div>
};
}
export default App;
