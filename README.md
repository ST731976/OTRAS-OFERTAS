
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplicación Horizontal con Imagen y Botón</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .horizontal-app {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .horizontal-column {
            margin-top: 1rem; /* Espacio de 1rem (aproximadamente 16px) arriba de cada columna */
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .horizontal-column img {
            max-width: 80%; /* La imagen ocupa el 80% del ancho disponible */
            margin-right: 0.5rem; /* Espacio de 0.5rem (aproximadamente 8px) a la derecha de la imagen */
        }
        .horizontal-column button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-left: 0.5rem; /* Espacio de 0.5rem (aproximadamente 8px) a la izquierda del botón */
        }
        .horizontal-column button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="horizontal-app">
        <!-- Primera columna horizontal -->
        <div class="horizontal-column">
            <!-- URL de la imagen para la primera columna -->
            <img src="https://finami.es/images/logo.png" alt="Logotipo de Finami">
            <!-- URL del enlace del botón para la primera columna -->
            <button onclick="window.open('https://infinsa.g2afse.com/click?pid=2078&offer_id=1754', '_blank')">Solicitar</button>
        </div>
        <!-- Segunda columna horizontal -->
        <div class="horizontal-column">
            <!-- URL de la imagen para la segunda columna -->
            <img src="https://binixo.es/img/logo.svg" alt="Logotipo de Binixo">
            <!-- URL del enlace del botón para la segunda columna -->
            <button onclick="window.open('https://infinsa.g2afse.com/click?pid=2078&offer_id=1566', '_blank')">Solicitar</button>
        </div>
    </div>
</body>
</html>

