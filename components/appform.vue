<template>

<!-- app -->
			<form class="orderForm">
				<div class="modal-header">
					<h4 class="modal-title">Оформление заказа</h4>
				</div>
				<div class="modal-body">
					<div class="row">
						<div class="col-md-6 left" style="padding-top: 30px;">
							<div class="form-group">
								<label for="ofinputName">Ваше имя:</label>
								<input type="text" class="form-control" name="name" id="ofinputName" placeholder="например Иван Иванов">
							</div>
							<div class="form-group">
								<label for="ofinputPhone">Ваш телефон:</label>
								<input type="text" class="form-control ofinputPhone phoneInput" name="phone" id="ofinputPhone"
									placeholder="в формате +7 (999) 999-99-99">
							</div>
							<div class="form-group">
								<label for="ofinputEmail">Ваш e-mail:</label>
								<input type="email" class="form-control ofinputEmail" name="email" id="ofinputEmail"
									placeholder="в формате mail@mail.ru">
							</div>
							<p>
								<label class="radio buyRadio">
									<input type="radio" name="ofVariant" data-toggle="radio" value="1" checked>
									<i></i><span class='descCheckbox_buy desc'>Я желаю приобрести леса</span>
								</label>
								<label class="radio rentRadio">
									<input type="radio" name="ofVariant" data-toggle="radio" value="2">
									<i></i><span class='descCheckbox_rent desc'>Я желаю взять леса в аренду</span>
								</label>
								<label class="radio">
									<input type="radio" name="ofVariant" data-toggle="radio" value="3">
									<i></i>
									<span class='desc'>Мне необходима консультация</span>
								</label>
								<input type="hidden" name="dataorder" value="">
							</p>
						</div>
						<div class="col-md-6">
							<div class="descblock">
								<div class="title"></div>
								<div class="image"><img></div>
								<div class="prices">
									<div class='discountedPrice price' style="display:none;">
										<div class="title-price">Стоимость покупки с учетом скидки</div>
										<div class="value"></div>
									</div>
									<div class="price mainprice">
										<div class="title-price">Стоимость покупки</div>
										<div class="hidden hide_const"></div>
										<div class="value">3'630.46</div>
									</div>
									<div class="price arendaprice">
										<div class="title-price">Стоимость аренды</div>
										<div class="value">907.62</div>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="row">
						<div class="col-md-6 quantityDayRent text-center">
							<label>
								Количество дней аренды
							</label>
							<div class="countGroup">
								<div class="minus count active"></div>
								<input class="form-control countItem" name="countArenda" id="countArenda" value="30">
								<div class="plus count active"></div>
							</div>
						</div>
						<div class="col-md-6 amout text-center">
							<label>
								Количество (шт.)
							</label>
							<div class="countGroup">
								<div class="minus count active"></div>
								<input class="form-control countItem quantityTowers" value="1">
								<div class="plus count active"></div>
							</div>
						</div>
					</div>
					<div class="row">
						<div class="checkbox_personalInformation form-group">
						  <label class="custom-control-label" for="personalInformationVseLesa">Я согласен с условиями политики конфиденциальности <a href="https://xn----8sbemb9a1be.xn--p1ai/personal_information.php" target="_blank">Подробнее</a></label>
						  <input type="checkbox" class="personalInformation" name="personalInformation">
						</div>
					  </div>
				</div>
				<div class="modal-footer">
					<button type="submit" class="btn btn-danger-fill-custom plane">Отправить</button>
				</div>
			</form>

</template>

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