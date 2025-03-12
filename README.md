# Maria-Clara-
Entre Ontem e Sempre 

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Entre Ontem e Sempre</title>
    <style>
        body {
            background-color: #f4e1d2;
            color: #5a3e2b;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #8b5e3b;
        }
        button {
            background-color: #8b5e3b;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }
        button:hover {
            background-color: #5a3e2b;
        }
        .poema {
            display: none;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Entre Ontem e Sempre</h1>
        <button onclick="mostrarPoema()">Clique aqui</button>
        <div class="poema" id="poema">
            <p>Entre ontem e sempre, há um agora<br>
               onde o tempo brinca de se perder,<br>
               onde três meses são mil histórias<br>
               e cada segundo insiste em viver.</p>

            <p>Entre o antes e o depois, há o meio,<br>
               onde teus olhos me fazem casa,<br>
               onde tua voz é um caminho inteiro<br>
               e o teu riso, um sol que não atrasa.</p>

            <p>Entre o instante e o infinito, há nós,<br>
               tecendo momentos que não se apagam,<br>
               fazendo do pouco um tudo tão nosso,<br>
               onde o mundo se cala e as almas falam.</p>

            <p>Entre o começo e o futuro, há um passo,<br>
               o que damos juntos, sem medir,<br>
               porque amar não é contar o tempo,<br>
               é fazer do tempo um lugar pra existir.</p>
        </div>
    </div>

    <script>
        function mostrarPoema() {
            document.getElementById("poema").style.display = "block";
        }
    </script>
</body>
</html>
