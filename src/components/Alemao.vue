<template>
	<div id="AppSite">
		<body>
			<section class="conteiner__logo">
				<img class="logo" src="../assets/logovnw.svg">
			</section>
			<section class="conteiner__pesquisas">
				<input class="pesquisa" type="text" name="">
				<button class="botao" >alimentação</button>
				<button class="botao" >arte e cultura</button>
				<button class="botao" >beleza e estética</button>
				<button class="botao" >coletivos</button>
				<button class="botao" >educação</button>
				<button class="botao" >esportes e atividades fisicas</button>
				<button class="botao" >ong's</button>
				<button class="botao" >saúde</button>
				<button class="botao" >serviços</button>
				<button class="botao" >transporte</button>
			</section>
			<section class="conteiner__atividade">
				<h1 class="titulo">Casa Brota</h1>
				<p class="subtitulo">Coworking</p>
			</section>
			<section class="conteiner__lista">
				<ul class="minilista">
					<li class="lista">Coworking</li>
					<li class="lista">Design</li>
					<li class="lista">Gráfica</li>
					<li class="lista">Dança</li>
					<li class="lista">Fotografia</li>
					<li class="lista">Produção</li>
				</ul>
			</section>
		</body>
	</div>
</template>
<script></script>
<style scoped>
	#AppSite{
		background-image: url(../assets/fundo.jpg); 
		min-height: 100vh;
	}
	body{
		display: flex;
		flex-wrap: wrap;
	}
	.conteiner__logo{

	}
	.logo{
		width: 20em;
	}
	.conteiner__pesquisas{
		display: flex;
		flex-direction: column;
	}
	.pesquisa{
		width: 10em;
		height: 48px;
		border-radius: 50px;
		border: none;
		font-family: Ministry-Medium;
		font-size: 1.63em;
		color: #2e3192;
		text-align: left;
		padding: 10px;

	}
	.botao{
		width: 10em;
		height: 4em;
		border-radius: 50px;
		font-family: Ministry-Medium;
		font-size: 1.63em;
		color: #ffffff;
		text-align: left;
		margin: 10px;
		padding: 10px;
		fill: solid;
		background: #f26522;
		border-width: 10px;
		border-style: solid;
		border-color: #fcae1b;
	}
	.conteiner__atividade{
		background-image: url(../assets/atividade.jpg);
		background-position: center;
	

		}
	.titulo{
		font-family: Ministry-Heavy;
		font-size: 1.63em;
		color: #ffffff;
		text-align: left;
	}
	.subtitulo{
		font-family: Ministry-MediumItalic;
		font-size: 1.63em;
		color: #ffffff;
		text-align: left;
	}
	.conteiner__lista{
		background: white;
		border-radius: 10px;
		width: 40%;
		display: flex;
	}
	.lista{
		font-size: 15px;
	}
</style>