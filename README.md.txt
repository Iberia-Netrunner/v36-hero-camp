HTML:


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="hero">       <!--hero class "Föräldrer", .hero i CSS-->
        <h1>Campus Demos</h1>
        <img src="https://placehold.co/400x200/orange/white" 
         alt="Logotyp för campus demo
         width 400 
         height 200">
        <p class="datum">21 mars 2026</p> <!--datum class "Barnet", .datum i CSS, ärver parents regel-->
        <p class="plats">Campus/Zoom</p> <!--plats class "Barnet", .plats i CSS, ärver parents regel-->
        <p class="tagline">Kodning, övningar och relax</p> <!--datum class "Barnet", .tagline i CSS, ärver parents regel-->
        
    </header>
    
</body>
</html>








CSS:


.hero {
    background-color: #0f3d3e;
    padding: 3rem 1.5rem;
    color: #fde68a;
    font-family: sans-serif;






Vissa egenskaper rinner från förälder till barn, framför allt text:
color och font-family. Box Model gör inte det. padding och
background-color stannar på elementet du stylar.


<!--hero class "Föräldrer", .hero i CSS-->
<!--datum class "Barnet", .datum i CSS, ärver parents regel-->
<!--plats class "Barnet", .plats i CSS, ärver parents regel-->
<!--datum class "Barnet", .tagline i CSS, ärver parents regel-->
Endast färg co htypografi följer med.