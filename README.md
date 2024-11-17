<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clon de Google</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #fff;
            color: #202124;
        }
        .logo {
            margin-bottom: 20px;
        }
        .logo img {
            width: 272px; /* Aproximadamente el tamaño del logo de Google */
        }
        .search-bar {
            width: 100%;
            max-width: 584px;
            display: flex;
            border: 1px solid #dfe1e5;
            border-radius: 24px;
            padding: 8px 16px;
            box-shadow: 0 1px 6px rgba(32, 33, 36, 0.28);
        }
        .search-bar input {
            width: 100%;
            border: none;
            outline: none;
            font-size: 16px;
        }
        .buttons {
            margin-top: 20px;
            display: flex;
            gap: 10px;
        }
        .buttons button {
            background-color: #f8f9fa;
            border: 1px solid #f8f9fa;
            padding: 10px 20px;
            border-radius: 4px;
            font-size: 14px;
            cursor: pointer;
            color: #5f6368;
        }
        .buttons button:hover {
            background-color: #f1f3f4;
            border: 1px solid #dadce0;
        }
    </style>
</head>
<body>
    <div class="logo">
        <img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" alt="Google Logo">
    </div>
    <div class="search-bar">
        <input type="text" placeholder="Buscar en Google">
    </div>
    <div class="buttons">
        <button>Buscar con Google</button>
        <button>Me siento con suerte</button>
    </div>
</body>
</html>
