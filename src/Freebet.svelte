<!--<script>
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
</section> -->

<style>
    #freebet{
        background-image: url("images/freebet-back.jpg");
        background-size: cover;
        padding-top:30px;
    }
    h2{
        font-size: 44px;
        font-weight: 700;
    }
    h3{
        display: inline-block;
        font-size: 14px;
        text-transform: uppercase;
        border-radius: 4px;
        color: #003b29;
        background-color: #d2d700;
        padding: 2px 4px;
        font-weight: 700;
    }
    .freebet_formula{
        padding: 25px;
        width: 655px;
        height: 120px;
        border-radius: 6px;
        background-color: #034d2f;
    }
    .freebet_formula .firstline{
        display: flex;
        align-items: center;
    }
    .symbol{
        position: relative;
        padding: 10px;
        top: 3px;
    }
    .freebet_formula .text{
        font-size: 20px;
        color: #d2d700;
        font-weight: 700;
        align-items: center;
        padding-right: 10px;
    }
    .freebet_formula p{
        text-align: center;
    }
    #freebet .page__container{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }
    .freebet_head {
        width: 100%;
        
    }
    .freebet_text{
        font-size: 24px;
        line-height: 26px;
        color: #d2d700;
        font-weight: 700;
        text-align: center;
        padding: 25px 0;
        margin: auto;
    }
    .freebet_picture{
        width: 51%;
        height: 420px;
        padding: 0 30px
    }
    .freebet_picture img{
        height: 100%
    }
    .freebet_list {
        width: 49%;
    }
    .freebet_list p{
        font-size: 24px;
        font-weight: 400;
        margin: 20px 0;
    }
    .freebet_list li{
        display: flex;
        position: relative;
        padding: 8px 75px;
        margin: 20px 0;
        min-height: 60px;
    }
    .freebet_list picture {
        position: absolute;
        left: 0;
        top: 0;
    }
</style>
<section id="freebet">
    <div class="page__container">
        <div class="freebet_head">
            <h2>Розыгрыш фрибетов</h2>
            <h3>каждую месяц</h3>
        </div>
        <div class="freebet_list">
            <p>Краткая механика:</p>
            <ol>
                <li>
                    <picture>
                        <img src="images/card.png" alt="">
                    </picture>
                    <div>1. Получение специальной карточки в клубе БК «Лига Ставок», участвующем в акции.</div>
                </li>
                <li>
                    <picture>
                        <img src="images/sticker.png" alt="">
                    </picture>
                    <div>2. Получение наклейки на карточку за пари от 1 555 ₽.</div>
                </li>

                <li>
                    <picture>
                        <img src="images/pen.png" alt="">
                    </picture>
                    <div>3. Обмен карточки на купоны в день и в клубе проведения розыгрыша.</div>
                </li>

                <li>
                    <picture>
                        <img src="images/baraban.png" alt="">
                    </picture>
                    <div>4. Определение победного купона с помощью прозрачного барабана.</div>
                </li>
                <li>
                    <picture>
                        <img src="images/repeat.png" alt="">
                    </picture>
                    <div>5. Возможность обмена гаджета на фрибет, равный стоимости приза.</div>
                </li>
                 <li>
                    <picture>
                        <img src="images/VIP.png" alt="">
                    </picture>
                    <div>Минимальная сумма пари для участия в VIP-розыгрыше — 10 000 ₽.</div>
                </li>
            </ol>
        </div>
        <div class="freebet_picture">
            <img src="images/freebetd.png" alt="">
        </div>
        <div class="freebet_formula">
            <div class="firstline">
                <span class="text">Формула расчёта количества купонов:</span> общий k <span class="symbol">*</span>
                <span>
                    <table style="border-radius: 50%;text-align:center;">
                        <tr>
                            <td rowspan="2"><span style="font-size: 32px;">(</span></td>
                            <td style="border-bottom:1px solid">сумма пари</td>
                            <td rowspan="2"><span style="font-size: 32px;">)</span></td>
                        </tr>
                        <tr>
                            <td>1 111 Р</td>
                        </tr>
                    </table>
                </span>
            </div>
            <p>Минимальный k = 1,50   Максимальный k = 7,0</p>
        </div>
        <div class="freebet_text">Больше наклеек – больше купонов – больше шансов выиграть один из гаджетов!</div>
    </div>
</section>