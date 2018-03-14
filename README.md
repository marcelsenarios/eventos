<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width,initial-scale=1">
	<title>Teste</title>
	<link rel="stylesheet" href="src/css/normalize.min.css">
	<link rel="stylesheet" href="src/css/main.css">
</head>
<body>
	<header>
		<img src="src/img/google-sheets-logo.png" alt="logo for google sheets">
		<h1>Calendário</h1>
	</header>
	<main>
		<div class="information">
			Wagner Fusca
		</div>
		<nav id="filter"></nav>
		<div id="container"></div>
		<div id="notice"></div>
	</main>
	<footer>
		<p>These blog posts are from a Google Sheets backend</p>
		<a href="https://medium.com/p/c2eab3fb0b2b">Read the article on Medium</a>
	</footer>
	<script src="src/js/main.js"></script>
	<script>
		document.addEventListener('DOMContentLoaded', app.init);
	</script>
</body>
</html>
