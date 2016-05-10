# custom_radio
radion bouton

Jquery librairies


Usage

!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>custom radio</title>
	<link rel="stylesheet" href="css/custom_radio.css" />
	<!-- lien vers la lib jquery -->
	<script src="js/jquery-1.12.3.min.js"></script>

	<script src="js/custom_radio.js"></script>
</head>
<body>

	<div class="custom_radio">
		<input type="radio" name="choix" value="oui" /><label>Oui</label>
		<input type="radio" name="choix" value="non" /><label>Non</label>
		<input type="radio" name="choix" value="peut-etre" /><label>Peut-être</label>
	</div>
	<div class="custom_radio">
		<input type="radio" name="choix" value="homme" /><label>Homme</label>
		<input type="radio" name="choix" value="femme" /><label>Femme</label>
	</div>
	
	<button id="btn">Clic !</button>


</body>
</html>

And that All !