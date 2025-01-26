<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Simples</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 1em 0;
        }
        main {
            padding: 2em;
            text-align: center;
        }
    </style>
</head>
<body>
    <img src="data:image/jpeg;base64,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" >


    <header>
        <h1>Bem-vindo ao site de Vitor Clock</h1>
    </header>

    <main>
        <p>Este é um site simples criado com HTML, é bem simples e mostra como eu entendi o conteúdo</p>
    </main>

    <footer>
        <p>&copy; Talento Tech Vitor Giovani Clock</p>
    </footer>

</body>
</html>
