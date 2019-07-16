<script>
	export let firstText, second;
	let srcImg="http://latex.numberempire.com/render?{x}_{1,2}=\frac{-b\pm\sqrt{b^2-4ac}}{2a}"
</script>

<style>
	h1 {
		color: purple;
	}

	.second div{
		border-radius: 6px;
		background-color: #006237;
	}

	.second h3{
		color: #d2d700;
	}

	.second span{
		color: #d2d700;
	}
</style>

<div>
	<section class="first">
		<img src="" alt="">
		<h1>{firstText}</h1>
	</section>

	<section class="second">
		<h2>{second.title}</h2>
		<h3>{second.subTitle}</h3>
		<img src="" alt="">
		<h4>Краткая механика:</h4>
		<ol>
			{#each second.list as item}
				<li>{item}</li>
			{/each}
		</ol>
		<div>
			<h3>Формула расчёта количества купонов:</h3>
			<img src={srcImg} alt="Корни квадратного уравнения">
			<h4>Минимальный k = 1,50   Максимальный k = 7,0 копия</h4>
		</div>
		<span>Выше коэффициент – больше купонов – больше шансов выиграть авто</span>
	</section>

	<section class="third">
		<h2>{third.title}</h2>
		<h3>{third.subTitle}</h3>
		<img src="" alt="">
		<h4>Краткая механика:</h4>
		<ol>
			{#each third.list as item}
				<li>{item}</li>
			{/each}
		</ol>

	</section>
</div>