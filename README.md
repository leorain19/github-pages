<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Amor para Naiomi🌷</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-image: url('https://photos.app.goo.gl/1rqeMCMvidaze2yA6');
            background-size: cover;
            background-position: center;
            color: #333;
            text-align: center;
            padding: 50px;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        h1 {
            color: #ff69b4;
        }
        input[type="text"] {
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ff69b4;
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #ff69b4;
            color: white;
            cursor: pointer;
            margin-top: 10px;
        }
        .letter {
            display: none;
            background-color: #ffccff;
            padding: 20px;
            border-radius: 10px;
            position: relative;
            animation: fadeIn 2s;
        }
        .letter button {
            background-image: url('https://photos.app.goo.gl/t12eSPvKRHSoMgsv9');
            background-size: cover;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: none;
            position: absolute;
            top: -25px;
            left: 50%;
            transform: translateX(-50%);
        }
        .content {
            display: none;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
            max-width: 600px;
            margin: auto;
        }
        .content::before, .content::after {
            content: '';
            position: absolute;
            top: 10px;
            width: 40px;
            height: 40px;
            background-color: white;
            border-radius: 50%;
        }
        .content::before {
            left: -20px;
        }
        .content::after {
            right: -20px;
        }
        .gallery img {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Página de Amor para Naiomi🌷</h1>
        <input type="text" id="nameInput" placeholder="Introduce tu nombre">
        <button onclick="showLetter()">Ingresar🌷</button>
        <div class="letter" id="letter">
            <button onclick="showContent()"></button>
            <div class="content" id="content">
                <p>Querida Naomi, el amor de mi vida,</p>
                <p>Desde el momento en que te conocí, supe que eras alguien especial. Tu sonrisa ilumina mis días y tu risa es la melodía que alegra mi corazón. Cada momento contigo es un tesoro que guardo con cariño en mi memoria.</p>
                <p>Quiero que sepas que te amo con todo mi ser, por favor perdóname por los errores que he cometido. Te prometo con todo mi corazón que ya no volverá a ocurrir. Sé que no te quiero perder y que te amo, te noto mal, yo sé el daño que causé, pero también sé que te voy a amar hasta después de la muerte. Mi amor por ti es tan profundo como el océano y tan vasto como el cielo. Eres mi compañera, mi confidente y mi mejor amiga. No puedo imaginar mi vida sin ti a mi lado.</p>
                <p>Gracias por ser quien eres, por tu amor incondicional y por llenar mi vida de alegría y felicidad. Eres mi inspiración y mi razón para sonreír cada día.</p>
                <p>Con todo mi amor,</p>
                <p>Davicito</p>

                <h2>Galería de Recuerdos</h2>
                <div class="gallery">
                    <img src="https://photos.app.goo.gl/h3uVUDZMANeDn7Vy5" alt="Descripción del recuerdo 1">
                    <img src="https://photos.app.goo.gl/m9Bq42upRzs5SuWu8" alt="Descripción del recuerdo 2">
                    <img src="https://photos.app.goo.gl/FKprQSAFFttSBjbm7" alt="Descripción del recuerdo 3">
                    <img src="https://photos.app.goo.gl/jHDnDnoGrmaGRNXT8" alt="Descripción del recuerdo 4">
                    <img src="https://photos.app.goo.gl/sHtbaxoUGYsKM9wv5" alt="Descripción del recuerdo 5">
                    <img src="https://photos.app.goo.gl/sBks1E8stKCWLpDJ9" alt="Descripción del recuerdo 6">
                    <img src="https://photos.app.goo.gl/oT3st6o6GijEGbrn8" alt="Descripción del recuerdo 7">
                </div>

                <p>Querida Naomi,</p>
                <p>Si aceptas perdonarme, de verdad quiero que sepas que no te voy a fallar y quiero que sepas que no voy a cometer otra estupidez. Con esta cartita te demuestro todo lo que estoy dispuesto a hacer por recuperar a la niña que tanto amo. Si así lo deseas, estoy aquí para apoyarte y estar contigo en las buenas y en las malas, mi niña. Estoy emocionado por todo lo que el futuro nos depara y por todos los momentos maravillosos que aún están por venir. Te amo más de lo que las palabras pueden expresar y siempre estaré aquí para ti.</p>
                <p>Con todo mi corazón,</p>
                <p>Tu negrito, Leito❤️‍🩹</p>
            </div>
        </div>
    </div>

    <script>
        function showLetter() {
            const name = document.getElementById('nameInput').value;
            if (name) {
                document.getElementById('letter').style.display = 'block';
            }
        }

        function showContent() {
            document.getElementById('content').style.display = 'block';
        }
    </script>
</body>
</html>
