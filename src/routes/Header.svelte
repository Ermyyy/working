<script>
	import logo from '$lib/images/chees.jpg';
	import { onMount } from 'svelte';
	import gsap from 'gsap';
</script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Butcherman&family=Climate+Crisis&family=Heebo&family=Poppins:wght@600&family=Rubik+Scribble&display=swap');
	* {
		margin: 0;
		padding: 0;
	}
  a {
		text-decoration: none;
		color: rgb(0, 0, 0);
		speak: none;
		font-style: normal;
		font-weight: normal;
		font-variant: normal;
		text-transform: none;
		line-height: 1;
		-webkit-font-smoothing: antialiased;
		font-family: 'Heebo', sans-serif;
	}
	.header-link {
		font-size: 32px;

	}
	.nav-bar {
	}
	.menu-items {
	}
	.menu-item {
		list-style-type: none;
	}
	.menu-item a {
		transition: .3s;
	}
	.menu-item a:hover {
		color: #2E4E92;
	}
	.container {
		max-width: 1780px;
		margin: 0 auto;
	}
	.container-header {
		display: flex;
		align-items: center;
		justify-content: space-between;
		color: #fff;
		text-align: center;
	}
	.container-first {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		min-height: 40vh;
		background-color: #f4f4f4;
		gap: 40px;
		padding: 20px;
	}
	.dish 
	{
		background-color: #fff;
		padding: 20px;
		border-radius: 10px;
		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
		text-align: center;
		max-width: 30%;

	}

	h2,h3,h1,h4 {
		color: #333;
		font-size: 24px;
		margin-bottom: 20px;
		font-family: 'Heebo', sans-serif;
	}
	img {
		width: 300px;
		height: 300px;
		border-radius: 10px;
		object-fit: cover;
		margin-bottom: 20px;
	}
	p {
		font-family: 'Heebo', sans-serif;
		font-size: 14px;
	}
	.recipe {
		margin: auto;
		width: 500px;
		padding: 20px;
		background-color: white;
		border: 2px solid #ddd;
		border-radius: 10px;
  	}
	.content {
		opacity: 1;
	}
</style>
<main>
	<div class="content">
		<header>
			<div class="header">
				<div class="container">
					<div class="container-header">
						<a class="header-link" href="#">Recipe Store</a>
						<nav class="nav-bar">
							<ul class="menu-items">
								<li class="menu-item"><a href="#">Главная</a></li>
							</ul>
						</nav>
					</div>
				</div>
			</div>
		</header>
		<div class="section-one">
			<div class="container-first">
				<div class="dish">
				<h2>Рецепт классического чизкейка</h2>
				<img src={logo} alt="background image" />
				<p>Не ищите больше рецепт классического чизкейка со сливками и ультра-гладкой текстурой! В сочитании с маслянистой корочкой крекера Грэм никто не сможет отрицать его простой декадентский вкус. Для для достижения наилучших результатов выпекайте на водяной бане.
				</p>
		
				</div>
				<div class="recipe">
					<h2>Ингредиенты</h2>
					<h3>Корж для крекеров "Грэм"</h3>
					<p>1 и 1/2 стакана (150 г) - крошки для крекеров "Грэм" (около 10 полных листов крекеров "грэм")</p>
					<p>5 столовых ложек (70 г) - растопленное несоленое сливочное масло</p>
					<p>1/4 стакана (50 г) - гранулированный сахар</p>
				
					<h3>Чизкейк</h3>
					<p>4 блока (904 г) - полножирный сливочный сыр, размягченный до комнатной температуры</p>
					<p>1 стакан (200 г) - гранулированный сахар</p>
					<p>1 стакан (240 г) - полножирная сметана комнатной температуры</p>
					<p>1 чайная ложка - чистый экстракт ванили</p>
					<p>2 чайные ложки - свежий лимонный сок (опционально, но рекомендуется)</p>
					<p>3 шт - яйца при комнатной температуре</p>
				
					<h3>Варианты начинки:</h3>
					<p>соленая карамель, лимонный творог, клубничная посыпка, шоколадный ганаш, шоколадный ганаш из красного вина, свежие фрукты, взбитые сливки или малиновый соус.</p>
				</div>
			</div>
		</div>
	</div>
</main>    