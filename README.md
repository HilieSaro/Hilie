<html lang="fr">
<head>
<meta name="autor" content="Hilie Saro">
<meta name="description" content="page personnel de hilie saro sur le bodybuilding et le culturisme">
<link rel="stylesheet" href="styles/main_style.css">
<style type="text/css">

H2 {
   transform: rotate(-360deg);
   font-size: 3em;
   font-family: Arial;
   margin: 30px auto 12px auto;
   padding: 12px;
   width: 333px;
   border: 10px solid white;
   border-radius: 80px;
   }

H2 {
   text-decoration: underline;
   text-align:center;
   opacity: ;
   color: white;
   }

body {   
   color: #000000;
   background-color: navy;
   }


</style>
<script>

	function swapImage(imgToSwap){
		imgToSwap.src = "images/triceps2.jpg";
		imgToSwap.alt = "Vous survolez mon bouton avec votre souris !";
	}

	function swapBack(imgToSwap){
		imgToSwap.src = "images/triceps1.jpg";
		imgToSwap.alt = "Survolez moi !";
	}

</script>
<script>
    function afficherPosition() {
        var gps = navigator.geolocation.getCurrentPosition(
           function(position){
                var resultat = '';
                var proprietesUtiles = ['latitude', 'longitude', 'accuracy', 'altitude', 'altitudeAccuracy', 'heading', 'speed'];
                for (let i = 0; i < proprietesUtiles.length; i++){
                    let key = proprietesUtiles[i];
                    if (position.coords[key] !== undefined){
                        resultat += key + ': ' + position.coords[key] + '<br>';
                    }
                }
                document.getElementById('resultat').innerHTML = resultat;
            }
        );
    }
</script>
<!--[if lt IE 9]>
   <script src="scripts/html5-ie.js"></script>
<![endif]-->
</head>
<body>
	<header style="background: #ffffff">
		<img alt="tague" src="images/tague.jpg" width="945" height="300">
	</header>
	<br><br>
	<nav>
		<ul>
		    <li><a href="news.html">🌞 Actualités 🌞</a></li>
			<li><a HREF="https://opensea.io/collection/hilie">🔗HILIE NFT💎</A></li>
            <li><a HREF="https://opensea.io/collection/hilie-pfp">🔗HILIE pfp💪</A></li>
			<li><a HREF="https://opensea.io/collection/hilie-nft-prestige">🔗NFT PRESTIGE👑</a></li>
		    <li><a href="contact.html">🌍 Contact 🌍</a></li>
			<li><a href="photos.html">📷 Photos 📸</a></li>
			<li><a href="videos.html">🎥 Vidéos 🎥</a></li>
			</ul>
	</nav>
	<div id="content_id"><h1>BODYBUILDING</h1></div><br><br>
	<h2> HILIE <img style="width: 250px; height: 250px" src="images/triceps1.jpg" onmouseover="swapImage(this);"
onmouseout="swapBack(this);" alt="Survolez moi !"></h2>
	<aside>
		<p>Bienvenue! Attrappe moi...<br>
			<button onclick="afficherPosition()">Clique pour connaître tes coordonnées</button><br><A HREF="https://www.coordonnees-gps.fr/">💎 vérifie sur la carte de France si tu es
				bien chez toi!</A>
    <div id="resultat"></div>
    </p>
	</aside>

<footer>
<img style="width: 25px; height: 25px" src="images/w3cx.jpg" alt="CSS Valide !">
<div style="float: right">
<h3><a href="mentionslégales.html">Droits réservés & Mentions légales</a></h3>
</div>
</footer>
</body>
</html>
