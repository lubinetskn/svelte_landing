<style>
    
</style>
<script>
    let freebet = {
        title:'Розыгрыш автомобилей',
        subTitle:'каждые 3 месяца',
        img:'',
        listTitle:'Краткая механика:',
        list: [
            'Заключение квалификационных пари в клубах БК «Лига Ставок, участвующих в акции',
            'Начисление купонов за каждые 2 222 ₽ и присвоение купонам номеров.',
            'Регистрация на розыгрыш в клубе его проведения.',
            'Определение победного номера купона с помощью шаров и прозрачного барабана.'
        ],
    };
</script>
<section class="Freebet">
    <h2>{freebet.title}</h2>
    <h3>{freebet.subTitle}</h3>
    <img src="" alt="">
    <h4>Краткая механика:</h4>
    <ol>
        {#each freebet.list as item}
            <li>{item}</li>
        {/each}
    </ol>
    <div>
        <h3>Формула расчёта количества купонов:</h3>
        <math>
            <mrow>
            <mrow>
                <msup>
                    <mi>a</mi>
                    <mn>2</mn>
                </msup>
                <mo>+</mo>
                <msup>
                    <mi>b</mi>
                    <mn>2</mn>
                </msup>
            </mrow>
            <mo>=</mo>
            <msup>
                <mi>c</mi>
                <mn>2</mn>
            </msup>
            </mrow>
        </math>
        <h4>Минимальный k = 1,50   Максимальный k = 7,0 копия</h4>
    </div>
    <span>Выше коэффициент – больше купонов – больше шансов выиграть авто</span>
</section>
