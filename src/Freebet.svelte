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
    #gadjet{
        background-color: #083b30;
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
    .gadjet_formula{
        padding: 25px;
        width: 757px;
        height: 120px;
        border-radius: 6px;
        background-color: #006237;
        display:flex;
        margin: 0 0 0 auto;
        align-items: center;
    }
    .gadjet_formula .text{
        font-size: 20px;
        color: #d2d700;
        font-weight: 700;
        align-items: center;
        width: 250px;
        padding-right: 40px;
    }
    .ball-wrap {
        display: flex;
        flex-wrap: wrap;
        margin: 10px 0;
    }
    .ball-wrap h4{
        width: 130px;
    }
    .ball {
        display: flex;
    }
    .ball--round li{
        font-size: 17px;
        font-weight: 400;
        text-align: center;
        background-color: #2da736;
        width: 27px;
        height: 27px;
        line-height: 27px;
        margin-right: 5px;
        border-radius:50%; 
    }
    .ball--squere li{
        font-size: 17px;
        font-weight: 400;
        text-align: center;
        background-color: #2da736;
        width: 32px;
        height: 24px;
        line-height: 27px;
        margin-right: 5px;
    }
    #gadjet .container{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }
    .gadjet_head {
        width: 50%;
        margin: 0 0 0 auto;
        padding-left: 1%;
    }
    .gadjet_text{
        font-size: 24px;
        line-height: 26px;
        color: #d2d700;
        font-weight: 700;
        text-align: center;
        padding: 25px 0;
        margin: auto;
    }
    .gadjet_picture{
        width: 51%;
        height: 420px;
        padding: 0 30px
    }
    .gadjet_picture img{
        height: 100%
    }
    .gadjet_list {
        width: 49%;
    }
    .gadjet_list p{
        font-size: 24px;
        font-weight: 400;
        margin: 20px 0;
    }
    .gadjet_list li{
        display: flex;
        position: relative;
        padding: 8px 75px;
        margin: 20px 0;
        min-height: 60px;
    }
    .gadjet_list picture {
        position: absolute;
        left: 0;
        top: 0;
    }
</style>
<section id="gadjet">
    <div class="container">
        <div class="gadjet_head">
            <h2>Розыгрыш гаджетов</h2>
            <h3>каждый месяц</h3>
        </div>
        <div class="gadjet_picture">
            <img src="images/platform.png" alt="">
        </div>
        <div class="gadjet_list">
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
        <div class="gadjet_formula">
            <div class="text">Формула расчёта количества купонов:</div>
            <div class="ball-group">
                <div class="ball-wrap">
                    <h4>Наклейки, шт.:</h4>
                    <ul class="ball ball--round">
                        <li>7</li>
                        <li>13</li>
                        <li>18</li>
                        <li>22</li>
                        <li>25</li>
                        <li>27</li>
                        <li>28</li>
                    </ul>
                </div>
                <div class="ball-wrap">
                    <h4>Купоны, шт.:</h4>
                    <ul class="ball ball--squere">
                        <li>1</li>
                        <li>2</li>
                        <li>3</li>
                        <li>4</li>
                        <li>5</li>
                        <li>6</li>
                        <li>7</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="gadjet_text">Больше наклеек – больше купонов – больше шансов выиграть один из гаджетов!</div>
    </div>
</section>