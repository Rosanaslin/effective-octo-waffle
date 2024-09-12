<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reflex Master</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 flex items-center justify-center h-screen text-white">
    <div id="game" class="text-center">
        <h1 class="text-4xl mb-4">Reflex Master</h1>
        <p id="score" class="text-2xl mb-4">Pontuação: 0</p>
        <p id="highScore" class="text-xl mb-4">Recorde: 0</p>
        <p id="lives" class="text-xl mb-4">Vidas: 3</p>
        <div id="game-area" class="relative bg-gray-800 h-64 w-64 mx-auto"></div>
        <button id="start-btn" class="mt-4 px-4 py-2 bg-green-500 rounded">Iniciar Jogo</button>
    </div>

    <script src="app.js"></script>
</body>
</html>
