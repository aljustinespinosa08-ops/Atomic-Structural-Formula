# Atomic-Structural-Formula
An atomic structural formula is a graphic representation that shows how atoms in a molecule are arranged and chemically bonded to one another. Unlike a simple chemical formula (like H_2O), it maps out the specific physical structure, using lines to represent shared electron bonds between the atomic symbols.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BondQuest</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <h1>BondQuest</h1>
    <h2>Learn Ionic and Covalent Bonding</h2>

    <div id="score">Score: 0</div>

    <div id="question">
        <p>Which bond is formed between Sodium (Na) and Chlorine (Cl)?</p>

        <button onclick="checkAnswer('ionic')">Ionic Bond</button>
        <button onclick="checkAnswer('covalent')">Covalent Bond</button>
    </div>

    <p id="result"></p>
</div>

<script src="script.js"></script>

</body>
</html>