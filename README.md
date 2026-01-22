<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="autor" content="Hilie Saro">
<meta name="description" content="page personnel de hilie saro sur le bodybuilding et le culturisme">
<title>Hilie</title>
<link rel="stylesheet" href="main_style.css">
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
   color: white;
   background-color: navy;
   }


</style>
<script>

	function swapImage(imgToSwap){
		imgToSwap.src = "triceps2.jpg";
		imgToSwap.alt = "Vous survolez mon bouton avec votre souris !";
	}

	function swapBack(imgToSwap){
		imgToSwap.src = "triceps1.jpg";
		imgToSwap.alt = "Survolez moi !";
	}

</script>
<!--[if lt IE 9]>
   <script src="html5-ie.js"></script>
<![endif]-->
</head>
<body>
	<header style="background: #ffffff">
		<img alt="tague" src="tague.jpg" width="945" height="300">
	</header>
	<br><br>
	<nav>
		<ul>
		    <li><a href="news.html">🌞 Actualités 🌞</a></li>
		    <li><a href="contact.html">🌍 Contact 🌍</a></li>
			<li><a href="photos.html">📷 Photos 📸</a></li>
			<li><a href="videos.html">🎥 Vidéos 🎥</a></li>
			</ul>
	</nav>
	<div id="content_id"><h1>BODYBUILDING</h1></div><br><br>
	<h2> HILIE <img style="width: 250px; height: 250px" src="triceps1.jpg" id="myButton" onmouseover="swapImage(this);"
onmouseout="swapBack(this);" alt="Survolez moi !"></h2>
	<aside>
		<p>
			Bienvenue!
		</p>
	</aside>

<footer> 
<img style="width: 25px; height: 25px" src="../images/w3cx.jpg" alt="CSS Valide !">
<div style="float: right">
Droits réservés<a href="mentionslégales.html">Mentions légales</a>
</div>
</footer>
</body>
</html>
