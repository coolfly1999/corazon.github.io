<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>corazon</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #0b1522;
        }

        .heart {
            height: 200px; /* Ajustado a un tamaño más grande */
            width: 200px;  /* Ajustado a un tamaño más grande */
            background-color: red;
            position: relative;
            transform: rotate(45deg);
            box-shadow: -20px 20px 150px #f20044;
            animation: palpitar 0.5s linear infinite alternate;
        }

        .contenido {
            position: fixed;
            margin-bottom: 50px;
            text-align: center;
        }

        h3 {
            color: white;
            font-size: 20px;
            line-height: 1.6;
            padding: 20px;
        }
        h1 {
            color: #f20044;
            font-size: 28px;
            font-weight: bold;
            margin-top: 100px;
        }

        @keyframes palpitar {
            0% {
                transform: rotate(45deg) scale(1.10);
            }

            80% {
                transform: rotate(45deg) scale(1.0);
            }

            100% {
                transform: rotate(45deg) scale(0.8);
            }
        }

        .heart::before {
            content: "";
            position: absolute;
            height: 200px; /* Ajustado a un tamaño más grande */
            width: 200px;  /* Ajustado a un tamaño más grande */
            background: red;
            right: 50%;
            border-radius: 50%;
            box-shadow: 20px 20px 150px #f20044;
        }

        .heart::after {
            content: "";
            position: absolute;
            height: 200px; /* Ajustado a un tamaño más grande */
            width: 200px;  /* Ajustado a un tamaño más grande */
            background: red;
            top: -50%;
            border-radius: 50%;
            box-shadow: 20px 20px 150px #f20044;
        }
    </style>
</head>

<body>
    <div class="heart"></div>
    <div class="contenido">
        <h3>
            
Desde el día en que te conocí, desde entonces te fui queriendo poco a poco, hasta que decidí quererte como yo no suelo hacerlo. Eres una de las cosas más increíbles que me pudo haber pasado. Gracias por enseñarme que se puede comenzar de nuevo. Gracias por estar ahí, cuando te necesitaba, llegaste a mi vida cuando menos lo esperaba, y hay algo que quiero dejarte claro, quiero estar ahí en los buenos y malos momentos, quiero que me dejes describir tu belleza. Déjame volver a ganar tu confianza para que puedas tener esperanza, déjame cuidarte para poder ayudarte, déjame ser nadie para poder volver a ser alguien, permíteme tocar tu corazón con mis manos heladas, te prometo que nadie te hará daño nunca más. Nunca volverás a estar sola, nunca voy a soltarte, quizá no pueda ofrecerte mucho, pero solo espero que confíes en mí, desde que llegaste a mi vida has mejorado mi mundo y me has ayudado a mejorar. ¿Y sabes?... todo de ti me fascina, está bien en la forma en que eres, la paz que me trasmites es lo más lindo que puedo tener en mi vida, eres una persona muy especial e importante en mi vida, una persona que me pareció increíble de conocer, te quiero libremente, sin tiempos, sin ataduras, definitivamente te quiero como eres y quien eres conmigo, alguien que me hace sentir bien, y quiero cuidarte el resto de mi vida.
        </h3>
        <h1> ¡TE QUIERO INMENSAMENTE!</h1>
    </div>
</body>
</html>
