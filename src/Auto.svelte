<style>
    #automobile{
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
    .automobile_formula{
        padding: 25px;
        width: 757px;
        height: 120px;
        border-radius: 6px;
        background-color: #006237;
        margin: 0 0 0 auto;
    }
    .automobile_formula .text{
        font-size: 20px;
        color: #d2d700;
        font-weight: 700;
        align-items: center;
        padding-right: 10px;
    }
    .automobile_formula .firstline{
        display: flex;
        align-items: center;
    }
    .automobile_formula p{
        text-align: center;
    }
    #automobile .container{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }
    .automobile_head {
        width: 50%;
        margin: 0 0 0 auto;
        padding-left: 1%;
    }
    .automobile_text{
        font-size: 24px;
        line-height: 26px;
        color: #d2d700;
        font-weight: 700;
        text-align: center;
        padding: 25px 0;
        margin: auto;
    }
    .automobile_picture{
        width: 51%;
        height: 420px;
        padding: 0 30px
    }
    .automobile_picture img{
        height: 100%
    }
    .automobile_list {
        width: 49%;
    }
    .automobile_list p{
        font-size: 24px;
        font-weight: 400;
        margin: 20px 0;
    }
    .automobile_list li{
        display: flex;
        position: relative;
        padding: 8px 75px;
        margin: 20px 0;
        min-height: 60px;
    }
    .automobile_list picture {
        position: absolute;
        left: 0;
        top: 0;
    }
</style>
<section id="automobile">
    <div class="container">
        <div class="automobile_head">
            <h2>Розыгрыш автомобилей</h2>
            <h3>каждые 3 месяца</h3>
        </div>
        <div class="automobile_picture">
            <img src="images/car.png" alt="">
        </div>
        <div class="automobile_list">
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
            </ol>
        </div>
        <div class="automobile_formula">
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
                            <td>2 222 Р</td>
                        </tr>
                    </table>
                </span>
            </div>
            <p>Минимальный k = 1,50   Максимальный k = 7,0</p>
        </div>
        <div class="automobile_text">Больше наклеек – больше купонов – больше шансов выиграть один из гаджетов!</div>
    </div>
</section>