<!DOCTYPE html>
<html>
<head>
    <title>ALERTE ⚠️</title>
</head>
<body>
    <audio autoplay loop>
        <source src="https://www.soundjay.com/button/beep-07.wav" type="audio/wav">
    </audio>
    <script>
        setInterval(() => {
            navigator.vibrate([500, 500, 500]); // Fait vibrer le téléphone en boucle
            alert("⚠️ Virus détecté ! Ne quittez pas cette page !");
        }, 3000);
    </script>
    <h1>🚨 Téléphone en danger !</h1>
</body>
</html>
