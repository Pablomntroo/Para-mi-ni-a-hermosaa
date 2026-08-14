<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Para mi princesa 💗</title>

<style>

body{
    margin:0;
    font-family:Arial,sans-serif;
    background:linear-gradient(#ffcce0,#fff5fa);
    color:#ff4f91;
    text-align:center;
    overflow-x:hidden;
}

.container{
    padding:30px 20px;
}

.hello{
    font-size:90px;
    animation:flotar 2s infinite alternate;
}

h1{
    font-size:40px;
}

.card{
    background:white;
    max-width:500px;
    margin:20px auto;
    padding:30px;
    border-radius:30px;
    box-shadow:0 10px 25px #ff9fc4;
}

p{
    font-size:18px;
    line-height:1.6;
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


.carta{
    display:none;
    background:#fff0f6;
    padding:20px;
    margin-top:20px;
    border-radius:20px;
    animation:aparecer 1s;
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


@keyframes aparecer{

from{
opacity:0;
transform:scale(.5);
}

to{
opacity:1;
transform:scale(1);
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


<div class="card">


<h2>
Para Mi bebe tiquita✨
</h2>


<p>
Hice esta página con mucho cariño para ti.
</p>


<p>
Gracias por cada risa, cada momento y cada recuerdo bonito.
</p>


<button onclick="abrirCarta()">
Abrir mi regalo 💌
</button>


<div class="carta" id="carta">

<h2>
💗 Para mi niña hermosa 💗
</h2>>

<p>
Mi amorcito, mi niña hermosa, mi cielo 💗
</p>

<p>
Quiero que sepas que eres una persona muy especial para mí.
Gracias por cada risa, cada momento bonito y cada recuerdo que hemos creado juntos.
</p>

<p>
Hice esta pequeña página porque quería darte algo diferente,
algo que pudiera recordarte lo importante que eres para mí.
</p>

<p>
Siempre voy a guardar con cariño todos nuestros momentos y espero que esto te saque una sonrisa 🎀✨
</p>

</div>


</div>


<div class="card">

<h2>
📸 Nuestros momentos 💗
</h2>

<p>
Aquí guardaré algunos recuerdos bonitos de nosotros ✨
</p>

<img src="a2f74d34-5d4f-4389-903e-cc2b5303adaa.jpg" width="300" style="border-radius:20px;">

<p>
Un recuerdo especial que siempre voy a guardar 💕
</p>

<div class="card">

<h2>
⏳ Nuestro tiempo juntos 💗
</h2>

<p id="contador">
Calculando nuestro tiempo...
</p>

</div>


<script>

function abrirCarta(){

document.getElementById("carta").style.display="block";

} 
let fechaInicio = new Date("2026-01-01 00:00:00");

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
✨ Tu manera de ser y tu personalidad
</p>

<p>
✨ Cada recuerdo bonito que hemos creado
</p>

<p>
✨ Que seas mi amorcito, mi niña hermosa y mi cielo 💕
</p>

</div>

</body>

</html>
