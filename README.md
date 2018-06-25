# HTML5/CSS3 - Elemento Centralizado

Centraliza qualquer elemento independente do dispositivo, elemento ou resolução.


## Arquivo
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
