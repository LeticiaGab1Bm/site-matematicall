# site-matematicall

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale-1.0">
	<title>OMC</title>
	<link rel="stylesheet" href="style.css">
</head>
	<body>
		<header class="cabecalho">

			<img class="cabecalho-imagem" src="logo-omc.png" alt="logo da omc">

			<ul class="cabecalho-lista">
				<li class="cabecalho-lista-item">Letícia Gabriele n21 2B</li>
			</ul>

		</header>

		<section class="escola">
			<div class="escola-div-conteudo">
				<h2 class="escola-titulo">Sobre a escola</h2>
				<p class="escola-texto">O Estadual Colégio Olindamir Merlim Cluadino, localizado em Fazenda Rio Grande (região metropolitna de Curtiba), é referêncial quando se diz respeito a organização, aprovação e time de professores.</p>
			</div>

			<img class="escola-imagem" src="end-yellow.png" alt="imagem da escola">
		</section>

<!-- segunda seção professores -->

		<section class="professores">
			<h2 class="professor-titulo">Conheça nossos professores:</h2>

			<div class="professores-todos">

				<span></span>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-rosane.jpg" alt="foto da professora Rosane">
					<h3 class="professor-nome">Rosane</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-cleunice.jpg" alt="foto da professora Cleunice">
					<h3 class="professor-nome">Cleunice</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-rone.jpg" alt="foto da professora Rone">
					<h3 class="professor-nome">Rone</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<span></span>
				<span></span>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-ilga.jpg" alt="foto da professora Ilga">
					<h3 class="professor-nome">Ilga</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-odinei.jpg" alt="foto da professor Odinei">
					<h3 class="professor-nome">Odinei</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-evangeline.jpg" alt="foto da professora Evangeline">
					<h3 class="professor-nome">Evangeline</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<span></span>
				<span></span>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-jacinta.jpg" alt="foto da professora Jacinta">
					<h3 class="professor-nome">Jacinta</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-nicolau.jpg" alt="foto da professor Nicolau">
					<h3 class="professor-nome">Nicolau</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-andre.jpg" alt="foto da professor André">
					<h3 class="professor-nome">André</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<span></span>
				<span></span>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-roberta.jpg" alt="foto da professora Roberta">
					<h3 class="professor-nome">Roberta</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-arnaldo.jpg" alt="foto da professor Arnaldo">
					<h3 class="professor-nome">Arnaldo</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<div class="professor-div">
					<img class="professor-imagem" src="foto-marilda.jpg" alt="foto da professora Marilda">
					<h3 class="professor-nome">Marilda</h3>
					<p class="professor-texto">Idade</p>
					<p class="professor-texto">Curso</p>
				</div>

				<span></span>
				<span></span>



			</div>
		</section>

		<footer class="rodape">
			<img class="rodape-imagem" src="logo-escrita-omc.png" alt="símbolo omc">
		</footer>

	</body>
</html>


padding: 0;
}

.cabecalho {
	display: flex;
	justify-content: space-around;
	padding: 24px 0;
	color: white;
}

body {
	background-image: linear-gradient(#000000,#FFF61E);
}

.cabecalho-imagem {
	width: 20%;
}

.cabecalho-lista-item {
	padding: 80px 0;
	display: inline-block;
	margin: 16px 16px;
	font-size: 24px;
}

.escola {
	color: white;
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 24px 0;
}

.escola-imagem {
	width: 30%;
}

.escola-div-conteudo {
	width: 35%;
}

.escola-titulo {
	padding: 24px 0;
}

/*segunda seção*/

.professores {
	color: black;
}

.professor-imagem {
	width: 150px;
	height: 150px;
	margin: 25px 0 0 0;
}

.professor-texto {
	margin: 2px 10px 2px 2px;
}

.professor-div {
	text-align: center;
}

.professor-titulo {
	text-align: center;
	padding: 50px 0;
}

.professores-todos {
	display: grid;
	grid-template-columns: 20% 20% 20% 20% 20%;
}

.rodape {
	background: black;
	text-align: center;
	margin: 12px 0 0 0;
}

.rodape-imagem {
	height: 60px;
	padding: 12px 0;
}
