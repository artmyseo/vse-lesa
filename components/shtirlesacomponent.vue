<template>
<div>
    <section class="lesa-section shtir-section" id="shtir-section">
<div class="topbar topbarshtir">
	<div class="container">
		<div class="row">
			<div class="col-md-3">
				<div class="namesection">
					<a href="/shtyrevye-lesa">Штыревые леса</a>
					<div class="snoski hidden-xs">
						<div class="snoska">продажа</div>
						<div class="snoska">аренда</div>
					</div>
				</div>
			</div>
			<div class="col-md-9">
				<div class="input-sources">
					<div class="is-group">
						<label for="countHeight" class="countTitle">Высота</label>
						<div class="countGroup">
							<div class="minus recount active"></div>
							<input class="form-control countItem countHeight" name="countHeight" value="2">
							<div class="plus recount active"></div>
						</div>
					</div>
					<div class="is-group">
						<label for="countLength" class="countTitle">Длина</label>
						<div class="countGroup">
							<div class="minus recount active"></div>
							<input class="form-control countItem countLength" name="countLength" value="3">
							<div class="plus recount active"></div>
						</div>
					</div>
					<div class="is-group">
						<label for="countNastilov" class="countTitle">ЯРУСОВ НАСТИЛОВ</label>
						<div class="countGroup">
							<div class="minus recount active"></div>
							<input class="form-control countItem countNastilov" name="countNastilov" value="1">
							<div class="plus recount active"></div>
						</div>
					</div>
					<div class="btn-showset">
						Дополнительные<br>параметры
					</div>
					<div class="params-panel">
						<div class="pp-inner arenda">
							<div class="row">
								<div class="col-md-6">
									<label for="countArenda">КОЛИЧЕСТВО ДНЕЙ АРЕНДЫ</label>
									<span>Минимальный срок аренды - 30 дней</span>
								</div>
								<div class="col-md-6">
									<div class="is-group">
										<div class="countGroup">
											<div class="minus recount active"></div>
											<input class="form-control countItem countArenda" name="countArenda"  value="30">
											<div class="plus recount active"></div>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="pp-inner">
							<div class="row">
								<div class="col-xs-12">
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Длина верт. стойки</div>
											<select name="shtir_stoika" size="1" class="form-control">
												<option value="0">4 м.</option>
												<option value="1">2 м.</option>
											</select>
										</div>
									</div>
								</div>
							</div>
							<div class="row">
								<div class="col-xs-7">
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Стабилизирующая опора</div>
											<select name="shtir_opora" size="1" class="form-control">
												<option value="0">Нет</option>
												<option value="1">2 м.</option>
												<option value="2">3 м.</option>
												<option value="3">4 м.</option>
												<option value="4">6 м.</option>
											</select>
										</div>
									</div>
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Планка под кронштейн</div>
											<select name="shtir_plankapk" size="1" class="form-control">
												<option value="0">Нет</option>
												<option value="1">300 мм.</option>
												<option value="2">400 мм.</option>
												<option value="3">500 мм.</option>
											</select>
										</div>
									</div>
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Шаг стоек по длине</div>
											<select name="shtir_shagst" size="1" class="form-control">
												<option value="0">3 м.</option>
												<option value="1">2.5 м.</option>
												<option value="2">2 м.</option>
											</select>
										</div>
									</div>
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Хомутовая стяжка</div>
											<input type="number" class="form-control" name="shtir_styagka" value="0">
										</div>
									</div>
								</div>
								<div class="col-xs-5">
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Настил</div>
											<select name="shtir_nastil" size="1" class="form-control">
												<option value="0">Деревянный</option>
												<option value="1">Металлический</option>
											</select>
										</div>
									</div>
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Подъемов</div>
											<input type="number" class="form-control" name="shtir_podjomov" value="1">
										</div>
									</div>
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Ярус огражд.</div>
											<input type="number" class="form-control" name="shtir_yarus" value="0">
										</div>
									</div>
									<div class="form-group">
										<div class="input-group">
											<div class="input-group-addon">Глубина</div>
											<select name="shtir_glubina" size="1" class="form-control">
												<option value="0">1 м.</option>
												<option value="1">1.2 м.</option>
												<option value="2">1.5 м.</option>
												<option value="3">2 м.</option>
											</select>
										</div>
									</div>
								</div>
							</div>
							<div class="form-group">
								<div class="input-group">
									<div class="input-group-addon">Кронштейн/Кронштейн с хомутом?</div>
									<select name="shtir_kronsht" size="1" class="form-control">
										<option value="0">Кронштейн</option>
										<option value="1">Кронштейн с хомутом</option>
									</select>
								</div>
							</div>
						</div>

						<div class="pp-inner closepanel">
							Закрыть доп. параметры
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
	<div class="containerDesc">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<tabs class="nav nav-text nav-stacked">
    					<tab title="Описание">
							<p class="justifyfull">Штыревые строительные леса являются надежными, прочными, способны выдерживать огромные нагрузки. Приспосабливаются под формы стен и рельефов любой сложности. В собранном виде представляют собой конструкцию, состоящую из вертикальных стоек и горизонтальных связей, при этом элементы конструкции соединяются между собой с помощью штырей, приваренных к несущем опорам. Высота установки – от 50 до 100 м. Нагрузка при фасадных работах составляет 200 кг/м&sup2; (при каменной кладке – 500 кг/м&sup2; или 1000 кг/м&sup2; в зависимости от вида штыревых лесов).</p>
							<div class="row">
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_1_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_2_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_3_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_4_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_5_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_6_s.jpg" alt="..."><span></span></a></div>
							
		<div
          v-for="(gorsel, gorselIndex) in gorseller"
          :key="gorselIndex"
          class="col-sm-2 col-xs-4"
          @click="index = gorselIndex"
        >
		  <div class="imagelink">
          	<img width="132" height="100" :src="gorsel.thumb" class="img-thumbnail" />
		  	<span></span>
		  </div>
        </div>
        <LightGallery
          :images="gorseller"
          :index="index"
          :disable-scroll="false"
          @close="index = null"
        />
							
							</div>
						</tab>
						<tab title="Видео">
							<div class="row">
								<div class="col-md-12">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/2Op68fIEkS4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
								</div>
							</div>
						</tab>
					</tabs>	
					
					<div class="discountblock">
						<span>При покупке на сумму от <strong>235 000</strong> <i class="fas fa-ruble-sign"></i></span>
						<div class="discountimage"></div>
					</div>

				</div>
				
			</div>
		</div>
	</div>

