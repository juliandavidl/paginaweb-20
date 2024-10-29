en style css
esta el código establece estilos para un contenedor de cabecera con una imagen de fondo y define características para un logo y un texto descriptivo

:root{
    font-family: Arial, Helvetica, sans-serif;
}
.logo{
    width: 120px;
}
#contener_cabecera{
width: 100%;
    display: flex;
    justify-content : space_evenly;
    align-items: center;{
  }
#contener_cabecera{
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url("./img/meca.jfif");
    background-size:cover ;
    background-repeat: no-repeat;
    height: 500px;
    #descripcion{
        font-size: x-large;
        color: azure#fff;
    }


index.html
este código define la estructura básica de una página web para un portafolio de mecatrónica, con un encabezado que incluye logos y un título

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/style.css" 
    <title>PORTAFOLIO MECATRONICA</title>
</head>
<body>
    <header>
        <div id="contenedor_cabecera">
            <img class="img/logo sena.png"> alt="LOGO SENA">
        <h1 id="titulo">PORTAFOLIO MODALIDAD MECATRONICA</h1>
            <img class="logo" src="./img/logo inem.png"alt="logo INEM">
        </div>
        <div id="contendedor_banner">
            <p id="descripcion">modalidad en articulacion sena</p>
            <div>

     </div>
    </header>
</body>
</html>
