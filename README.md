<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="../CSS/style.css" rel="stylesheet" >
        <title>Document</title>
</head>
<body>
        <div class="contenedor">
            <h1> 𝓢𝓽𝔂𝓵𝓮 𝓪𝓽 𝓕𝓪𝓼𝓱𝓲𝓸𝓷</h1>
            <nav>
                <a href="#">Inicio</a>
                <a href="#">Nosotros</a>
                <a href="#">Contactanos</a>
            </nav>
        </div>
        <header>
            <img src="../Imagenes/imagen 2.jpeg" width="1020" height="400">
        </header>
        <section>
            <h2>MODELOS</h2>
        <img src="../Imagenes/imagen 4.jpg"width="250" height="150">
            <img src="../Imagenes/images 3.jpg"width="250" height="150">
            <img src="../Imagenes/txt.jpg"width="250" height="150">
        </section>
        <div class="contenedor2">
            
        </div>

</body>
</html>

body{
background: linear-gradient(#000,#dc143c
}
 
.contenedor{
    text-align: center;
     display: flex;
     background-color: aliceblue;
     height: 11vh;
     position: fixed;
     width: 100%;
}

h1{
    margin-top: 0px;
    text-align: left;
    font-size: 45px;
    color: #dc143c;
    margin-left: 10px;
    animation-name: moverTitulo;
    animation-duration: 8s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
    overflow: hidden;

}
h1:hover{
        animation-play-state: paused;
    }
    @keyframes moverTitulo{
        0%{
              transform: translateX(100%)
        }
        20%{
              transform: translateX(0%);
        }
        50%{
              transform: translate(2%,20%)
        }
        75%{
              transform: translate(0,10%)
        }
}


nav{
margin-right: 10px ;
margin-left:900px ;
margin-top: 30px;
position: fixed;
}

nav a{  
text-decoration: none;
margin-right: 10px;
padding: 10px;
font-size: 20px;
color: #000;
width: 40%;
}
nav a:hover{
    background: linear-gradient(#fd003f,
    border-radius: 10px;
    
}
header{
    text-align: center;
    width: 100%;
}
header img{
    margin-top: 100px;
    text-align: center;
    width: 89%;
}
section{
text-align: center;

}
h2{
    text-align: center;
    font-size: 30px;
    color: aliceblue;
}

section img{
    text-align: center;
}
section img:hover{
  border-radius: 30px;
}
.contenedor2{
height: 140vh;
}