<div class="container">
<div class="row">
	<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
		<div class="product" data-id="1">
		<div class="preload_product"><div class="preload_product__spin"></div></div>
			<div class="product-title"><h3>Штыревые леса серии ЛШ-50</h3></div>

			<div class="productblocks">
				<div class="col-sm-6 left">
					<img class="b-lazy image" src="~/assets/img/shtyrevye-lesa/lsh-50.jpg">
				</div>
				<div class="col-sm-6 right">
					<div class="desc">
						<div class="char">
							<strong>Макс. высота:</strong>
							<span>50 м.</span>
						</div>
						<div class="char">
							<strong>Высота яруса:</strong>
							<span>регулируемая</span>
						</div>
						<div class="char">
							<strong>Кол-во ярусов настилов:</strong><br>
							<span>не менее 3 шт.</span>
						</div>
						<div class="char">
							<strong>Шаг яруса вдоль стены:</strong><br>
							<span>1,5 / 2 / 2,5/ 3 м.</span>
						</div>
						<div class="char">
							<strong>Несущая труба:</strong>
							<span>48 мм.</span>
						</div>
						<div class="char">
							<strong>Макс. нагрузка:</strong>
							<span>200 кг/м&sup2;</span>
						</div>
					</div>
				</div>
			</div>


			<div class="clearfix"></div>
			<div class="productbottom">
				<div class="col-sm-6">
					<div class="prices">
						<div class="price mainprice">
							<div class="title-price">Стоимость покупки</div>
							<div class="origprice"><div class="origvalue"></div></div>
							<div class="value shtirValue" id = "checkValueShtir"></div>
							<div class = "discount"><b>-15%</b></div>
						</div>
						<div class="price arendaprice">
							<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
							<div class="value"></div>
						</div>
					</div>
				</div>
				
					<div class="col-sm-6 productbuttons">
						<div class="btn-group " role="group">
							<button type="button" class="btn btn-black-custom report">Комплектация</button>
							<button type="button" class="btn btn-black-custom save">Сохранить</button>
						</div>
						<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa' @click="showModal = true"> Оформить заказ</button>
					</div>
					<input type="hidden" name="datas">
					<input type="hidden" name="datajson">
				
			</div>

		</div>
	</div>
	<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
		<div class="product" data-id="2">
		<div class="preload_product"><div class="preload_product__spin"></div></div>
			<div class="product-title"><h3>Штыревые леса серии ЛШ-100</h3></div>

			<div class="productblocks">
				<div class="col-sm-6 left">
					<img class="b-lazy image" src="~/assets/img/shtyrevye-lesa/lsh-100.jpg">
				</div>
				<div class="col-sm-6 right">
					<div class="desc">
						<div class="char">
							<strong>Макс. высота:</strong>
							<span>100 м.</span>
						</div>
						<div class="char">
							<strong>Высота яруса:</strong>
							<span>регулируемая</span>
						</div>
						<div class="char">
							<strong>Кол-во ярусов настилов:</strong><br>
							<span>не менее 3 шт.</span>
						</div>
						<div class="char">
							<strong>Шаг яруса вдоль стены:</strong><br>
							<span>1,5 / 2 / 2,5/ 3 м.</span>
						</div>
						<div class="char">
							<strong>Несущая труба:</strong>
							<span>57*3 мм.</span>
						</div>
						<div class="char">
							<strong>Макс. нагрузка:</strong>
							<span>200 кг/м&sup2;</span>
						</div>
					</div>
				</div>
			</div>

			<div class="clearfix"></div>
			<div class="productbottom">
				<div class="col-sm-6">
					<div class="prices">
						<div class="price mainprice">
							<div class="title-price">Стоимость покупки</div>
							<div class="origprice"><div class="origvalue"></div></div>
							<div class="value shtirValue"></div>
							<div class = "discount"><b>-15%</b></div>
						</div>
						<div class="price arendaprice">
							<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
							<div class="value"></div>
						</div>
					</div>
				</div>
				
					<div class="col-sm-6 productbuttons">
						<div class="btn-group " role="group">
							<button type="button" class="btn btn-black-custom report">Комплектация</button>
							<button type="button" class="btn btn-black-custom save">Сохранить</button>
						</div>
						<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa' @click="showModal = true"> Оформить заказ</button>
					</div>
					<input type="hidden" name="datas">
					<input type="hidden" name="datajson">
				
			</div>

		</div>
	</div>
