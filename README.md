<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>му ℓσνє 𝐕 ᥫ᭡ </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://i0.wp.com/dailyanimeart.com/wp-content/uploads/2015/04/stand-guard-ichigo-orihime-by-mai-kuu1.png?fit=1200%2C729&ssl=1');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            text-align: left;
            padding: 50px;
            max-width: 800px;
            margin: 0 auto;
        }
        h1 {
            color: #FFC0CB;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7), 0 0 10px rgba(255, 255, 255, 0.5), 0 0 20px rgba(255, 255, 255, 0.3), 0 0 15px rgba(255, 192, 203, 0.8), 0 0 30px rgba(255, 192, 203, 0.5), 0 0 40px rgba(255, 192, 203, 0.7), 0 0 50px rgba(255, 192, 203, 0.4);
            text-align: center;
            font-size: 3em;
            font-weight: bold;
            margin-bottom: 30px;
        }
        p {
            color: #fff;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
            margin-bottom: 15px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 5px;
        }
        .italics {
            font-style: italic;
        }
        .center-content {
            text-align: center;
        }
        button {
            padding: 10px 20px;
            background-color: #FFC0CB;
            color: white;
            border: none;
            cursor: pointer;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3), 0 0 10px rgba(255, 192, 203, 0.8), 0 0 20px rgba(255, 192, 203, 0.5);
        }
        button:hover {
            background-color: #FFB6C1;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3), 0 0 15px rgba(255, 192, 203, 0.9), 0 0 25px rgba(255, 192, 203, 0.6);
        }
        #noButton {
            position: relative;
        }
        #mensaje {
            color: #fff;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
        }
        #mensaje p {
            margin-bottom: 10px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>ᴍɪ ᴘʀɪɴᴄᴇꜱᴀ</h1>
    <p class="italics">Desde hace tiempo he estado pensando en lo muchisimo que significas para mi, en todo lo que hemos compartido, por poco o mucho que parezca, me haz hecho sentir cosas que no sentía hace tiempo. No estoy escribiendo esto solo por impulso ni para sonar bonito, sino porque realmente quiero que sepas lo que siento y lo que quiero contigo.</p>
    <p class="italics">Desde que empezamos a hablar, las cosas cambiaron. Poco a poco me fui dando cuenta de que me gustaba hablar contigo, que me hacía bien, que lo necesitaba. Estar en llamada contigo se volvió una de mis partes favoritas del día. Me siento tranquilo, me siento yo, y eso no me pasa con cualquiera.</p>
    <p class="italics">Sé que no llevamos una eternidad conociéndonos, pero siento que en este tiempo pasaron cosas que valen más que la cantidad de días. Me hiciste sentir acompañado, escuchado, y me di cuenta de que quiero estar contigo de una forma mas seria. No es algo q lo diga asi nda mas y tampoco estoy buscando una relación solo por tenerla.</p>
    <p class="italics">Queria preguntarte algo q ya me da muchisima pena pero es lo del final. No te prometo que todo será perfecto, porque no lo va a ser, pero sí te prometo que voy a dar lo mejor de mí. Quiero que sepas que, si estás conmigo, no te va a faltar nada. No te va a faltar ni tiempo, ni cariño, ni amor.</p>
    <p class="italics">Me importas, me gustas, y me encantaría poder compartir todo esto contigo, no solo como alguien que te aprecia, sino como alguien que quiere algo de verdad a tu lado. Gracias por hacerme sentir tan bien en tan poco tiempo, este tiempo contigo ha sido de lo mejor que me ha pasado.</p>
    <div class="center-content">
        <p class="italics">¿Puedo ser tu novio?<br>
        Puedo ser esa persona que esté para ti, que te apoye, que te escuche, que te acompañe en lo bueno y en lo difícil también?</p>
        <button id="siButton" onclick="cambiarTexto()">Sí</button>
        <button id="noButton" onmouseover="moverBoton()">No</button>
    </div>
    <div id="mensaje"></div>
    <script>
        function cambiarTexto() {
            document.getElementById("mensaje").innerHTML = `
                <p>Gracias por decir que sí. En serio, gracias por confiar en mí, por aceptarme ser tu pareja, aunque apenas comienza, ya significa muchísimo para mi.</p>
                <p>Te prometeria mil cosas aunque solo sean palabras y proximamente te lo demuestro con hechos, pero sí te prometo algo real: compromiso, respeto, cuidado y tiempo. Prometo darte lo mejor de mí, incluso en los días que me sienta para la mierda.</p>
                <p>Te aviso que no te quiero para pasar el rato, ni por llenar un vacio, te quiero para darte todo lo que te mereces, el amor que te mereces, demostrarte como de verdad tienes que ser tratada. Algo que tenga sentido, que crezca cada vez mas con el tiempo.</p>
                <p>Me importas muchisiimoo mas de lo que imaginás, por vos estoy dispuesto a dar mucho, basicamente todo. No porque lo sienta como una obligación, sino porque yo quiero hacerlo. Porque cuando alguien te hace sentir bien con solo estar, lo mínimo que uno puede querer es hacer lo mismo por ella.</p>
                <p>Quiero cuidarte, apoyarte, estar siempre para vos, quiero ser tu paz, no causarte caos. Porque algo que lo tengo claro, es que vale la pena intentarlo contigo. Gracias por darme esta oportunidad. No la pienso desaprovechar.</p>
            `;
            document.getElementById("noButton").style.display = "none";
        }

        function moverBoton() {
            const button = document.getElementById("noButton");
            const maxX = window.innerWidth - button.offsetWidth - 20;
            const maxY = window.innerHeight - button.offsetHeight - 20;
            let randomX, randomY;
            do {
                randomX = Math.floor(Math.random() * maxX);
                randomY = Math.floor(Math.random() * maxY);
            } while (randomX > 200 && randomX < maxX - 200 && randomY > 100 && randomY < maxY - 100); // Evita el área central para no superponerse al texto
            button.style.left = randomX + "px";
            button.style.top = randomY + "px";
            button.style.position = "absolute";
        }
    </script>
</body>
</html>

