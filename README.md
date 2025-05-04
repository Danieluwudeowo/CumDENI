<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background: pink;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        h1 {
            color: white;
            font-size: 3rem;
            margin: 0;
            text-align: center;
            animation: jump 0.5s infinite alternate; /* Se agrega la animación */
        }
        img {
            max-width: 100%;
            max-height: 100vh;
            animation: jump 0.5s infinite alternate;
        }
        @keyframes jump {
            0% { transform: translateY(0); }
            100% { transform: translateY(-20px); }
        }
    </style>
</head>
<body>
    <h1>Feliz Cumpleaños Amorcito :D</h1>
    <img src="cum.jpg" alt="Imagen de cum">
    <audio autoplay loop>
        <source src="Mañanitas.mp3" type="audio/mpeg">
    </audio>
</body>
</html>
