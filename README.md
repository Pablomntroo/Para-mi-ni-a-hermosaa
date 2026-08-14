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
    background:linear-gradient(#ffd6e7,#fff5fa);
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
    box-shadow:0 10px 25px #ffb6d2;
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


<div class="corazon" style="left:10%;">💗</div>
<div class="corazon" style="left:30%;animation-delay:2s;">💕</div>
<div class="corazon" style="left:60%;animation-delay:1s;">💖</div>
<div class="corazon" style="left:80%;animation-delay:3s;">💗</div>


<div class="container">


<div class="hello">
🎀
</div>


<h1>
FELIZ DÍA DEL AMOR 💗
</h1>


<div class="card">

<h2>
Para mi persona especial ✨
</h2>


<p>
Hice esta página con mucho cariño para recordarte lo importante que eres para mí.
</p>


<p>
Gracias por cada momento, cada risa y cada recuerdo.
</p>


<p>
Siempre voy a guardar los momentos bonitos que hemos vivido juntos 💕
</p>


<button onclick="mensaje()">
Te amo 💗
</button>


</div>


</div>


<script>

function mensaje(){

alert("Gracias por existir 💗 Nunca olvides lo especial que eres ✨");

}

</script>


</body>

</html>
