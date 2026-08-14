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
Quiero que nunca olvides lo especial que eres para mí, amorcito.
Eres mi niña hermosa, mi cielo, mi mundo mi todo y una persona que ocupa un lugar muy importante en mi corazón.
</p>

<p>
Espero que esta pequeña página te saque una sonrisa ✨
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

<img <img src="a2f74d34-5d4f-4389-903e-cc2b5303adaa".jpg width="300" style="border-radius:20px;">

<p>
Un recuerdo especial que siempre voy a guardar 💕
</p>

</div>


<script>

function abrirCarta(){

document.getElementById("carta").style.display="block";

}

</script>


</body>

</html>
