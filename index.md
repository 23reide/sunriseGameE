<html>
<link rel="stylesheet" href="months.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="months.js"> </script>
    <body onload="makeMonth()">
        <div class="row">
            <div class="text1">In the month of&nbsp;<span id="month"></span></div>
        </div>
        <div class="row text2">
            the sun rises...
        </div>
        <div class="row">
            <button class="btn" id="neButton" value=2>North of East</button><button class="btn" id="dueEastButton" value=1>Due East</button><button class="btn" id="seButton" value=0>South of East</button>
        </div>
        <div class="text3 row" id="answer">Pick a direction.
        </div>
        <div class="text4 row points" id="win-loss">Points:&nbsp;&nbsp;<span id="points">0</span>
        </div>
        <div class="row">
            <div><button id="monthButton">Change Month</button></div>
        </div>
    </body>
</html>
