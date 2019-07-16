<script>
	export let firstText, second;
	let srcImg="http://latex.numberempire.com/render?{x}_{1,2}=\frac{-b\pm\sqrt{b^2-4ac}}{2a}"
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<section class="first">
	<img src="" alt="">
	<h1>{firstText}</h1>
</section>

<section class="second">
	<h1>{second.title}</h1>
	<h2>{second.subTitle}</h2>
	<img src="" alt="">
	<h3>{second.listTitle}</h3>
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
