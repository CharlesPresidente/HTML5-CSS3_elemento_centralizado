# HTML5/CSS3 - Elemento Centralizado

Centraliza qualquer elemento independente do dispositivo, elemento ou resolução.


## Arquivos

### .html

	<!DOCTYPE html>
	<html  lang="pt">
		<head>
			<meta  charset="UTF-8">
			<meta  name="viewport"  content="width=device-width, initial-scale=1.0">
			<meta  http-equiv="X-UA-Compatible"  content="ie=edge">
			<title>Document</title>
		</head>
		
		<body>
			<h1>Elemento centralizado</h1>
		</body>
	</html>

### .css
Destaque para os elementos sinalizados com as setas:

	<style type="text/css">
		body {
			margin: 0;
			padding: 0;
			background-color: #0b0b0b;
		}
		h1 {
			color: white;
			font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
			font-weight: lighter;
			text-align: center;
			position: absolute; <-- 
			top: 50%; <--
			left: 50%; <--
			transform: translateX(-50%) translateY(-50%); <--
		}
	</style>