</div>
</div>
</section>

<div class="modal-vue">
	  <!-- button show -->
  
  <!-- overlay -->
  <div class="overlay" v-if="showModal" @click="showModal = false"></div>
  
  <!-- modal -->
  <div class="modalty" v-if="showModal">
    <button class="close" @click="showModal = false">x</button>
	<appform />
  </div>
</div>

</div>

</template>

<script>
import { Tabs, Tab } from 'vue-slim-tabs'
import appform from '~/components/appform'

export default {

components: {
    Tabs, Tab, appform
},
data() {
   return{
	showModal: false,
	gorseller: [
      	{ title: "Штыревые леса", url: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_1.jpg", thumb: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_1_s.jpg"},
    	{ title: "Штыревые леса", url: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_2.jpg", thumb: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_2_s.jpg"},
	    { title: "Штыревые леса", url: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_3.jpg", thumb: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_3_s.jpg"},
	    { title: "Штыревые леса", url: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_4.jpg", thumb: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_4_s.jpg"},
	    { title: "Штыревые леса", url: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_5.jpg", thumb: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_5_s.jpg"},
	    { title: "Штыревые леса", url: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_6.jpg", thumb: "https://все-леса.рф/photo/shtyrevye-lesa/shtyrevye_lesa_6_s.jpg"}	  	  	     
    ],
    index: null,
   };
},
  }
</script>

<style scoped>
.modal-vue  {
 display:flex;
 align-items:center;
 justify-content:center;
}	

.modal-vue .overlay {
  position: fixed;
  z-index: 9998;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, .5);
}

.modal-vue .modalty {
  position: fixed;
  width: 600px;
  z-index: 9999;
  left:50%;
  top:50%;
  transform:translate(-50%,-50%);
 padding: 20px 30px;
 background-color: #fff;
}

.modal-vue .close{
  position: absolute;
  top: 10px;
  right: 10px;
}
</style>

