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
    margin:25px auto;
    padding:30px;
    border-radius:30px;
    box-shadow:0 10px 25px #ffb0cf;
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
Esto es para mi amorcito 💗
</h1>


<p>
🎀 Una pequeña sorpresa hecha con mucho cariño para mi niña hermosa 🎀
</p>



<div class="card">

<h2>
Para Arleny, mi amorcito ✨
</h2>

<p>
Hice esta página para recordarte lo especial que eres para mí.
</p>

<p>
Gracias por cada risa, cada momento bonito y cada recuerdo que hemos creado juntos.
</p>


<button onclick="abrirCarta()">
💌 Abrir mi cartita
</button>



<div class="carta" id="carta">

<h2>
💗 Para mi niña hermosa 💗
</h2>

<p>
Amorcito, mi cielo, mi niña hermosa.
</p>

<p>
Quiero que nunca olvides lo importante que eres para mí.
Gracias por formar parte de mi vida y por todos los momentos que hemos compartido.
</p>

<p>
Espero que esta pequeña sorpresa te saque una sonrisa 💗
</p>

</div>


</div>




<div class="card">

<h2>
📸 Nuestros momentos 💗
</h2>


<img src="a2f74d34-5d4f-4389-903e-cc2b5303adaa.jpg" width="300" style="border-radius:20px;">


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


<img src="279996e2-4a4c-49c4-9720-4e07ac7563b2.jpg" width="300" style="border-radius:25px;">


<p>
Amorcito, quiero que sepas lo mucho que significas para mí.
</p>


<p>
Amo tu forma de ser, tu sonrisa y esos pequeños detalles que te hacen ser tú.
</p>


<p>
Tus ojos tienen algo especial y cada vez que los veo recuerdo momentos bonitos contigo.
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


<p>✨ Tu forma de hacerme sonreír</p>

<p>✨ Los momentos que compartimos juntos</p>

<p>✨ Tu manera de ser</p>

<p>✨ Cada recuerdo bonito que tenemos</p>

<p>✨ Que seas mi amorcito, mi niña hermosa y mi cielo 💕</p>


</div>



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
