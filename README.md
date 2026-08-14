<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Para Arleny 💗</title>

<style>

body{
margin:0;
font-family:Arial,sans-serif;
background:linear-gradient(#ffd1e5,#fff5fa);
color:#ff4f91;
text-align:center;
overflow-x:hidden;
}

.container{
padding:30px 20px;
}

.card{
background:white;
max-width:520px;
margin:25px auto;
padding:30px;
border-radius:30px;
box-shadow:0 10px 25px #ffb0cf;
}

h1{
font-size:40px;
}

h2{
color:#ff69a6;
}

p{
font-size:18px;
line-height:1.6;
}

.hello{
font-size:90px;
animation:flotar 2s infinite alternate;
}

button{
background:#ff69a6;
color:white;
border:none;
padding:15px 35px;
border-radius:30px;
font-size:18px;
cursor:pointer;
}

img{
max-width:100%;
}

.carta{
display:none;
background:#fff0f6;
padding:20px;
margin-top:20px;
border-radius:20px;
}

.corazon{
position:fixed;
top:-20px;
font-size:25px;
animation:caer 5s infinite;
}

@keyframes flotar{
from{
transform:translateY(0);
}
to{
transform:translateY(-15px);
}
}

@keyframes caer{
from{
top:-20px;
}
to{
top:100vh;
}
}

</style>

</head>


<body>


<div class="corazon" style="left:10%">💗</div>
<div class="corazon" style="left:30%;animation-delay:2s">💕</div>
<div class="corazon" style="left:60%;animation-delay:1s">💖</div>
<div class="corazon" style="left:80%;animation-delay:3s">💗</div>


<div class="container">


<div class="hello">
🎀
</div>


<h1>
Esto es para ti amorcito 💗
</h1>


<p>
🎀 Una pequeña sorpresa hecha con mucho cariño para mi niña hermosa 🎀
</p>


<div class="card">

<h2>
Para Arleny, mi amorcito ✨
</h2>

<p>
Hice esta página especialmente para ti, para recordarte lo importante que eres para mí.
</p>


<button onclick="abrirCarta()">
💌 Abrir mi cartita
</button>

<div class="card">

<h2>
📸 Nuestros momentos 💗
</h2>

<img src="a2f74d34-5d4f-4389-903e-cc2b5303adaa.jpg">

<p>
Cada recuerdo contigo es algo que guardo con mucho cariño 💕
</p>

</div>



<div class="card">

<h2>
⏳ Nuestro tiempo juntos 💗
</h2>

<p id="contador">
Calculando nuestro tiempo...
</p>

</div>



<div class="card">

<h2>
💗 Lo que amo de ti 💗
</h2>

<img src="279996e2-4a4c-49c4-9720-4e07ac7563b2.jpg">


<p>
Amorcito, quiero que sepas lo mucho que significas para mí.
</p>


<p>
Amo tu forma de ser, tu sonrisa y esos pequeños detalles que te hacen ser tú.
</p>


<p>
Tus ojos tienen algo especial, porque cuando los veo recuerdo muchos momentos bonitos contigo.
</p>


<p>
Gracias por cada risa, cada momento y cada recuerdo que hemos creado juntos.
</p>


<p>
Gracias por ser mi niña hermosa, mi cielo y mi amorcito 💗
</p>


</div>



<div class="card">

<h2>
💗 Cosas que amo de ti 💗
</h2>


<p>
✨ Tu forma de hacerme sonreír
</p>

<p>
✨ Los momentos que compartimos juntos
</p>

<p>
✨ Tu manera de ser
</p>

<p>
✨ Cada recuerdo bonito que tenemos
</p>

<p>
✨ Que seas mi amorcito, mi niña hermosa y mi cielo 💕
</p>


<div class="card">

<h2>
🕷️🎀 Mi Spiderman para ti 💗
</h2>


<img src="339eb499-b297-4b0e-b63e-26b54066a2be.jpg">


<p>
Aunque no tenga poderes de verdad, siempre voy a intentar ser ese Spiderman que cuide tu corazón, te saque una sonrisa y haga tus días un poquito más bonitos. 🕷️💗
</p>


<p>
Siempre voy a querer verte feliz, mi amorcito, mi niña hermosa y mi cielo 🎀
</p>


</div>




<div class="card">

<h2>
💗 Mi promesa para ti 💗
</h2>


<img src="0f704e5a-079d-4bdb-b81e-7dfa8d4384e8.jpg">


<p>
Amorcito, gracias por llegar a mi vida y por todos los momentos que hemos compartido juntos.
</p>


<p>
Prometo seguir valorando cada sonrisa, cada recuerdo y cada instante bonito que tengamos.
</p>


<p>
Quiero seguir siendo esa persona que te saque sonrisas, que te acompañe y que te recuerde lo especial que eres.
</p>


<p>
Gracias por ser mi niña hermosa, mi cielo y mi amorcito 💗
</p>


<p>
Con mucho cariño: Pablo 💕
</p>


</div>


<script>


function abrirCarta(){

document.getElementById("carta").style.display="block";

}



let fechaInicio = new Date("2026-01-18 00:00:00");



function actualizarContador(){


let ahora = new Date();

let diferencia = ahora - fechaInicio;


let dias = Math.floor(diferencia / (1000 * 60 * 60 * 24));


let horas = Math.floor((diferencia / (1000 * 60 * 60)) % 24);


let minutos = Math.floor((diferencia / (1000 * 60)) % 60);



document.getElementById("contador").innerHTML =
"Llevamos juntos 💗<br>" +
dias + " días, " +
horas + " horas y " +
minutos + " minutos ✨";


}


actualizarContador();

setInterval(actualizarContador,60000);



</script>


</body>

</html>
