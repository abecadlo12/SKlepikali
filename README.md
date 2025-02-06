
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> name= "Srebereko" </title>
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
            font-family: 'Pacificio';
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
            border: 5px solid #b30000; /* Czerwona ramka */
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
            font-family: 'Pacificio', cursive;
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
            color: #b30000;
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
            margin-top: 35px;
            font-size: 90px;
            color: #b30000;
            font-family: 'Pacifico';
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
            margin-top: 60px; /* Dodatkowe przesunięcie tytułu niżej */
        }
    </style>
</head>
<body>
    <h1 class="title"> <img src="https://github.com/user-attachments/assets/41d7213a-1db6-4b80-99e5-7ef170c9a1cb" alt="tytuł"></h1>
    <p style="margin-top: 20px; font-size: 24px; font-weight: bold;font-family: 'Pacificio',">Kwiaty więdną, czekoladki znikają, a biżuteria zostaje na zawsze.</p>
    <div class="static-text"> --------------- </div>
    <div class="static-text"> BIŻUTERIA </div>
    <div class="static-text"> --------------- </div>
    <div class="static-text"> Prezent na dziś, skarb na zawsze. </div>
    <img src="https://github.com/user-attachments/assets/1f40c95c-7f81-4e32-b641-828dd979f8d6" alt="Zdjęcie sklepu">
    <div class="side-images left-side"></div>
    <div class="side-images right-side"></div>
     <p style="margin-top: 20px; font-size: 24px; font-weight: bold;font-family: 'Pacificio';">Z hasłem <span style="color: #b30000;">Thoni-Alutec</span> 10% zniżki!</p>
    <a href="https://www.google.com/maps/place//data=!4m2!3m1!1s0x473d2da806df8d8d:0xb6c8bb17d8b92786?sa=X&ved=1t:8290&ictx=111" target="_blank">Zobacz lokalizację sklepu</a>
   <a href="tel:+48509512989" class="phone-number">📞 W razie pytań Zadzwoń: +48 509 512 989 </a>
     <div class="static-text">Przykładowe oferty walentynkowe (z hasłem): </div>
    <img src="https://github.com/user-attachments/assets/235a39ec-3957-4a85-babc-e26829e40600" alt="zdjęcie oferty">
    <!-- Nowy fragment: Cena przed i po rabacie -->
<p style="margin-top: 10px; font-size: 22px; font-weight: bold;">
    Cena przed rabatem: <s style="color: #b30000;">199 zł</s>  
    <br>
    Cena po rabacie: <span style="color: #008000;">179 zł</span>
</p>
<details style="margin-top: 15px; font-size: 20px; text-align: center;">
    <summary style="cursor: pointer; font-weight: bold; color: #b30000;">
        ℹ️ Informacje o produkcie
    </summary>
    <p style="margin-top: 10px; font-size: 18px; color: #333;">
        - Komplet: kolczyki i zawieszka <br>
        - Materiał: Srebro próby 925 <br>
        - Kamień: Cyrkonia <br>
        
        
    </p>
</details>

    
</body>
</html>


