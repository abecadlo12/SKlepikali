
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sreberko - Sklep z modną biżuterią</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
        
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #fae3e3; /* Beżowo-różowe tło */
            background-image: url('walentynkowe-tlo.png'); /* Motyw serduszek */
            background-size: cover;
            background-position: center;
            text-align: center;
            font-family: 'Lobster', cursive;
            padding-top: 20px;
        }
        .side-images {
            position: absolute;
            top: 0;
            bottom: 0;
            width: 150px;
            background-size: contain;
            background-repeat: no-repeat;
        }
        .left-side {
            left: 0;
            background-image: url('serduszka-lewe.png'); /* Obraz serduszek po lewej stronie */
        }
        .right-side {
            right: 0;
            background-image: url('serduszka-prawe.png'); /* Obraz serduszek po prawej stronie */
        }
        img {
            max-width: 90%;
            height: auto;
            border-radius: 10px;
            border: 5px solid #ff6f61; /* Czerwona ramka */
        }
        a {
            display: block;
            margin-top: 20px;
            font-size: 24px;
            text-decoration: none;
            color: #ff3b3b;
            font-weight: bold;
            background: #fff0f0;
            padding: 10px 20px;
            border-radius: 15px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
        a:hover {
            background: #ff6f61;
            color: white;
        }
        .static-text {
            margin-top: 20px;
            font-size: 24px;
            color: black;
            font-family: 'Lobster', cursive;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
        .text-controls {
            margin-top: 20px;
        }
        .phone-number {
            margin-top: 20px;
            font-size: 24px;
            font-weight: bold;
            color: #ff3b3b;
            text-decoration: none;
            background: #fff0f0;
            padding: 10px 20px;
            border-radius: 15px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
        .phone-number:hover {
            background: #ff6f61;
            color: white;
        }
        .title {
            font-size: 50px;
            color: #b30000;
            font-family: 'Lobster', cursive;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
            margin-top: 60px; /* Dodatkowe przesunięcie tytułu niżej */
        }
    </style>
</head>
<body>
    <h1 class="title">Sreberko</h1>
    <p>Kwiaty zwiędną, czekoladki znikną w kilka chwil, a pluszowe misie trafią na półkę. Biżuteria? Ona pozostanie – jako symbol miłości, elegancji i wyjątkowych chwil.</p>
    <img src="https://github.com/user-attachments/assets/986c7102-3b3d-4572-91d7-c66ec199f588" alt="Zdjęcie sklepu">
    <div class="side-images left-side"></div>
    <div class="side-images right-side"></div>
     <div class="static-text">Sklep znajduję się wewnątrz Hali Targowej w Stalowej Woli </div>
    <a href="https://www.google.com/maps/place//data=!4m2!3m1!1s0x473d2da806df8d8d:0xb6c8bb17d8b92786?sa=X&ved=1t:8290&ictx=111" target="_blank">Zobacz lokalizację sklepu</a>
   <div class="static-text">Godziny otwarcia: </div>
    <div class="static-text">Poniedziałek-Piątek </div>
    <div class="static-text">09:00-17:00 </div>
    <div class="static-text">Sobota </div>
    <div class="static-text">09:00-13:00 </div>
    <a href="tel:+48509512989" class="phone-number">📞 W razie pytań Zadzwoń: +48 509 512 989 </a>
    <p style="margin-top: 20px; font-size: 24px; font-weight: bold;">Z hasłem <span style="color: #d10056;">Thoni-Alutec</span> 10% zniżki!</p>
</body>
</html>


