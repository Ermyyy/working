<script>
	import logo from '$lib/images/chees.jpg';
	import logos from '$lib/images/muff.jpg';
	
</script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Butcherman&family=Climate+Crisis&family=Heebo&family=Poppins:wght@600&family=Rubik+Scribble&display=swap');
	* {
		margin: 0;
		padding: 0;
	}
	h1,h2,h3 {
		text-align: center;
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
		padding: 20px;
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
		text-align: center;
	}
	.recipe {
		margin: auto;
		width: 500px;
		margin-bottom: 30px;
		padding: 20px;
		background-color: white;
		border: 2px solid #ddd;
		border-radius: 10px;
  	}
	.content {
		opacity: 1;
	}
	main {
    opacity: 0;
    animation: fade-in-out 2s ease-out forwards;
	}
	@keyframes fade-in-out {
		0% {opacity: 0;}
		100% {opacity: 1;}
	}
	header {
		position: relative;
		animation: move 1s ease-out forwards;
	}
	@keyframes move {
		0% { transform: translateY(-100%); }
		40% { transform: translateY(-60%); }
		100% { transform: translateY(0%); }
	}
	.container {
        max-width: 100%;
        padding: 0 10px;
    }

        .dish,
        .recipe {
            max-width: 100%;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        /* Стили для планшетов и десктопов */
        @media only screen and (min-width: 768px) {
            .container {
                max-width: 768px;
                margin: 0 auto;
            }

            .dish,
            .recipe {
                max-width: 48%;
            }
        }

        /* Стили для больших десктопов */
        @media only screen and (min-width: 1200px) {
            .container {
                max-width: 1200px;
            }

            .dish,
            .recipe {
                max-width: 23%;
            }
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
				<p class="parag">Не ищите больше рецепт классического чизкейка со сливками и ультра-гладкой текстурой! В сочитании с маслянистой корочкой крекера Грэм никто не сможет отрицать его простой декадентский вкус. Для для достижения наилучших результатов выпекайте на водяной бане.
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
			<div class="section-one">
				<div class="container-first">
					<div class="dish">
					<h2>Рецепт Маффина</h2>
					<img src={logos} alt="" />
					<p class="parag">
						Американский вариант кекса, маленькая круглая или овальная выпечка, преимущественно сладкая, в состав которой входят разнообразные начинки, в том числе фрукты. Обычно маффин помещается в ладони взрослого человека.

					</p>
			
					</div>
					<div class="recipe">
						<h2>Ингредиенты</h2>
						<h3>Ванильные маффины</h3>
						<p>240 г муки;</p>
						<p>1/2 чайные ложки разрыхлителя;</p>
						<p>200 г сахара;</p>
						<p>2 яйца;</p>
						<p>120 мл молока;</p>
						<p>2 чайные ложки ванильного экстракта или 1½ г ванилина.</p>
						<h3></h3>
						<h2>Ингредиенты</h2>
						<h3>Маффины «Двойной шоколад»</h3>
						<p>240 г муки;</p>
						<p>150 г какао-порошка;;</p>
						<p>150 г сахара;</p>
						<p>¹⁄₂ чайной ложки соли;</p>
						<p>30 г сливочного масла;</p>
						<p>2 яйца;</p>
						<p>300 мл молока;</p>
						<p>80 мл растительного масла;</p>
						<p>1 чайная ложка ванильного экстракта;</p>
						<p>160 г рубленого шоколада.
						</p>
					</div>
				</div>	
			</div>
	</div>
</main>   
