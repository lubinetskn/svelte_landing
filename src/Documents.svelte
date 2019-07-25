<style>
	#documents{
		padding-top: 60px;
		padding-bottom: 50px;
		background-color: #083b30
	}
	.btns{
		display: flex;
	    justify-content: space-between;
	}
	.btns li{
		margin-bottom: 20px;	
	}
	.btns li a{
		display: inline-block;
        border-radius: 5px;
        background-color: #2da736;
        margin: auto;
		text-align: center;
		text-transform: uppercase;
        padding-top: 16px;
        padding-left: 77px;
        padding-right: 47px;
        padding-bottom: 16px;
        box-sizing: border-box;
 		color: #fff;

        background-image: url("images/ico-pdf.png");
        background-position: 30px center;
        background-repeat: no-repeat;
    }
    .btns  span{
        color: #fff;
	}
	
	@media (max-width: 1000px) {
        .btns{
    		flex-flow: wrap;
		}
		.btns li{
			width: 50%;
			text-align: center;
		}
		.btns li a{
			width:240px;
		}
    }
</style>
<section id="documents">
	<div class="page__container">
		<ul class="btns">
			<li><a href="pr.pdf"><span class="ico ico--pdf"></span>Призовой фонд</a></li>
			<li><a href="pr.pdf"><span class="ico ico--pdf"></span>КЛУБЫ ПРИЁМА ПАРИ</a></li>
			<li><a href="pr.pdf"><span class="ico ico--pdf"></span>Календарь розыгрышей</a></li>
			<li><a href="pr.pdf"><span class="ico ico--pdf"></span>условия акции</a></li>
		</ul>
	</div>
</section>