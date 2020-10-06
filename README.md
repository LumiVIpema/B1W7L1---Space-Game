# B1W7L1---Space-Game

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SpaceShip</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link href="css/style.css" type="text/css" rel="stylesheet">
</head>
<body>
    <div id="goals" class="w-100">
        <h1>Space Puzzel</h1>
    </div>
    <div id="container" class="index">
        <p>Welkom, hier onder vind je 10 puzzels die je kan oplossen door middel van code.</p>
        <p>Elke puzzel heeft een eigen HTML bestand, waar je op een vast plek JavaScript commandos kunt plaatsen</p>
        <p>Er zijn 5 commandos/functies:</p>
        <ol>
            <li>
                <b>spaceShip.moveForward();</b>
                <span class="comment small">// het schip gaat de richting op waar de punt toe wijst</span>
            </li>
            <li>
                <b>spaceShip.moveBackward();</b>
                <span class="comment small">// het schip gaat de richting op waar de punt niet toe wijst</span>
            </li>
            <li>
                <b>spaceShip.rotateRight();</b>
                <span class="comment small">// het schip draait naar rechts, maar beweegt niet</span>
            </li>
            <li>
                <b>spaceShip.rotateLeft();</b>
                <span class="comment small">// het schip draait naar links, maar beweegt niet</span>
            </li>
            <li>
                <b>spaceShip.wait();</b>
                <span class="comment small">// het schip draait en beweegt niet </span>
            </li>
        </ol>

        <p>Sommige puzzels hebben restricties of criteria</p>

        <div class="row">
            <div class="goal col-4 mb-1">
                maxLines: X
            </div>
            <div class="small col-7 ml-2 mb-1 comment">
                // Het maximale aantal regels code die je mag hebben tussen "code  start" en "code  einde". Lege regels, comments, console.log en } worden niet meegeteld
            </div>

            <div class="goal col-4 mb-1">
                maxActions: X
            </div>
            <div class="small col-7 ml-2 mb-1 comment">
                // Het maximale aantal acties die je mag doe.
            </div>

            <div class="goal col-4 mb-1">
                noExtraActions: true
            </div>
            <div class="small col-7 ml-2 mb-1 comment">
                // Nadat het level klaar is (bijv. door de finish te halen), mogen er geen acties zijn die niet uitgevoerd zijn
            </div>

            <div class="goal col-4 mb-1">
                noFailedActions: true
            </div>
            <div class="small col-7 ml-2 mb-1 comment">
                // Je mag bijv niet tegen een muur aankomen of proberen voorbij de rand van het veld te gaan.
            </div>

            <div class="goal col-4 mb-1">
                colorAll: true
            </div>
            <div class="small col-7 ml-2 mb-1 comment">
                // Kleur alle velden
            </div>

            <div class="goal col-4 mb-1">
                allowedFunctions: ...
            </div>
            <div class="small col-7 ml-2 mb-1 comment">
                // Er zijn maar een bepaald aantal commandos/functies die je mag aanroep. Ze staan hier bij vermeld
            </div>
        </div>

        <p class="mt-3">Maak de 9 opdrachten als je daar mee klaar bent en tijd over hebt maak je de bonus puzzel:</p>

        <div class="text-center">
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht01.html">Opdracht 01</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht02.html">Opdracht 02</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht03.html">Opdracht 03</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht04.html">Opdracht 04</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht05.html">Opdracht 05</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht06.html">Opdracht 06</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht07.html">Opdracht 07</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht08.html">Opdracht 08</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Opdracht09.html">Opdracht 09</a>
            <a class="btn  btn-outline-dark btn-lg mb-1" href="Bonus.html">Bonus</a>
        </div>
    </div>
</body>
</html>
