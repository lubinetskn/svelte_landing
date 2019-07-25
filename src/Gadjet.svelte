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
    .ball--square li{
        font-size: 17px;
        font-weight: 400;
        text-align: center;
        background-color: #2da736;
        width: 32px;
        height: 24px;
        line-height: 27px;
        margin-right: 5px;
    }
    #gadjet .page__container{
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
    .gadjet_list p {
        font-size: 24px;
        font-weight: 400;
        margin: 20px 0;
    }
    .gadjet_list li h3 {
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
    @media (max-width: 1000px) {
        #gadjet .page__container{
            align-items: center;
        }
        #gadjet{
            padding-left: 16px;
            padding-right: 16px;
         }
        .gadjet_head {
            width: 100%;
            margin: 0;
        }
        .gadjet_formula{
            width: 50%;
            order: 1;
            overflow:hidden;
            margin: 0;
            flex-flow: column;
            padding: 20px 10px;
            align-items: flex-start;
        }
        .gadjet_formula .text{
            width:auto;
            padding-right: 0;
            font-size: 18px;
        }
        .gadjet_picture{
            order:2;
            height: auto;
            width: 50%;
            align-items: center;
            vertical-align: middle;
        }
        .gadjet_picture img{
            height: auto;
        }
        .gadjet_list{
            order:4;
        }
        .gadjet_text{
            order: 5;
        }
        .ball-wrap h4{
            width: 90px;
            font-size: 14px;
        }
        .ball--square li{
            font-size:12px;
            width:26px;
        }
        .ball--round li{
            width:22px;
        }
    }
</style>
<section id="gadjet">
    <div class="page__container">
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
                    <ul class="ball ball--square">
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