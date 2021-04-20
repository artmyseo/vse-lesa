<template>
<div>

	<section class="about-block">
		<div class="container">
			<div class="title-block">
				<h1>Производственная компания ООО "ПК МДН-Пром"</h1>
				<span></span>
			</div>
			<div class="row">
				<div class="col-md-8 col-lg-9">
					<p class="description justifyfull">
						
						Производственная компания ООО "ПК МДН-Пром" уже
						более 10 лет занимается производством металлоконструкций различных видов: строительных лесов,
						вышек-тур, остановочных, курительных, павильонов для паркоматов, теплиц, вольеров, ограждений и
						др. При производстве большое внимание уделяется качеству продукции, поэтому у нас работают
						высококвалифицированные специалисты, имеется современное профессиональное оборудование, а также
						мы используем качественное сырье и материалы.</p>
				</div>
				<div class="col-md-4 col-lg-3 rightlinks">
					<button class="btn btn-about why fastlink" data-linkto=".how-work">Как мы работаем</button><br>
					<button class="btn btn-about where fastlink" data-linkto=".mapCont">Где мы находимся</button>
				</div>
			</div>
			<hr>
			<div class="row why-blocks">
				<div class="col-md-2 col-md-offset-1 col-xs-6 block">
					<div class="title">Собственное<br>производство</div>
					<div class="icon i-1"></div>
				</div>
				<div class="col-md-2 col-xs-6 block">
					<div class="title">Доставка<br>по России</div>
					<div class="icon i-2"></div>
				</div>
				<div class="col-md-2 col-xs-6 block">
					<div class="title">Гарантия<br>на продукцию</div>
					<div class="icon i-3"></div>
				</div>
				<div class="col-md-2 col-xs-6 block">
					<div class="title">Более 11<br>лет работы</div>
					<div class="icon i-4"></div>
				</div>
				<div class="col-xs-6 col-xs-offset-3 col-md-2 col-md-offset-0 block">
					<div class="title">Паспорта<br>и сертификаты</div>
					<div class="icon i-5"></div>
				</div>
			</div>
		</div>
	</section>

  	<section class="lesa-section rama-section" id="rama-section">
	<div class="topbar topbarrama">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<div class="namesection">
						<a href="/ramnye-lesa">Рамные леса</a>
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
							<div class="fa-2x" style="float:left; margin: 0 10px 0 -40px;"><i class="fas fa-cog fa-spin"></i></div>Дополнительные<br>параметры
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
												<input class="form-control countItem countArenda" name="countArenda" value="30">
												<div class="plus recount active"></div>
											</div>
										</div>
									</div>
								</div>
							</div>
							<div class="pp-inner">
								<div class="row">
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Планка под кронштейн</div>
												<select name="rama_plankapk" size="1" class="form-control">
													<option value="0">Нет</option>
													<option value="1">300 мм.</option>
													<option value="2">400 мм.</option>
													<option value="3">500 мм.</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Домкрат/подпятник</div>
												<select name="rama_podp" size="1" class="form-control" disabled>
													<option value="0">Подпятник</option>
													<option value="1">Домкрат</option>
												</select>
											</div>
										</div>
									</div>
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Длина ячейки</div>
												<select name="rama_dlinaYach" size="1" class="form-control">
													<option value="0">3 м.</option>
													<option value="1">2 м.</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Стабилиз. опора</div>
												<select name="rama_opora" size="1" class="form-control" id="opora">
													<option value="0">Нет</option>
													<option value="1">2 м.</option>
													<option value="2">3 м.</option>
													<option value="3">4 м.</option>
													<option value="4">6 м.</option>
												</select>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-md-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Настил</div>
												<select name="rama_nastil" size="1" class="form-control" id="nastil">
													<option value="4" selected>Деревянный 0,75*0,95 (только для ЛР-10)</option>
													<option value="0" disabled>Деревянный 1,05*0,95</option>
													<option value="1" disabled>Деревянный 1,05*0,45</option>
													<option value="2">Металлический</option>
													<option value="3">Комбинированный</option>
												</select>
											</div>
										</div>
									</div>
									<div class="col-md-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Ограждения</div>
												<select name="rama_ograd" size="1" class="form-control" id="ograd">
													<option value="0">С ограждениями</option>
													<option value="1" selected="">Без ограждений</option>
													<option value="2">Диагонали в каждой ячейке</option>
												</select>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-md-10 col-sm-12">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Хомутовая стяжка</div>
												<select name="rama_styagka" size="1" class="form-control" id="styagka" style="width: 50%" disabled>
													<option value="0">Нет</option>
													<option value="1">1,5 м. (42)</option>
													<option value="2">2 м. (42)</option>
													<option value="3">3 м. (42)</option>
													<option value="4">1,5 м. (48)</option>
													<option value="5">2 м. (48)</option>
													<option value="6">3 м. (48)</option>
												</select>
												<input type="number" class="form-control" name="rama_kolstyagka" value="0" style="width: 50%" disabled="disabled">
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-md-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Подъемов</div>
												<input type="number" class="form-control" name="rama_podjomov" value="1">
											</div>
										</div>
									</div>
	
									<div class="col-md-6">
										<div class="checkbox">
											<label>
												<input type="checkbox" name="only_rigel" data-toggle="checkbox"> Только ригеля
											</label>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-md-6">
										<div class="checkbox">
											<label>
												<input type="checkbox" name="rama_torc" data-toggle="checkbox"> Торцевое ограждение
											</label>
										</div>
									</div>
									<div class="col-md-6">
										<div class="checkbox">
											<label>
												<input type="checkbox" name="rama_kirp" data-toggle="checkbox"> Для кирпичной кладки
											</label>
										</div>
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
					<ul class="nav nav-text nav-stacked" role="tablist">
						<li class="active">
							<a href="#rama-desc" class="desc" role="tab" data-toggle="tab">
								Описание
							</a>
						</li>
						<li>
							<a href="#rama-video" class="video" role="tab" data-toggle="tab">
								Видео
							</a>
						</li>
					</ul>
					<tabs class="nav nav-text nav-stacked">
    					<tab title="Описание">
							<p class="justifyfull">Рамные строительные леса отличаются высокой прочностью, простотой в эксплуатации, и, при этом, их стоимость намного ниже по сравнению с другими видами строительных лесов. Они предназначены для строительных и монтажных работ любой сложности; являются быстровозводимыми, с лежащими в основе пространственными каркасами из вертикальных рам, соединённых между собой горизонтальными и диагональными связями (которые в свою очередь соединяются между собой с помощью флажковых креплений). Высота установки данного вида лесов – до 100 м, количество ярусов настилов – не менее 3 штук, а нагрузка при фасадных работах – 200 кг/м&sup2; (при каменной кладке – 300 кг/м&sup2;). Диаметр трубы и толщина стенки зависит от вида рамных лесов.</p>
							<div class="row">
								<div class="col-sm-2 col-xs-4"><a data-lightbox="ramnyelesa" class="imagelink" href="/photo/ramnye-lesa/ramnye-lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/ramnye-lesa/ramnye-lesa_1_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="ramnyelesa" class="imagelink" href="/photo/ramnye-lesa/ramnye-lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/ramnye-lesa/ramnye-lesa_2_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="ramnyelesa" class="imagelink" href="/photo/ramnye-lesa/ramnye-lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/ramnye-lesa/ramnye-lesa_3_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="ramnyelesa" class="imagelink" href="/photo/ramnye-lesa/ramnye-lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/ramnye-lesa/ramnye-lesa_4_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="ramnyelesa" class="imagelink" href="/photo/ramnye-lesa/ramnye-lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/ramnye-lesa/ramnye-lesa_5_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="ramnyelesa" class="imagelink" href="/photo/ramnye-lesa/ramnye-lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/ramnye-lesa/ramnye-lesa_6_s.jpg" alt="..."><span></span></a></div>
							</div>
						</tab>
						<tab title="Видео">
							<div class="row">
								<div class="col-md-6">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/31Ue7G5Ffy4?rel=0" frameborder="0" allowfullscreen></iframe>
								</div>
								<div class="col-md-6">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/wOEi_EoE0gY?rel=0" frameborder="0" allowfullscreen></iframe>
								</div>
							</div>
						</tab>
					</tabs>	

					<div class = "pull-left" style = "margin-top:20px">
						<span>
							<p style = "color:black;font-weight:bold;">При</p>
							<p style = "color:black;font-weight:bold;">Покупке</p>
							<p style = "color:black;font-weight:bold;">На сумму</p>
							<p style = "color:black;font-weight:bold;">от 235 000 р.</p>
						</span>
						</div>
					<div class="pull-right dimmed" id = "salePic" style="margin-top: 20px;"><img class="b-lazy image" src="~/assets/img/sale.png" alt="Скидка"></div>
				</div>

			</div>
		</div>
	</div>
	<div class="container">
		<div class="row">
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="1">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Рамные леса серии ЛР-10</h3></div>
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/ramnye-lesa/lr-10.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>10 м.</span>
								</div>
								<div class="char">
									<strong>Кратность по длине:</strong><br>
									<span>2 / 3 м.</span>
								</div>
								<div class="char">
									<strong>Шаг яруса по высоте:</strong><br>
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Кол-во ярусов настилов:</strong><br>
									<span>не менее 3 шт.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>32x1.5 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong><br>
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
									<div class="value ramaValue" id = "checkValueRama"></div>
									<div class = "discount"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
	
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" data-nameprod='Рамные леса серии ЛР-10' class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'>Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
	
				</div>
			</div>
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="2">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Рамные леса серии ЛРП 2000-20</h3></div>
	
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/ramnye-lesa/lrp-2000-20.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>20 м.</span>
								</div>
								<div class="char">
									<strong>Кратность по длине:</strong><br>
									<span>2 / 3 м.</span>
								</div>
								<div class="char">
									<strong>Шаг яруса по высоте:</strong><br>
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Кол-во ярусов настилов:</strong><br>
									<span>не менее 3 шт.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>30x30x1.5 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong><br>
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
									<div class="value ramaValue"></div>
									<div class = "discount"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
	
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="3">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Рамные леса серии ЛРП 2000-40</h3></div>
	
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/ramnye-lesa/lrp-2000-40.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>40 м.</span>
								</div>
								<div class="char">
									<strong>Кратность по длине:</strong><br>
									<span>2 / 3 м.</span>
								</div>
								<div class="char">
									<strong>Шаг яруса по высоте:</strong><br>
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Кол-во ярусов настилов:</strong><br>
									<span>не менее 3 шт.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>42x1.5 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong><br>
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
									<div class="value ramaValue"></div>
									<div class = "discount"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
	
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
	
				</div>
			</div>
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="4">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Рамные леса серии ЛРП 2000-60</h3></div>
	
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/ramnye-lesa/lrp-2000-60.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>60 м.</span>
								</div>
								<div class="char">
									<strong>Кратность по длине:</strong><br>
									<span>2 / 3 м.</span>
								</div>
								<div class="char">
									<strong>Шаг яруса по высоте:</strong><br>
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Кол-во ярусов настилов:</strong><br>
									<span>не менее 3 шт.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>42x2 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong><br>
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
									<div class="value ramaValue"></div>
									<div class = "discount"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
	
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
	
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="6">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Рамные леса серии ЛРП 2000-80</h3></div>
	
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/ramnye-lesa/lrp-2000-20.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>80 м.</span>
								</div>
								<div class="char">
									<strong>Кратность по длине:</strong><br>
									<span>2 / 3 м.</span>
								</div>
								<div class="char">
									<strong>Шаг яруса по высоте:</strong><br>
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Кол-во ярусов настилов:</strong><br>
									<span>не менее 3 шт.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>48x2 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong><br>
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
									<div class="value ramaValue"></div>
									<div class = "discount"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
	
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
	
				</div>
			</div>
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="5">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Рамные леса серии ЛРП 2000-100</h3></div>
	
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/ramnye-lesa/lrp-2000-100.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>100 м.</span>
								</div>
								<div class="char">
									<strong>Кратность по длине:</strong><br>
									<span>2 / 3 м.</span>
								</div>
								<div class="char">
									<strong>Шаг яруса по высоте:</strong><br>
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Кол-во ярусов настилов:</strong><br>
									<span>не менее 3 шт.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>48x3 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong><br>
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
									<div class="value ramaValue"></div>
									<div class = "discount"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
	
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
	
				</div>
			</div>
		</div>
	</div>
	</section>
<section class="lesa-section klin-section" id="klin-section">
	<div class="topbar topbarklin">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<div class="namesection">
						<a href="/klinovye-lesa">Клиновые леса</a>
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
							<div class="fa-2x" style="float:left; margin: 0 10px 0 -40px;"><i class="fas fa-cog fa-spin"></i></div>Дополнительные<br>параметры
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
												<input class="form-control countItem countArenda" name="countArenda" value="30">
												<div class="plus recount active"></div>
											</div>
										</div>
									</div>
								</div>
							</div>
							<div class="pp-inner">
								<div class="row">
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Длина ячейки</div>
												<select name="klin_dlinayach" size="1" class="form-control">
													<option value="4">2 м.</option>
													<option value="5">2,5 м.</option>
													<option value="6" selected>3 м.</option>
												</select>
											</div>
										</div>
									</div>
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Глубина ячейки</div>
												<select name="klin_glyach" size="1" class="form-control">
													<option value="1">1 м.</option>
													<option value="2">1,2 м.</option>
													<option value="3">1,5 м.</option>
													<option value="4">2 м.</option>
													<option value="5">2,5 м.</option>
													<option value="6">3 м.</option>
												</select>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-sm-12">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Настил</div>
												<select name="klin_nastil" size="1" class="form-control">
													<option class="dl_1 gl_1" value="1_1_1">Настил деревянный 1,23*0,45 (25 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_1" value="1_1_2">Настил деревянный 1,23*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_1" value="1_1_3">Настил комбинированный 1*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_1" value="1_1_4">Настил металлический 1*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_1">Настил деревянный 1,43*0,45 (25 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_2">Настил деревянный 1,43*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_3">Настил комбинированный 1,2*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_4">Настил металлический 1,2*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_3" value="1_3_1">Настил деревянный 1,8*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_3" value="1_3_2">Настил комбинированный 1,5*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_3" value="1_3_3">Настил металлический 1,5*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_4" value="1_4_1">Настил деревянный 2,3*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_4" value="1_4_2">Настил комбинированный 2*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_4" value="1_4_3">Настил металлический 2*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_5" value="1_5_1">Настил деревянный 2,8*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_5" value="1_5_2">Настил комбинированный 2,5*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_5" value="1_5_3">Настил металлический 2,5*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_6" value="1_6_1">Настил комбинированный 3*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_6" value="1_6_2">Настил металлический 3*0,42 (2 настила на секцию)</option>
													<!-- Длина 1.2 -->
													<option class="dl_2 gl_1" value="2_1_1">Настил деревянный 1,23*0,45 (25 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_1" value="2_1_2">Настил деревянный 1,23*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_1" value="2_1_3">Настил комбинированный 1,2*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_1" value="2_1_4">Настил металлический 1,2*0,42 (2 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_1">Настил деревянный 1,43*0,45 (25 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_2">Настил деревянный 1,43*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_3">Настил комбинированный 1,2*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_4">Настил металлический 1,2*0,28/1,2*0,42 (2/1 настила на секцию)</option>
													<option class="dl_2 gl_3" value="2_3_1">Настил деревянный 1,8*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_3" value="2_3_2">Настил комбинированный 1,5*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_3" value="2_3_3">Настил металлический 1,5*0,28/1,5*0,42 (2/1 настила на секцию)</option>
													<option class="dl_2 gl_4" value="2_4_1">Настил деревянный 2,3*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_4" value="2_4_2">Настил комбинированный 2*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_4" value="2_4_3">Настил металлический 2*0,28/2*0,42 (2/1 настила на секцию)</option>
													<option class="dl_2 gl_5" value="2_5_1">Настил деревянный 2,8*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_2 gl_5" value="2_5_2">Настил комбинированный 2,5*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_5" value="2_5_3">Настил металлический 2,5*0,28/2,5*0,42 (2/1 настила на секцию)</option>
													<option class="dl_2 gl_6" value="2_6_1">Настил комбинированный 3*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_6" value="2_6_2">Настил металлический 3*0,28/3*0,42 (2/1 настила на секцию)</option>
													<!-- Длина 1.5 -->
													<option class="dl_3 gl_1" value="3_1_1">Настил деревянный 1,23*0,45 (25 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_1" value="3_1_2">Настил деревянный 1,23*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_1" value="3_1_3">Настил комбинированный 1,5*0,45 (2 настила на секцию)</option>
													<option class="dl_3 gl_1" value="3_1_4">Настил металлический 1,5*0,42 (2 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_1">Настил деревянный 1,43*0,45 (25 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_2">Настил деревянный 1,43*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_3">Настил комбинированный 1,5*0,45 (2 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_4">Настил металлический 1,5*0,28/1,5*0,42 (2/1 настила на секцию)</option>
													<option class="dl_3 gl_3" value="3_3_1">Настил деревянный 1,8*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_3" value="3_3_2">Настил комбинированный 1,5*0,45 (3 настила на секцию)</option>
													<option class="dl_3 gl_3" value="3_3_3">Настил металлический 1,5*0,28/1,5*0,42 (1/2 настила на секцию)</option>
													<option class="dl_3 gl_4" value="3_4_1">Настил деревянный 2,3*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_4" value="3_4_2">Настил комбинированный 2*0,45 (3 настила на секцию)</option>
													<option class="dl_3 gl_4" value="3_4_3">Настил металлический 2*0,28/2*0,42 (1/2 настила на секцию)</option>
													<option class="dl_3 gl_5" value="3_5_1">Настил деревянный 2,8*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_3 gl_5" value="3_5_2">Настил комбинированный 2,5*0,45 (3 настила на секцию)</option>
													<option class="dl_3 gl_5" value="3_5_3">Настил металлический 2,5*0,28/2,5*0,42 (1/2 настила на секцию)</option>
													<option class="dl_3 gl_6" value="3_6_1">Настил комбинированный 3*0,45 (3 настила на секцию)</option>
													<option class="dl_3 gl_6" value="3_6_2">Настил металлический 3*0,28/3*0,42 (1/2 настила на секцию)</option>
													<!-- Длина 2 -->
													<option class="dl_4 gl_1" value="4_1_1">Настил деревянный 1,23*0,45 (25 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_1" value="4_1_2">Настил деревянный 1,23*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_1" value="4_1_3">Настил комбинированный 2*0,45 (2 настила на секцию)</option>
													<option class="dl_4 gl_1" value="4_1_4">Настил металлический 2*0,42 (2 настила на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_1">Настил деревянный 1,43*0,45 (25 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_2">Настил деревянный 1,43*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_3">Настил комбинированный 2*0,45 (2 настила на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_4">Настил металлический 2*0,28/2*0,42 (2/1 настила на секцию)</option>
													<option class="dl_4 gl_3" value="4_3_1">Настил деревянный 1,8*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_3" value="4_3_2">Настил комбинированный 2*0,45 (3 настила на секцию)</option>
													<option class="dl_4 gl_3" value="4_3_3">Настил металлический 2*0,28/2*0,42 (1/2 настила на секцию)</option>
													<option class="dl_4 gl_4" value="4_4_1">Настил деревянный 2,3*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_4" value="4_4_2">Настил комбинированный 2*0,45 (4 настила на секцию)</option>
													<option class="dl_4 gl_4" value="4_4_3">Настил металлический 2*0,28/2*0,42 (2/3 настила на секцию)</option>
													<option class="dl_4 gl_5" value="4_5_1">Настил деревянный 2,8*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_4 gl_5" value="4_5_2">Настил комбинированный 2,5*0,45 (4 настила на секцию)</option>
													<option class="dl_4 gl_5" value="4_5_3">Настил металлический 2,5*0,28/2,5*0,42 (2/3 настила на секцию)</option>
													<option class="dl_4 gl_6" value="4_6_1">Настил комбинированный 3*0,45 (4 настила на секцию)</option>
													<option class="dl_4 gl_6" value="4_6_2">Настил металлический 3*0,28/3*0,42 (2/3 настила на секцию)</option>
													<!-- Длина 2.5 -->
													<option class="dl_5 gl_1" value="5_1_1">Настил деревянный 1,23*0,45 (25 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_1" value="5_1_2">Настил деревянный 1,23*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_1" value="5_1_3">Настил комбинированный 2,5*0,45 (2 настила на секцию)</option>
													<option class="dl_5 gl_1" value="5_1_4">Настил металлический 2,5*0,42 (2 настила на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_1">Настил деревянный 1,43*0,45 (25 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_2">Настил деревянный 1,43*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_3">Настил комбинированный 2,5*0,45 (2 настила на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_4">Настил металлический 2,5*0,28/2,5*0,42 (2/1 настила на секцию)</option>
													<option class="dl_5 gl_3" value="5_3_1">Настил деревянный 1,8*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_3" value="5_3_2">Настил комбинированный 2,5*0,45 (3 настила на секцию)</option>
													<option class="dl_5 gl_3" value="5_3_3">Настил металлический 2,5*0,28/2,5*0,42 (1/2 настила на секцию)</option>
													<option class="dl_5 gl_4" value="5_4_1">Настил деревянный 2,3*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_4" value="5_4_2">Настил комбинированный 2,5*0,45 (4 настила на секцию)</option>
													<option class="dl_5 gl_4" value="5_4_3">Настил металлический 2,5*0,28/2,5*0,42 (2/3 настила на секцию)</option>
													<option class="dl_5 gl_5" value="5_5_1">Настил деревянный 2,8*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_5 gl_5" value="5_5_2">Настил комбинированный 2,5*0,45 (5 настилов на секцию)</option>
													<option class="dl_5 gl_5" value="5_5_3">Настил металлический 2,5*0,28/2,5*0,42 (1/5 настилов на секцию)</option>
													<option class="dl_5 gl_6" value="5_6_1">Настил комбинированный 3*0,45 (5 настилов на секцию)</option>
													<option class="dl_5 gl_6" value="5_6_2">Настил металлический 3*0,28/3*0,42 (1/5 настилов на секцию)</option>
													<!-- Длина 3 -->
													<option class="dl_6 gl_1" value="6_1_1">Настил деревянный 1,23*0,45 (25 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_1" value="6_1_2">Настил деревянный 1,23*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_1" value="6_1_3">Настил комбинированный 3*0,45 (2 настила на секцию)</option>
													<option class="dl_6 gl_1" value="6_1_4">Настил металлический 3*0,42 (2 настила на секцию)</option>
													<option class="dl_6 gl_2" value="6_2_1">Настил деревянный 1,43*0,45 (25 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_2" value="6_2_2">Настил деревянный 1,43*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_2" value="6_2_3">Настил комбинированный 3*0,45 (2 настила на секцию)</option>
													<option class="dl_6 gl_2" value="6_2_4">Настил металлический 3*0,28/3*0,42 (2/1 настила на секцию)</option>
													<option class="dl_6 gl_3" value="6_3_1">Настил деревянный 1,8*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_3" value="6_3_2">Настил комбинированный 3*0,45 (3 настила на секцию)</option>
													<option class="dl_6 gl_3" value="6_3_3">Настил металлический 3*0,28/3*0,42 (1/2 настила на секцию)</option>
													<option class="dl_6 gl_4" value="6_4_1">Настил деревянный 2,3*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_4" value="6_4_2">Настил комбинированный 3*0,45 (4 настила на секцию)</option>
													<option class="dl_6 gl_4" value="6_4_3">Настил металлический 3*0,28/3*0,42 (2/3 настила на секцию)</option>
													<option class="dl_6 gl_5" value="6_5_1">Настил деревянный 2,8*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_6 gl_5" value="6_5_2">Настил комбинированный 3*0,45 (5 настилов на секцию)</option>
													<option class="dl_6 gl_5" value="6_5_3">Настил металлический 3*0,28/3*0,42 (1/5 настилов на секцию)</option>
													<option class="dl_6 gl_6" value="6_6_1">Настил комбинированный 3*0,45 (6 настилов на секцию)</option>
													<option class="dl_6 gl_6" value="6_6_2">Настил металлический 3*0,28/3*0,42 (1/6 настилов на секцию)</option>
	
												</select>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Подъемов</div>
												<input type="number" class="form-control" name="klin_podjomov" value="1">
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Длина стойки</div>
												<select name="klin_stoika" size="1" class="form-control">
													<option value="0">4 м.</option>
													<option value="1">3 м.</option>
													<option value="2">2 м.</option>
													<option value="3">1 м.</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Домкрат/подпятник</div>
												<select name="klin_podp" size="1" class="form-control novkt" id="podp" disabled>
													<option value="0">Подпятник</option>
													<option value="1">Домкрат</option>
												</select>
											</div>
										</div>
									</div>
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Ярус огражд.</div>
												<input type="number" class="form-control" name="klin_yarus" value="0">
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Шаг фланца</div>
												<select name="klin_flanec" class="form-control">
													<option value="0">1 м.</option>
													<option value="1">0,5 м.</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Отборт.элем (ярус)</div>
												<input type="number" class="form-control novkt" name="klin_otbelem" value="0" disabled>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Планка под кронштейн</div>
												<select name="klin_plankapk" size="1" class="form-control novkt" disabled>
													<option value="0">Нет</option>
													<option value="1">300 мм.</option>
													<option value="2">400 мм.</option>
													<option value="3">500 мм.</option>
												</select>
											</div>
										</div>
									</div>
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Кроншт./стен.опора</div>
												<select name="klin_stena" size="1" class="form-control novkt" disabled>
													<option value="0">Кронштейн</option>
													<option value="1">Стеновая опора 0,25 м.</option>
													<option value="2">Стеновая опора 0,5 м.</option>
												</select>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Консоль</div>
												<input type="number" class="form-control novkt" name="klin_konsol" value="0" disabled>
											</div>
										</div>
									</div>
									<div class="col-sm-6">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Стабил.опора</div>
												<select name="klin_opora" size="1" class="form-control novkt" disabled>
													<option value="0">Нет</option>
													<option value="1">2 м.</option>
													<option value="2">3 м.</option>
													<option value="3">4 м.</option>
													<option value="4">6 м.</option>
												</select>
											</div>
										</div>
									</div>
								</div>
								<div class="row">
									<div class="col-sm-6">
										<div class="checkbox">
											<label>
												<input type="checkbox" name="klin_stelem" data-toggle="checkbox"> Стартовый элемент
											</label>
										</div>
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
					<div class="col-md-3">
						<ul class="nav nav-text nav-stacked" role="tablist">
							<li class="active">
								<a href="#klin-desc" class="desc" role="tab" data-toggle="tab">
									Описание
								</a>
							</li>
							<li>
								<a href="#klin-video" class="video" role="tab" data-toggle="tab">
									Видео
								</a>
							</li>
						</ul>
						<div class = "pull-left" style = "margin-top:20px">
						<span>
							<p style = "color:black;font-weight:bold;">При</p>
							<p style = "color:black;font-weight:bold;">Покупке</p>
							<p style = "color:black;font-weight:bold;">На сумму</p>
							<p style = "color:black;font-weight:bold;">от 235 000 р.</p>
						</span>
						</div>
						<div class="pull-right dimmed" id = "salePicKlin" style="margin-top: 20px;"><img class="b-lazy" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="/img/sale.png" alt="Скидка" /></div>
					</div>
					<div class="col-md-9">
						<!-- Tab panes -->
						<div class="tab-content">
							<div class="tab-pane active" id="klin-desc">
								<p class="justifyfull">Строительные леса клинового типа являются надежными и универсальными, простыми в монтаже и демонтаже, что обеспечивает огромный спрос на них. Используются при ремонтно-строительных работах домов, в судостроении, при установке концертных площадок и сцен для шоу-программ. Что касается способа крепления, то клин забивают и расклинивают во фланцевый замок, который устроен таким образом, что самопроизвольное выпадение клина невозможно. Максимальная высота установки клиновых лесов варьируется от 60 до 100 м. Изготавливаются из труб диаметром 48 мм, при этом нагрузка при фасадных работах – 200 кг/м&sup2; (при каменной кладке – 500 кг/м&sup2;).</p>
								<div class="row">
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_1_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_2_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_3_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_4_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_5_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_6_s.jpg" alt="..."><span></span></a></div>
								</div>
							</div>
							<div class="tab-pane" id="klin-video">
								<div class="row">
									<div class="col-md-6">
										<iframe width="100%" height="315" src="https://www.youtube.com/embed/cuMiD0OeZcA?rel=0" frameborder="0" allowfullscreen></iframe>
									</div>
									<div class="col-md-6">
										<iframe width="100%" height="315" src="https://www.youtube.com/embed/zzLM14bbz2k?rel=0" frameborder="0" allowfullscreen></iframe>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
	</div>
	<div class="container">
	<div class="row">
		<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
			<div class="product" data-id="3">
			<div class="preload_product"><div class="preload_product__spin"></div></div>
				<div class="product-title"><h3>Клиновые леса серии ЛСК-30</h3></div>
	
				<div class="productblocks">
					<div class="col-sm-6 left">
						<img class="b-lazy image" src="~/assets/img/klinovye-lesa/lsk-100.jpg">
					</div>
					<div class="col-sm-6 right">
						<div class="desc">
							<div class="char">
								<strong>Макс. высота:</strong>
								<span>30 м.</span>
							</div>
							<div class="char">
								<strong>Высота яруса:</strong>
								<span>2 м.</span>
							</div>
							<div class="char">
								<strong>Шаг яруса вдоль стены:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Ширина яруса:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Несущая труба:</strong>
								<span>48*1.5 мм.</span>
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
								<div class="value klinValue" id = "checkValueKlin"></div>
								<div class = "discount"><b>-15%</b></div>
							</div>
							<div class="price arendaprice">
								<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
								<div class="value"></div>
							</div>
						</div>
					</div>
	
					<form method="POST" target="formwindow">
						<div class="col-sm-6 productbuttons">
							<div class="btn-group " role="group">
								<button type="button" class="btn btn-black-custom report">Комплектация</button>
								<button type="button" class="btn btn-black-custom save">Сохранить</button>
							</div>
							<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
						</div>
						<input type="hidden" name="datas">
						<input type="hidden" name="datajson">
					</form>
				</div>
	
			</div>
		</div>
	
		<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
			<div class="product" data-id="1">
			<div class="preload_product"><div class="preload_product__spin"></div></div>
				<div class="product-title"><h3>Клиновые леса серии ЛСК-60</h3></div>
	
				<div class="productblocks">
					<div class="col-sm-6 left">
						<img class="b-lazy image" src="~/assets/img/klinovye-lesa/lsk-60.jpg">
					</div>
					<div class="col-sm-6 right">
						<div class="desc">
							<div class="char">
								<strong>Макс. высота:</strong>
								<span>60 м.</span>
							</div>
							<div class="char">
								<strong>Высота яруса:</strong>
								<span>2 м.</span>
							</div>
							<div class="char">
								<strong>Шаг яруса вдоль стены:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Ширина яруса:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Несущая труба:</strong>
								<span>48*2 мм.</span>
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
								<div class="value klinValue" id = "checkValueKlin"></div>
								<div class = "discount"><b>-15%</b></div>
							</div>
							<div class="price arendaprice">
								<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
								<div class="value"></div>
							</div>
						</div>
					</div>
	
					<form method="POST" target="formwindow">
						<div class="col-sm-6 productbuttons">
							<div class="btn-group " role="group">
								<button type="button" class="btn btn-black-custom report">Комплектация</button>
								<button type="button" class="btn btn-black-custom save">Сохранить</button>
							</div>
							<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
						</div>
						<input type="hidden" name="datas">
						<input type="hidden" name="datajson">
					</form>
				</div>
	
			</div>
		</div>
		<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
			<div class="product" data-id="2">
			<div class="preload_product"><div class="preload_product__spin"></div></div>
				<div class="product-title"><h3>Клиновые леса серии ЛСК-100</h3></div>
	
				<div class="productblocks">
					<div class="col-sm-6 left">
						<img class="b-lazy image" src="~/assets/img/klinovye-lesa/lsk-100.jpg">
					</div>
					<div class="col-sm-6 right">
						<div class="desc">
							<div class="char">
								<strong>Макс. высота:</strong>
								<span>100 м.</span>
							</div>
							<div class="char">
								<strong>Высота яруса:</strong>
								<span>2 м.</span>
							</div>
							<div class="char">
								<strong>Шаг яруса вдоль стены:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Ширина яруса:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Несущая труба:</strong>
								<span>48*3 мм.</span>
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
								<div class="value klinValue"></div>
								<div class = "discount" style = "display:none;"><b>-15%</b></div>
							</div>
							<div class="price arendaprice">
								<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
								<div class="value"></div>
							</div>
						</div>
					</div>
					<form method="POST" target="formwindow">
						<div class="col-sm-6 productbuttons">
							<div class="btn-group " role="group">
								<button type="button" class="btn btn-black-custom report">Комплектация</button>
								<button type="button" class="btn btn-black-custom save">Сохранить</button>
							</div>
							<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
						</div>
						<input type="hidden" name="datas">
						<input type="hidden" name="datajson">
					</form>
				</div>
	
			</div>
		</div>
	
		<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
			<div class="product" data-id="4">
			<div class="preload_product"><div class="preload_product__spin"></div></div>
				<div class="product-title"><h3>Вышка ВКТ</h3></div>
	
				<div class="productblocks">
					<div class="col-sm-6 left">
						<img style="max-width: 66%;display: block;margin: 8% auto;" class="b-lazy image" src="~/assets/img/vkt-17.png">
					</div>
					<div class="col-sm-6 right">
						<div class="desc">
							<div class="char">
								<strong>Макс. высота:</strong>
								<span>15 м.</span>
							</div>
							<div class="char">
								<strong>Макс. высота рабочей площадки:</strong>
								<span>14 м.</span>
							</div>
							<div class="char">
								<strong>Шаг яруса вдоль стены:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Ширина яруса:</strong><br>
								<span>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</span>
							</div>
							<div class="char">
								<strong>Несущая труба:</strong>
								<span>48*1.5 мм.</span>
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
								<div class="value klinValue"></div>
								<div class = "discount" style = "display:none;"><b>-15%</b></div>
							</div>
							<div class="price arendaprice">
								<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
								<div class="value"></div>
							</div>
						</div>
					</div>
					<form method="POST" target="formwindow">
						<div class="col-sm-6 productbuttons">
							<div class="btn-group " role="group">
								<button type="button" class="btn btn-black-custom report">Комплектация</button>
								<button type="button" class="btn btn-black-custom save">Сохранить</button>
							</div>
							<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
						</div>
						<input type="hidden" name="datas">
						<input type="hidden" name="datajson">
					</form>
				</div>
	
			</div>
		</div>
	
	</div>
	</div>
	</section>

  <section class="lesa-section shtir-section" id="shtir-section">
<div class="topbar topbarshtir">
	<div class="container">
		<div class="row">
			<div class="col-md-3">
				<div class="namesection">
					<a href="https://xn----8sbemb9a1be.xn--p1ai/shtyrevye-lesa.php">Штыревые леса</a>
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
				<div class="col-md-3">
					<ul class="nav nav-text nav-stacked" role="tablist">
						<li class="active">
							<a href="#shtir-desc" class="desc" role="tab" data-toggle="tab">
								Описание
							</a>
						</li>
						<li>
							<a href="#shtir-video" class="video" role="tab" data-toggle="tab">
								Видео
							</a>
						</li>
					</ul>
					<div class = "pull-left" style = "margin-top:20px">
					<span>
						<p style = "color:black;font-weight:bold;">При</p>
    					<p style = "color:black;font-weight:bold;">Покупке</p>
    					<p style = "color:black;font-weight:bold;">На сумму</p>
    					<p style = "color:black;font-weight:bold;">от 235 000 р.</p>
					</span>
					</div>
					<div class="pull-right dimmed" id = "salePicShtir" style="margin-top: 20px;"><img class="b-lazy" src="~/assets/img/sale.png" alt="Скидка"></div>
				</div>
				<div class="col-md-9">
					

					<div class="tab-content">
						<div class="tab-pane active" id="shtir-desc">
							<p class="justifyfull">Штыревые строительные леса являются надежными, прочными, способны выдерживать огромные нагрузки. Приспосабливаются под формы стен и рельефов любой сложности. В собранном виде представляют собой конструкцию, состоящую из вертикальных стоек и горизонтальных связей, при этом элементы конструкции соединяются между собой с помощью штырей, приваренных к несущем опорам. Высота установки – от 50 до 100 м. Нагрузка при фасадных работах составляет 200 кг/м&sup2; (при каменной кладке – 500 кг/м&sup2; или 1000 кг/м&sup2; в зависимости от вида штыревых лесов).</p>
							<div class="row">
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_1_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_2_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_3_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_4_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_5_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink" href="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/shtyrevye-lesa/shtyrevye_lesa_6_s.jpg" alt="..."><span></span></a></div>
							</div>
						</div>
						<div class="tab-pane" id="shtir-video">
							<div class="row">
								<div class="col-md-12">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/2Op68fIEkS4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
								</div>
							</div>
						</div>
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

				<form method="POST" target="formwindow">
					<div class="col-sm-6 productbuttons">
						<div class="btn-group " role="group">
							<button type="button" class="btn btn-black-custom report">Комплектация</button>
							<button type="button" class="btn btn-black-custom save">Сохранить</button>
						</div>
						<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
					</div>
					<input type="hidden" name="datas">
					<input type="hidden" name="datajson">
				</form>
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
				<form method="POST" target="formwindow">
					<div class="col-sm-6 productbuttons">
						<div class="btn-group " role="group">
							<button type="button" class="btn btn-black-custom report">Комплектация</button>
							<button type="button" class="btn btn-black-custom save">Сохранить</button>
						</div>
						<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
					</div>
					<input type="hidden" name="datas">
					<input type="hidden" name="datajson">
				</form>
			</div>

		</div>
	</div>
</div>
</div>
</section>

<section class="lesa-section homut-section" id="homut-section">
	<div class="topbar topbarhomut">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<div class="namesection">
						<a href="https://xn----8sbemb9a1be.xn--p1ai/homutovye-lesa.php">Хомутовые леса</a>
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
												<input class="form-control countItem countArenda" name="countArenda" value="30">
												<div class="plus recount active"></div>
											</div>
										</div>
									</div>
								</div>
							</div>
							<div class="pp-inner">
								<div class="row">
									<div class="col-xs-7">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Длина ячейки</div>
												<select name="homut_dlinayach" size="1" class="form-control">
													<option value="1">1 м.</option>
													<option value="2">1,5 м.</option>
													<option value="3">2 м.</option>
													<option value="4">2,5 м.</option>
													<option value="5" selected>3 м.</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Настил</div>
												<select name="homut_nastil" size="1" id="homut_nastil" class="form-control">
													<option class="dl_1 gl_1" value="1_1_1">Настил деревянный 1,23*0,45 (25 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_1" value="1_1_2">Настил деревянный 1,23*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_1" value="1_1_3">Настил комбинированный 1*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_1" value="1_1_4">Настил металлический 1*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_1">Настил деревянный 1,8*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_2">Настил комбинированный 1,5*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_2" value="1_2_3">Настил металлический 1,5*0,42 (2 настила на секцию)</option>
													<option class="dl_1 gl_3" value="1_3_1">Настил деревянный 2,3*0,45 (40 мм.) (2 настила на секцию)</option>
													<option class="dl_1 gl_3" value="1_3_2">Настил комбинированный 2*0,45 (2 настила на секцию)</option>
													<option class="dl_1 gl_3" value="1_3_3">Настил металлический 2*0,42 (2 настила на секцию)</option>
													<!-- Длина 1.5 -->
													<option class="dl_2 gl_1" value="2_1_1">Настил деревянный 1,23*0,45 (25 мм.) (3 настила на секцию)</option>
													<option class="dl_2 gl_1" value="2_1_2">Настил деревянный 1,23*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_2 gl_1" value="2_1_3">Настил комбинированный 1,5*0,45 (2 настила на секцию)</option>
													<option class="dl_2 gl_1" value="2_1_4">Настил металлический 1,5*0,42 (2 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_1">Настил деревянный 1,8*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_2">Настил комбинированный 1,5*0,45 (3 настила на секцию)</option>
													<option class="dl_2 gl_2" value="2_2_3">Настил металлический 1,5*0,28/1,5*0,42 (1/2 настила на секцию)</option>
													<option class="dl_2 gl_3" value="2_3_1">Настил деревянный 2,3*0,45 (40 мм.) (3 настила на секцию)</option>
													<option class="dl_2 gl_3" value="2_3_2">Настил комбинированный 2*0,45 (3 настила на секцию)</option>
													<option class="dl_2 gl_3" value="2_3_3">Настил металлический 2*0,28/2*0,42 (1/2 настила на секцию)</option>
													<!-- Длина 2 -->
													<option class="dl_3 gl_1" value="3_1_1">Настил деревянный 1,23*0,45 (25 мм.) (4 настила на секцию)</option>
													<option class="dl_3 gl_1" value="3_1_2">Настил деревянный 1,23*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_3 gl_1" value="3_1_3">Настил комбинированный 2*0,45 (2 настила на секцию)</option>
													<option class="dl_3 gl_1" value="3_1_4">Настил металлический 2*0,42 (2 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_1">Настил деревянный 1,8*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_2">Настил комбинированный 2*0,45 (3 настила на секцию)</option>
													<option class="dl_3 gl_2" value="3_2_3">Настил металлический 2*0,28/2*0,42 (1/2 настила на секцию)</option>
													<option class="dl_3 gl_3" value="3_3_1">Настил деревянный 2,3*0,45 (40 мм.) (4 настила на секцию)</option>
													<option class="dl_3 gl_3" value="3_3_2">Настил комбинированный 2*0,45 (4 настила на секцию)</option>
													<option class="dl_3 gl_3" value="3_3_3">Настил металлический 2*0,28/2*0,42 (2/3 настила на секцию)</option>
													<!-- Длина 2.5 -->
													<option class="dl_4 gl_1" value="4_1_1">Настил деревянный 1,23*0,45 (25 мм.) (5 настилов на секцию)</option>
													<option class="dl_4 gl_1" value="4_1_2">Настил деревянный 1,23*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_4 gl_1" value="4_1_3">Настил комбинированный 2,5*0,45 (2 настила на секцию)</option>
													<option class="dl_4 gl_1" value="4_1_4">Настил металлический 2,5*0,42 (2 настила на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_1">Настил деревянный 1,8*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_2">Настил комбинированный 2,5*0,45 (3 настила на секцию)</option>
													<option class="dl_4 gl_2" value="4_2_3">Настил металлический 2,5*0,28/2,5*0,42 (1/2 настила на секцию)</option>
													<option class="dl_4 gl_3" value="4_3_1">Настил деревянный 2,3*0,45 (40 мм.) (5 настилов на секцию)</option>
													<option class="dl_4 gl_3" value="4_3_2">Настил комбинированный 2,5*0,45 (4 настила на секцию)</option>
													<option class="dl_4 gl_3" value="4_3_3">Настил металлический 2,5*0,28/2,5*0,42 (2/3 настила на секцию)</option>
													<!-- Длина 3 -->
													<option class="dl_5 gl_1" value="5_1_1">Настил деревянный 1,23*0,45 (25 мм.) (6 настилов на секцию)</option>
													<option class="dl_5 gl_1" value="5_1_2">Настил деревянный 1,23*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_5 gl_1" value="5_1_3">Настил комбинированный 3*0,45 (2 настила на секцию)</option>
													<option class="dl_5 gl_1" value="5_1_4">Настил металлический 3*0,42 (2 настила на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_1">Настил деревянный 1,8*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_2">Настил комбинированный 3*0,45 (3 настила на секцию)</option>
													<option class="dl_5 gl_2" value="5_2_3">Настил металлический 3*0,28/3*0,42 (1/2 настила на секцию)</option>
													<option class="dl_5 gl_3" value="5_3_1">Настил деревянный 2,3*0,45 (40 мм.) (6 настилов на секцию)</option>
													<option class="dl_5 gl_3" value="5_3_2">Настил комбинированный 3*0,45 (4 настила на секцию)</option>
													<option class="dl_5 gl_3" value="5_3_3">Настил металлический 3*0,28/3*0,42 (2/3 настила на секцию)</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Стабилизирующая опора</div>
												<select name="homut_opora" size="1" class="form-control">
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
												<select name="homut_plankapk" size="1" class="form-control">
													<option value="0">Нет</option>
													<option value="1">300 мм.</option>
													<option value="2">400 мм.</option>
													<option value="3">500 мм.</option>
												</select>
											</div>
										</div>
									</div>
									<div class="col-xs-5">
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Глубина</div>
												<select name="homut_glubina" size="1" class="form-control">
													<option value="1">1 м.</option>
													<option value="2">1.5 м.</option>
												</select>
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Подъемов</div>
												<input type="number" class="form-control" name="homut_podjomov" value="1">
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Ярус огражд.</div>
												<input type="number" class="form-control" name="homut_yarus" value="0">
											</div>
										</div>
										<div class="form-group">
											<div class="input-group">
												<div class="input-group-addon">Для ЛХ-80-УС</div>
												<select name="homut_svyaz" size="1" class="form-control">
													<option value="0" selected>Связи 48*3</option>
													<option value="1">Связи 57*3</option>
												</select>
											</div>
										</div>
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
				<div class="col-md-3">
					<ul class="nav nav-text nav-stacked" role="tablist">
						<li class="active">
							<a href="#homut-desc" class="desc" role="tab" data-toggle="tab">
								Описание
							</a>
						</li>
						<li>
							<a href="#homut-video" class="video" role="tab" data-toggle="tab">
								Видео
							</a>
						</li>
					</ul>
					<div class = "pull-left" style = "margin-top:20px">
					<span>
						<p style = "color:black;font-weight:bold;">При</p>
    					<p style = "color:black;font-weight:bold;">Покупке</p>
    					<p style = "color:black;font-weight:bold;">На сумму</p>
    					<p style = "color:black;font-weight:bold;">от 235 000 р.</p>
					</span>
					</div>
					<div class="pull-right dimmed" id = "salePicKhomut" style="margin-top: 20px;"><img class="b-lazy" src="~/assets/img/sale.png" alt="Скидка"></div>
				</div>
				<div class="col-md-9">
					<div class="tab-content">
						<div class="tab-pane active" id="homut-desc">
							<p class="justifyfull">Строительные леса хомутового типа используются при работах со сложными объектами, устанавливаются даже в самых труднодоступных местах. Например, используются для фасадных или высотных работ, реставрации памятников, храмов и т.д. Представляют собой трубчатые многоярусные и многосекционные металлоконструкции, все элементы которых соединяются поворотными и глухими хомутами. Высота данного вида лесов варьируется от 30 до 80 м, а нагрузка при фасадных работах – 200 кг/м&sup2; (при каменной кладке – от 300 до 500 кг/м&sup2; в зависимости от вида хомутовых лесов).</p>
							<div class="row">
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_1_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_2_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_3_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_4_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_5_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_6_s.jpg" alt="..."><span></span></a></div>
							</div>
						</div>
						<div class="tab-pane" id="homut-video">
							<div class="row">
								<div class="col-md-12">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/M9lDVHyc8tU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
								</div>
							</div>
						</div>
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
					<div class="product-title"><h3>Хомутовые леса серии ЛХ-30-Л</h3></div>
					
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/homutovye-lesa/lh-30-l.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>30 м.</span>
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
									<span>3 м.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>42 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong>
									<span>150 кг/м&sup2;</span>
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
									<div class="value khomutValue" id = "checkValueKhomut"></div>
									<div class = "discount" style = "display:none;"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
					
				</div>
			</div>
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="2">
				<div class="preload_product"><div class="preload_product__spin"></div></div>	
					<div class="product-title"><h3>Хомутовые леса серии ЛХ-40</h3></div>
					
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/homutovye-lesa/lh-80-us.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>40 м.</span>
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
									<span>3 м.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>48*1,5 мм.</span>
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
									<div class="value khomutValue"></div>
									<div class = "discount" style = "display:none;"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
					
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="3">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Хомутовые леса серии ЛХ-40-УС</h3></div>
					
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/homutovye-lesa/lh-40-us.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>40 м.</span>
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
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>48*3 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong>
									<span>250 кг/м&sup2;</span>
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
									<div class="value khomutValue"></div>
									<div class = "discount" style = "display:none;"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
					
				</div>
			</div>
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="4">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Хомутовые леса серии ЛХ-60</h3></div>
					
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/homutovye-lesa/lh-80-v.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>60 м.</span>
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
									<span>2,5 м.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>48*2 мм.</span>
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
									<div class="value khomutValue"></div>
									<div class = "discount" style = "display:none;"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
					
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="5">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Хомутовые леса серии ЛХ-80-В</h3></div>
					
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/homutovye-lesa/lh-80-v.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>80 м.</span>
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
									<span>2,5 м.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>48*3 мм.</span>
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
									<div class="value khomutValue"></div>
									<div class = "discount" style = "display:none;"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
					
				</div>
			</div>
			<div class="col-md-6 col-sm-8 col-sm-offset-2 col-md-offset-0 col-xs-12">
				<div class="product" data-id="6">
				<div class="preload_product"><div class="preload_product__spin"></div></div>
					<div class="product-title"><h3>Хомутовые леса серии ЛХ-80-УС</h3></div>
					
					<div class="productblocks">
						<div class="col-sm-6 left">
							<img class="b-lazy image" src="~/assets/img/homutovye-lesa/lh-80-us.jpg">
						</div>
						<div class="col-sm-6 right">
							<div class="desc">
								<div class="char">
									<strong>Макс. высота:</strong>
									<span>80 м.</span>
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
									<span>2 м.</span>
								</div>
								<div class="char">
									<strong>Несущая труба:</strong>
									<span>57*3 мм.</span>
								</div>
								<div class="char">
									<strong>Макс. нагрузка:</strong>
									<span>250 кг/м&sup2;</span>
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
									<div class="value khomutValue"></div>
									<div class = "discount" style = "display:none;"><b>-15%</b></div>
								</div>
								<div class="price arendaprice">
									<div class="title-price">Стоимость аренды <span class="value1"></span> дней</div>
									<div class="value"></div>
								</div>
							</div>
						</div>
						
						<form method="POST" target="formwindow">
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa'> Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						</form>
					</div>
					
				</div>
			</div>
		</div>
	</div>
</section>


<section class="lesa-section tura-section" id="tura-section">
	
	<section>
	<div class="topbar topbartur">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<div class="namesection" data-id="1">
						<a href="https://xn----8sbemb9a1be.xn--p1ai/vyshki-tura.php">Вышки-тура</a>
						<div class="snoski hidden-xs">
							<div class="snoska">продажа</div>
							<div class="snoska">аренда</div>
						</div>
					</div>
				</div>
				<div class="col-md-9">
					<div class="input-sources">
						<div class="namesection2">
							<p>Выберите высоту вышки</p>
						</div>
						<div class="is-group">
							<label for="countHeight" class="countTitle">Высота</label>
							<div class="countGroup">
								<div class="minus recount active"></div>
								<input class="form-control countItem" name="countHeight" id="countHeight" value="2">
								<div class="plus recount active"></div>
							</div>
						</div>
						<div class="btn-showset">
							<span style="line-height: 2.7;">Выберите площадку</span>
						</div>
						<div class="params-panel">
							<div class="area-size pp-inner">
								<div class="row">
									<div class="col-lg-12">
										<h2>Выберите размер площадки</h2>
										<div class="choice">
											<p><input type="checkbox" value="0.5*1.5">0,5*1,5</p>
											<p><input type="checkbox" value="0.75*2">0,75*2</p>
											<p><input type="checkbox" value="1.2*2">1,2*2</p>
											<p><input type="checkbox" value="1.5*2">1,5*1</p>
											<p><input type="checkbox" value="1.5*1.5">1,5*1,5</p>
											<p><input type="checkbox" value="2.0*1.0">2,0*1,0</p>
											<p><input type="checkbox" value="2.0*1.5">2,0*1,5</p>
											<p><input type="checkbox" value="2*2">2*2</p>
										</div>
									</div>
								</div>
							</div>
							<div class="pp-inner arenda">
								<div class="row">
									<div class="col-md-6">
										<div class="productbuttons">
											<button class="btn btn-danger-fill-custom cart getorderformtur"> Оформить
												заказ</button>
										</div>
									</div>
									<div class="col-md-6">
										<label for="countArenda">КОЛИЧЕСТВО ДНЕЙ АРЕНДЫ</label>
										<span>Минимальный срок аренды - 5 дней</span>
										<div class="is-group">
											<div class="countGroup">
												<div class="minus recount active"></div>
												<input class="form-control countItem countArenda" name="countArenda"
													value="5" min="5">
												<div class="plus recount active"></div>
											</div>
										</div>
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
				<!-- <div class="col-md-3">
					<div class="pull-right" style="margin-top: 20px;" style="margin-top: 20px;"><img src="img/sale.png" alt="Скидка"></div>
				</div> -->
				<div class="col-md-12">
					<p class="justifyfull">Строительные вышки туры - вспомогательное сооружение башенного типа на
						поворотных колесах изготавливается из стальных конструкций и устанавливается на высоту до 21
						метра. Основное различие сборно-разборных тур это габаритные размеры рабочих площадок. В
						зависимости от того, какие виды монтажных или отделочных работ производится на строительных
						подмостях, будет зависеть, какая серия ТУРЫ оптимально подходит для этих целей.

						На нашем заводе производятся различные вышки туры. Вы можете изучить более подробно все
						преимущества и недостатки той или иной конструкции. И выбрать для себя именно ту вышку, которая
						будет наиболее эффективна. А наша задача заключается в том, чтобы сделать ваш заказ качественно,
						быстро и не дорого.</p>
					<div class="row">
						<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink"
								href="~/assets/photo/vyshky-tura/gigant.jpg"><img class="b-lazy img-thumbnail"
									src="~/assets/photo/vyshky-tura/gigant_s.jpg" alt="..."><span></span></a></div>
						<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink"
								href="~/assets/photo/vyshky-tura/tur7.jpg"><img class="b-lazy img-thumbnail"
									src="~/assets/photo/vyshky-tura/tur7_s.jpg" alt="..."><span></span></a></div>
						<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink"
								href="~/assets/photo/vyshky-tura/uvt10.jpg"><img class="b-lazy img-thumbnail"
									src="~/assets/photo/vyshky-tura/uvt10_s.jpg" alt="..."><span></span></a></div>
						<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink"
								href="~/assets/photo/vyshky-tura/uvt15.jpg"><img class="b-lazy img-thumbnail"
									src="~/assets/photo/vyshky-tura/uvt15_s.jpg" alt="..."><span></span></a></div>
						<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink"
								href="~/assets/photo/vyshky-tura/vsrp19900.jpg"><img class="b-lazy img-thumbnail"
									src="~/assets/photo/vyshky-tura/vsrp19900_s.jpg" alt="..."><span></span></a></div>
						<div class="col-sm-2 col-xs-4"><a data-lightbox="shtyrevyelesa" class="imagelink"
								href="~/assets/photo/vyshky-tura/uvt102.jpg"><img class="b-lazy img-thumbnail"
									src="~/assets/photo/vyshky-tura/uvt102_s.jpg" alt="..."><span></span></a></div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<div class="prices-block prices-block-Desc">
		<div class="container">
			<div class="title">Цены и размеры - выберите модель вышки</div>

			<tabs class="prices-tabs">
    			<tab title="ВСРП 1,2">
					<vsrp1-2 />
    			</tab>
    			<tab title="ВСРП 0,75">
					<vsrp075 />
    			</tab>
    			<tab title="ГИГАНТ">
					<gigant />
    			</tab>
				<tab title="МЕРДИ-10">
					<merdi />
    			</tab>
				<tab title="ТУР-7">
      			  	<tur7 />
    			</tab>
				<tab title="УВТ-7.5 1,5">
      				<uvt-75-15 />		
    			</tab>
				<tab title="УВТ-7.5 2">
					<uvt-75-2 />	
    			</tab>
				<tab title="УВТ-10 1,5">
					<uvt-10-15 />
    			</tab>
				<tab title="УВТ-10 2">
					<uvt-10-2 />
    			</tab>
				<tab title="УВТ-15 1,5">
					<uvt-15-15 />
    			</tab>
				<tab title="УВТ-15 2">
					<uvt-15-2 />
    			</tab>
				<tab title="СМП-4">
					<smp4 />
    			</tab>
				<tab title="ПС-1,5">
					<pc1-5 />
    			</tab>
  			</tabs>
			
		</div>
	</div>
	</section>

	<div class="prices-block prices-block-Mob">
		<div class="title">Цены и размеры - выберите модель вышки</div>
		<ul class="prices-tabs">
			<li class="active" data-price="prices-vsrp_2" style="width: 33%;">ВСРП 1,2</li>
			<li data-price="prices-vsrp_1" style="width: 33%">ВСРП 0,75</li>
			<li data-price="prices-gigant" style="width: 33%">ГИГАНТ</li>
			<li data-price="prices-merdi" style="width: 33%">МЕРДИ-10</li>
			<li data-price="prices-tur" style="width: 33%">ТУР-7</li>
			<li data-price="prices-uvt10_1" style="width: 33%">УВТ-10 1,5</li>
			<li data-price="prices-uvt10_2" style="width: 33%">УВТ-10 2</li>
			<li data-price="prices-uvt15_1" style="width: 33%">УВТ-15 1,5</li>
			<li data-price="prices-uvt15_2" style="width: 33%">УВТ-15 2</li>
			<li data-price="prices-smp4" style="width: 49.5%">СМП-4</li>
			<li data-price="prices-ps15" style="width: 49.5%">ПС-1,5</li>
		</ul>
		<div class="tableInner">
			<div class="tab-block active" id="prices-vsrp_2" data-vkt="vsrp2_0_1_2" style="display: block">
				<div class='h6 text-center'>Вышка-тура ВСРП-19900 (площадка 2,0*1,2 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2960<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>13 664.00</td></tr>
        <tr><td>Оптовая цена: </td><td>11 614.40</td></tr>
        <tr><td>Цена аренды: </td><td>1 639.68</td></tr>
        <tr><td>Каждый последующий день: </td><td>204.96</td></tr>
        <tr><td>Вес, кг : </td><td>105.84</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.55</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4485<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>17 416.00</td></tr>
        <tr><td>Оптовая цена: </td><td>14 803.60</td></tr>
        <tr><td>Цена аренды: </td><td>2 089.92</td></tr>
        <tr><td>Каждый последующий день: </td><td>261.24</td></tr>
        <tr><td>Вес, кг : </td><td>137.84</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>6010</td></tr>
        <tr><td>Розничная цена: </td><td>22 888.00</td></tr>
        <tr><td>Оптовая цена: </td><td>19 454.80</td></tr>
        <tr><td>Цена аренды: </td><td>2 746.56</td></tr>
        <tr><td>Каждый последующий день: </td><td>343.32</td></tr>
        <tr><td>Вес, кг : </td><td>178.60</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.10</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7535</td></tr>
        <tr><td>Розничная цена: </td><td>26 168.00</td></tr>
        <tr><td>Оптовая цена: </td><td>22 242.80</td></tr>
        <tr><td>Цена аренды: </td><td>3 140.16</td></tr>
        <tr><td>Каждый последующий день: </td><td>392.52</td></tr>
        <tr><td>Вес, кг : </td><td>206.40</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.30</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>9060</td></tr>
        <tr><td>Розничная цена: </td><td>29 448.00</td></tr>
        <tr><td>Оптовая цена: </td><td>25 030.80</td></tr>
        <tr><td>Цена аренды: </td><td>3 533.76</td></tr>
        <tr><td>Каждый последующий день: </td><td>441.72</td></tr>
        <tr><td>Вес, кг : </td><td>234.20</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.60</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10620</td></tr>
        <tr><td>Розничная цена: </td><td>33 840.00</td></tr>
        <tr><td>Оптовая цена: </td><td>28 764.00</td></tr>
        <tr><td>Цена аренды: </td><td>4 060.80</td></tr>
        <tr><td>Каждый последующий день: </td><td>507.60</td></tr>
        <tr><td>Вес, кг : </td><td>266.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>12145</td></tr>
        <tr><td>Розничная цена: </td><td>37 356.00</td></tr>
        <tr><td>Оптовая цена: </td><td>31 752.60</td></tr>
        <tr><td>Цена аренды: </td><td>4 482.72</td></tr>
        <tr><td>Каждый последующий день: </td><td>560.34</td></tr>
        <tr><td>Вес, кг : </td><td>295.90</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.10</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>13670</td></tr>
        <tr><td>Розничная цена: </td><td>40 636.00</td></tr>
        <tr><td>Оптовая цена: </td><td>34 540.60</td></tr>
        <tr><td>Цена аренды: </td><td>4 876.32</td></tr>
        <tr><td>Каждый последующий день: </td><td>609.54</td></tr>
        <tr><td>Вес, кг : </td><td>323.70</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.40</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>15195</td></tr>
        <tr><td>Розничная цена: </td><td>43 916.00</td></tr>
        <tr><td>Оптовая цена: </td><td>37 328.60</td></tr>
        <tr><td>Цена аренды: </td><td>5 269.92</td></tr>
        <tr><td>Каждый последующий день: </td><td>658.74</td></tr>
        <tr><td>Вес, кг : </td><td>351.50</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>16720</td></tr>
        <tr><td>Розничная цена: </td><td>47 196.00</td></tr>
        <tr><td>Оптовая цена: </td><td>40 116.60</td></tr>
        <tr><td>Цена аренды: </td><td>5 663.52</td></tr>
        <tr><td>Каждый последующий день: </td><td>707.94</td></tr>
        <tr><td>Вес, кг : </td><td>379.30</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>18245</td></tr>
        <tr><td>Розничная цена: </td><td>50 712.00</td></tr>
        <tr><td>Оптовая цена: </td><td>43 105.20</td></tr>
        <tr><td>Цена аренды: </td><td>6 085.44</td></tr>
        <tr><td>Каждый последующий день: </td><td>760.68</td></tr>
        <tr><td>Вес, кг : </td><td>409.20</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>3.20</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>19770</td></tr>
        <tr><td>Розничная цена: </td><td>53 992.00</td></tr>
        <tr><td>Оптовая цена: </td><td>45 893.20</td></tr>
        <tr><td>Цена аренды: </td><td>6 479.04</td></tr>
        <tr><td>Каждый последующий день: </td><td>809.88</td></tr>
        <tr><td>Вес, кг : </td><td>437.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>3.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-vsrp_1">
				<div class='h6 text-center'>Вышка-тура ВСРП-19900 (площадка 2,0*0,75 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2960<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>11 515.00</td></tr>
        <tr><td>Оптовая цена: </td><td>9 787.75</td></tr>
        <tr><td>Цена аренды: </td><td>1 381.80</td></tr>
        <tr><td>Каждый последующий день: </td><td>172.73</td></tr>
        <tr><td>Вес, кг : </td><td>79.34</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.45</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4485<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>14 971.00</td></tr>
        <tr><td>Оптовая цена: </td><td>12 725.35</td></tr>
        <tr><td>Цена аренды: </td><td>1 796.52</td></tr>
        <tr><td>Каждый последующий день: </td><td>224.57</td></tr>
        <tr><td>Вес, кг : </td><td>106.28</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>6010</td></tr>
        <tr><td>Розничная цена: </td><td>20 169.00</td></tr>
        <tr><td>Оптовая цена: </td><td>17 143.65</td></tr>
        <tr><td>Цена аренды: </td><td>2 420.28</td></tr>
        <tr><td>Каждый последующий день: </td><td>302.54</td></tr>
        <tr><td>Вес, кг : </td><td>142.84</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7535</td></tr>
        <tr><td>Розничная цена: </td><td>23 175.00</td></tr>
        <tr><td>Оптовая цена: </td><td>19 698.75</td></tr>
        <tr><td>Цена аренды: </td><td>2 781.00</td></tr>
        <tr><td>Каждый последующий день: </td><td>347.63</td></tr>
        <tr><td>Вес, кг : </td><td>166.44</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.10</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>9060</td></tr>
        <tr><td>Розничная цена: </td><td>26 181.00</td></tr>
        <tr><td>Оптовая цена: </td><td>22 253.85</td></tr>
        <tr><td>Цена аренды: </td><td>3 141.72</td></tr>
        <tr><td>Каждый последующий день: </td><td>392.72</td></tr>
        <tr><td>Вес, кг : </td><td>190.04</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.40</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10620</td></tr>
        <tr><td>Розничная цена: </td><td>30 299.00</td></tr>
        <tr><td>Оптовая цена: </td><td>25 754.15</td></tr>
        <tr><td>Цена аренды: </td><td>3 635.88</td></tr>
        <tr><td>Каждый последующий день: </td><td>454.49</td></tr>
        <tr><td>Вес, кг : </td><td>217.64</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.60</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>12145</td></tr>
        <tr><td>Розничная цена: </td><td>33 530.00</td></tr>
        <tr><td>Оптовая цена: </td><td>28 500.50</td></tr>
        <tr><td>Цена аренды: </td><td>4 023.60</td></tr>
        <tr><td>Каждый последующий день: </td><td>502.95</td></tr>
        <tr><td>Вес, кг : </td><td>242.91</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>13670</td></tr>
        <tr><td>Розничная цена: </td><td>36 536.00</td></tr>
        <tr><td>Оптовая цена: </td><td>31 055.60</td></tr>
        <tr><td>Цена аренды: </td><td>4 384.32</td></tr>
        <tr><td>Каждый последующий день: </td><td>548.04</td></tr>
        <tr><td>Вес, кг : </td><td>266.51</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>15195</td></tr>
        <tr><td>Розничная цена: </td><td>39 542.00</td></tr>
        <tr><td>Оптовая цена: </td><td>33 610.70</td></tr>
        <tr><td>Цена аренды: </td><td>4 745.04</td></tr>
        <tr><td>Каждый последующий день: </td><td>593.13</td></tr>
        <tr><td>Вес, кг : </td><td>290.11</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.30</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>16720</td></tr>
        <tr><td>Розничная цена: </td><td>42 548.00</td></tr>
        <tr><td>Оптовая цена: </td><td>36 165.80</td></tr>
        <tr><td>Цена аренды: </td><td>5 105.76</td></tr>
        <tr><td>Каждый последующий день: </td><td>638.22</td></tr>
        <tr><td>Вес, кг : </td><td>313.71</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>18245</td></tr>
        <tr><td>Розничная цена: </td><td>45 779.00</td></tr>
        <tr><td>Оптовая цена: </td><td>38 912.15</td></tr>
        <tr><td>Цена аренды: </td><td>5 493.48</td></tr>
        <tr><td>Каждый последующий день: </td><td>686.69</td></tr>
        <tr><td>Вес, кг : </td><td>338.98</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>19770</td></tr>
        <tr><td>Розничная цена: </td><td>48 785.00</td></tr>
        <tr><td>Оптовая цена: </td><td>41 467.25</td></tr>
        <tr><td>Цена аренды: </td><td>5 854.20</td></tr>
        <tr><td>Каждый последующий день: </td><td>731.78</td></tr>
        <tr><td>Вес, кг : </td><td>362.58</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>3.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-gigant">
				<div class='h6 text-center'>Вышка-тура ГИГАН (площадка 2,0*2,0 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2960<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>17 568.00</td></tr>
        <tr><td>Оптовая цена: </td><td>14 932.80</td></tr>
        <tr><td>Цена аренды: </td><td>2 108.16</td></tr>
        <tr><td>Каждый последующий день: </td><td>263.52</td></tr>
        <tr><td>Вес, кг : </td><td>134.54</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4485<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>21 927.00</td></tr>
        <tr><td>Оптовая цена: </td><td>18 637.95</td></tr>
        <tr><td>Цена аренды: </td><td>2 631.24</td></tr>
        <tr><td>Каждый последующий день: </td><td>328.91</td></tr>
        <tr><td>Вес, кг : </td><td>172.44</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.10</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>6010</td></tr>
        <tr><td>Розничная цена: </td><td>28 205.00</td></tr>
        <tr><td>Оптовая цена: </td><td>23 974.25</td></tr>
        <tr><td>Цена аренды: </td><td>3 384.60</td></tr>
        <tr><td>Каждый последующий день: </td><td>423.08</td></tr>
        <tr><td>Вес, кг : </td><td>221.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7535</td></tr>
        <tr><td>Розничная цена: </td><td>32 291.00</td></tr>
        <tr><td>Оптовая цена: </td><td>27 447.35</td></tr>
        <tr><td>Цена аренды: </td><td>3 874.92</td></tr>
        <tr><td>Каждый последующий день: </td><td>484.37</td></tr>
        <tr><td>Вес, кг : </td><td>256.60</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>9060</td></tr>
        <tr><td>Розничная цена: </td><td>36 377.00</td></tr>
        <tr><td>Оптовая цена: </td><td>30 920.45</td></tr>
        <tr><td>Цена аренды: </td><td>4 365.24</td></tr>
        <tr><td>Каждый последующий день: </td><td>545.66</td></tr>
        <tr><td>Вес, кг : </td><td>292.20</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.20</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10620</td></tr>
        <tr><td>Розничная цена: </td><td>41 575.00</td></tr>
        <tr><td>Оптовая цена: </td><td>35 338.75</td></tr>
        <tr><td>Цена аренды: </td><td>4 989.00</td></tr>
        <tr><td>Каждый последующий день: </td><td>623.63</td></tr>
        <tr><td>Вес, кг : </td><td>331.80</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>12145</td></tr>
        <tr><td>Розничная цена: </td><td>45 934.00</td></tr>
        <tr><td>Оптовая цена: </td><td>39 043.90</td></tr>
        <tr><td>Цена аренды: </td><td>5 512.08</td></tr>
        <tr><td>Каждый последующий день: </td><td>689.01</td></tr>
        <tr><td>Вес, кг : </td><td>369.70</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>13670</td></tr>
        <tr><td>Розничная цена: </td><td>50 020.00</td></tr>
        <tr><td>Оптовая цена: </td><td>42 517.00</td></tr>
        <tr><td>Цена аренды: </td><td>6 002.40</td></tr>
        <tr><td>Каждый последующий день: </td><td>750.30</td></tr>
        <tr><td>Вес, кг : </td><td>405.30</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>3.20</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>15195</td></tr>
        <tr><td>Розничная цена: </td><td>54 106.00</td></tr>
        <tr><td>Оптовая цена: </td><td>45 990.10</td></tr>
        <tr><td>Цена аренды: </td><td>6 492.72</td></tr>
        <tr><td>Каждый последующий день: </td><td>811.59</td></tr>
        <tr><td>Вес, кг : </td><td>440.90</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>3.60</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>16720</td></tr>
        <tr><td>Розничная цена: </td><td>58 192.00</td></tr>
        <tr><td>Оптовая цена: </td><td>49 463.20</td></tr>
        <tr><td>Цена аренды: </td><td>6 983.04</td></tr>
        <tr><td>Каждый последующий день: </td><td>872.88</td></tr>
        <tr><td>Вес, кг : </td><td>476.50</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>4.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>18245</td></tr>
        <tr><td>Розничная цена: </td><td>62 551.00</td></tr>
        <tr><td>Оптовая цена: </td><td>53 168.35</td></tr>
        <tr><td>Цена аренды: </td><td>7 506.12</td></tr>
        <tr><td>Каждый последующий день: </td><td>938.27</td></tr>
        <tr><td>Вес, кг : </td><td>514.40</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>4.30</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>19770</td></tr>
        <tr><td>Розничная цена: </td><td>66 637.00</td></tr>
        <tr><td>Оптовая цена: </td><td>56 641.45</td></tr>
        <tr><td>Цена аренды: </td><td>7 996.44</td></tr>
        <tr><td>Каждый последующий день: </td><td>999.56</td></tr>
        <tr><td>Вес, кг : </td><td>550.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>4.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>21295</td></tr>
        <tr><td>Розничная цена: </td><td>70 723.00</td></tr>
        <tr><td>Оптовая цена: </td><td>60 114.55</td></tr>
        <tr><td>Цена аренды: </td><td>8 486.76</td></tr>
        <tr><td>Каждый последующий день: </td><td>1 060.85</td></tr>
        <tr><td>Вес, кг : </td><td>585.60</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>5.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-merdi">
				<div class='h6 text-center'>Вышка-тура МЕРДИ-10 (площадка 1,5*1,0 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2800<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>10 385.00</td></tr>
        <tr><td>Оптовая цена: </td><td>8 827.25</td></tr>
        <tr><td>Цена аренды: </td><td>1 246.20</td></tr>
        <tr><td>Каждый последующий день: </td><td>155.78</td></tr>
        <tr><td>Вес, кг : </td><td>67.94</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.45</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>3300<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>10 963.00</td></tr>
        <tr><td>Оптовая цена: </td><td>9 318.55</td></tr>
        <tr><td>Цена аренды: </td><td>1 315.56</td></tr>
        <tr><td>Каждый последующий день: </td><td>164.45</td></tr>
        <tr><td>Вес, кг : </td><td>71.14</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4400<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>13 404.00</td></tr>
        <tr><td>Оптовая цена: </td><td>11 393.40</td></tr>
        <tr><td>Цена аренды: </td><td>1 608.48</td></tr>
        <tr><td>Каждый последующий день: </td><td>201.06</td></tr>
        <tr><td>Вес, кг : </td><td>94.04</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4900<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>13 982.00</td></tr>
        <tr><td>Оптовая цена: </td><td>11 884.70</td></tr>
        <tr><td>Цена аренды: </td><td>1 677.84</td></tr>
        <tr><td>Каждый последующий день: </td><td>209.73</td></tr>
        <tr><td>Вес, кг : </td><td>97.24</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5400</td></tr>
        <tr><td>Розничная цена: </td><td>16 752.00</td></tr>
        <tr><td>Оптовая цена: </td><td>14 239.20</td></tr>
        <tr><td>Цена аренды: </td><td>2 010.24</td></tr>
        <tr><td>Каждый последующий день: </td><td>251.28</td></tr>
        <tr><td>Вес, кг : </td><td>113.40</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5900</td></tr>
        <tr><td>Розничная цена: </td><td>18 615.00</td></tr>
        <tr><td>Оптовая цена: </td><td>15 822.75</td></tr>
        <tr><td>Цена аренды: </td><td>2 233.80</td></tr>
        <tr><td>Каждый последующий день: </td><td>279.23</td></tr>
        <tr><td>Вес, кг : </td><td>133.10</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.95</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>6400</td></tr>
        <tr><td>Розничная цена: </td><td>19 193.00</td></tr>
        <tr><td>Оптовая цена: </td><td>16 314.05</td></tr>
        <tr><td>Цена аренды: </td><td>2 303.16</td></tr>
        <tr><td>Каждый последующий день: </td><td>287.90</td></tr>
        <tr><td>Вес, кг : </td><td>136.30</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>6900</td></tr>
        <tr><td>Розничная цена: </td><td>19 771.00</td></tr>
        <tr><td>Оптовая цена: </td><td>16 805.35</td></tr>
        <tr><td>Цена аренды: </td><td>2 372.52</td></tr>
        <tr><td>Каждый последующий день: </td><td>296.57</td></tr>
        <tr><td>Вес, кг : </td><td>139.50</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.10</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7400</td></tr>
        <tr><td>Розничная цена: </td><td>20 349.00</td></tr>
        <tr><td>Оптовая цена: </td><td>17 296.65</td></tr>
        <tr><td>Цена аренды: </td><td>2 441.88</td></tr>
        <tr><td>Каждый последующий день: </td><td>305.24</td></tr>
        <tr><td>Вес, кг : </td><td>142.70</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.20</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7900</td></tr>
        <tr><td>Розничная цена: </td><td>22 212.00</td></tr>
        <tr><td>Оптовая цена: </td><td>18 880.20</td></tr>
        <tr><td>Цена аренды: </td><td>2 665.44</td></tr>
        <tr><td>Каждый последующий день: </td><td>333.18</td></tr>
        <tr><td>Вес, кг : </td><td>162.40</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.30</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>8400</td></tr>
        <tr><td>Розничная цена: </td><td>22 790.00</td></tr>
        <tr><td>Оптовая цена: </td><td>19 371.50</td></tr>
        <tr><td>Цена аренды: </td><td>2 734.80</td></tr>
        <tr><td>Каждый последующий день: </td><td>341.85</td></tr>
        <tr><td>Вес, кг : </td><td>165.60</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.35</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>9000</td></tr>
        <tr><td>Розничная цена: </td><td>23 368.00</td></tr>
        <tr><td>Оптовая цена: </td><td>19 862.80</td></tr>
        <tr><td>Цена аренды: </td><td>2 804.16</td></tr>
        <tr><td>Каждый последующий день: </td><td>350.52</td></tr>
        <tr><td>Вес, кг : </td><td>168.80</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.45</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>9400</td></tr>
        <tr><td>Розничная цена: </td><td>23 946.00</td></tr>
        <tr><td>Оптовая цена: </td><td>20 354.10</td></tr>
        <tr><td>Цена аренды: </td><td>2 873.52</td></tr>
        <tr><td>Каждый последующий день: </td><td>359.19</td></tr>
        <tr><td>Вес, кг : </td><td>172.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-tur">
				<div class='h6 text-center'>Вышка-тура Тур-7 (площадка 1,5*0,5 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2910<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>7 860.00</td></tr>
        <tr><td>Оптовая цена: </td><td>6 681.00</td></tr>
        <tr><td>Цена аренды: </td><td>943.20</td></tr>
        <tr><td>Каждый последующий день: </td><td>117.90</td></tr>
        <tr><td>Вес, кг : </td><td>59.48</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.40</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>3880<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>9 066.00</td></tr>
        <tr><td>Оптовая цена: </td><td>7 706.10</td></tr>
        <tr><td>Цена аренды: </td><td>1 087.92</td></tr>
        <tr><td>Каждый последующий день: </td><td>135.99</td></tr>
        <tr><td>Вес, кг : </td><td>69.06</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4850</td></tr>
        <tr><td>Розничная цена: </td><td>10 272.00</td></tr>
        <tr><td>Оптовая цена: </td><td>8 731.20</td></tr>
        <tr><td>Цена аренды: </td><td>1 232.64</td></tr>
        <tr><td>Каждый последующий день: </td><td>154.08</td></tr>
        <tr><td>Вес, кг : </td><td>78.64</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5820</td></tr>
        <tr><td>Розничная цена: </td><td>14 038.00</td></tr>
        <tr><td>Оптовая цена: </td><td>11 932.30</td></tr>
        <tr><td>Цена аренды: </td><td>1 684.56</td></tr>
        <tr><td>Каждый последующий день: </td><td>210.57</td></tr>
        <tr><td>Вес, кг : </td><td>101.18</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>6790</td></tr>
        <tr><td>Розничная цена: </td><td>15 244.00</td></tr>
        <tr><td>Оптовая цена: </td><td>12 957.40</td></tr>
        <tr><td>Цена аренды: </td><td>1 829.28</td></tr>
        <tr><td>Каждый последующий день: </td><td>228.66</td></tr>
        <tr><td>Вес, кг : </td><td>110.76</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-uvt10_1">
				<div class='h6 text-center'>Вышка-тура УВТ-10(площадка 1,5*1,0 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2800<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>11 962.00</td></tr>
        <tr><td>Оптовая цена: </td><td>10 167.70</td></tr>
        <tr><td>Цена аренды: </td><td>1 435.44</td></tr>
        <tr><td>Каждый последующий день: </td><td>179.43</td></tr>
        <tr><td>Вес, кг : </td><td>81.26</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.45</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4300<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>14 620.00</td></tr>
        <tr><td>Оптовая цена: </td><td>12 427.00</td></tr>
        <tr><td>Цена аренды: </td><td>1 754.40</td></tr>
        <tr><td>Каждый последующий день: </td><td>219.30</td></tr>
        <tr><td>Вес, кг : </td><td>101.02</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5800</td></tr>
        <tr><td>Розничная цена: </td><td>19 470.00</td></tr>
        <tr><td>Оптовая цена: </td><td>16 549.50</td></tr>
        <tr><td>Цена аренды: </td><td>2 336.40</td></tr>
        <tr><td>Каждый последующий день: </td><td>292.05</td></tr>
        <tr><td>Вес, кг : </td><td>133.74</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7300</td></tr>
        <tr><td>Розничная цена: </td><td>22 128.00</td></tr>
        <tr><td>Оптовая цена: </td><td>18 808.80</td></tr>
        <tr><td>Цена аренды: </td><td>2 655.36</td></tr>
        <tr><td>Каждый последующий день: </td><td>331.92</td></tr>
        <tr><td>Вес, кг : </td><td>153.50</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.15</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>8800</td></tr>
        <tr><td>Розничная цена: </td><td>24 786.00</td></tr>
        <tr><td>Оптовая цена: </td><td>21 068.10</td></tr>
        <tr><td>Цена аренды: </td><td>2 974.32</td></tr>
        <tr><td>Каждый последующий день: </td><td>371.79</td></tr>
        <tr><td>Вес, кг : </td><td>173.26</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.40</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10300</td></tr>
        <tr><td>Розничная цена: </td><td>27 444.00</td></tr>
        <tr><td>Оптовая цена: </td><td>23 327.40</td></tr>
        <tr><td>Цена аренды: </td><td>3 293.28</td></tr>
        <tr><td>Каждый последующий день: </td><td>411.66</td></tr>
        <tr><td>Вес, кг : </td><td>193.02</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.60</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-uvt10_2">
				<div class='h6 text-center'>Вышка-тура УВТ-10(площадка 2,0*1,0 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2800<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>13 902.00</td></tr>
        <tr><td>Оптовая цена: </td><td>11 816.70</td></tr>
        <tr><td>Цена аренды: </td><td>1 668.24</td></tr>
        <tr><td>Каждый последующий день: </td><td>208.53</td></tr>
        <tr><td>Вес, кг : </td><td>91.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4300<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>16 644.00</td></tr>
        <tr><td>Оптовая цена: </td><td>14 147.40</td></tr>
        <tr><td>Цена аренды: </td><td>1 997.28</td></tr>
        <tr><td>Каждый последующий день: </td><td>249.66</td></tr>
        <tr><td>Вес, кг : </td><td>111.80</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.71</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5800</td></tr>
        <tr><td>Розничная цена: </td><td>21 578.00</td></tr>
        <tr><td>Оптовая цена: </td><td>18 341.30</td></tr>
        <tr><td>Цена аренды: </td><td>2 589.36</td></tr>
        <tr><td>Каждый последующий день: </td><td>323.67</td></tr>
        <tr><td>Вес, кг : </td><td>145.56</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.95</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7300</td></tr>
        <tr><td>Розничная цена: </td><td>24 320.00</td></tr>
        <tr><td>Оптовая цена: </td><td>20 672.00</td></tr>
        <tr><td>Цена аренды: </td><td>2 918.40</td></tr>
        <tr><td>Каждый последующий день: </td><td>364.80</td></tr>
        <tr><td>Вес, кг : </td><td>166.36</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.20</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>8800</td></tr>
        <tr><td>Розничная цена: </td><td>27 062.00</td></tr>
        <tr><td>Оптовая цена: </td><td>23 002.70</td></tr>
        <tr><td>Цена аренды: </td><td>3 247.44</td></tr>
        <tr><td>Каждый последующий день: </td><td>405.93</td></tr>
        <tr><td>Вес, кг : </td><td>187.16</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.45</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10300</td></tr>
        <tr><td>Розничная цена: </td><td>29 804.00</td></tr>
        <tr><td>Оптовая цена: </td><td>25 333.40</td></tr>
        <tr><td>Цена аренды: </td><td>3 576.48</td></tr>
        <tr><td>Каждый последующий день: </td><td>447.06</td></tr>
        <tr><td>Вес, кг : </td><td>207.96</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-uvt15_1">
				<div class='h6 text-center'>Вышка-тура УВТ-15(площадка 1,5*1,5 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2800<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>13 742.00</td></tr>
        <tr><td>Оптовая цена: </td><td>11 680.70</td></tr>
        <tr><td>Цена аренды: </td><td>1 649.04</td></tr>
        <tr><td>Каждый последующий день: </td><td>206.13</td></tr>
        <tr><td>Вес, кг : </td><td>102.16</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.55</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4300<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>16 678.00</td></tr>
        <tr><td>Оптовая цена: </td><td>14 176.30</td></tr>
        <tr><td>Цена аренды: </td><td>2 001.36</td></tr>
        <tr><td>Каждый последующий день: </td><td>250.17</td></tr>
        <tr><td>Вес, кг : </td><td>124.82</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5800</td></tr>
        <tr><td>Розничная цена: </td><td>21 806.00</td></tr>
        <tr><td>Оптовая цена: </td><td>18 535.10</td></tr>
        <tr><td>Цена аренды: </td><td>2 616.72</td></tr>
        <tr><td>Каждый последующий день: </td><td>327.09</td></tr>
        <tr><td>Вес, кг : </td><td>160.44</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.10</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7300</td></tr>
        <tr><td>Розничная цена: </td><td>24 742.00</td></tr>
        <tr><td>Оптовая цена: </td><td>21 030.70</td></tr>
        <tr><td>Цена аренды: </td><td>2 969.04</td></tr>
        <tr><td>Каждый последующий день: </td><td>371.13</td></tr>
        <tr><td>Вес, кг : </td><td>183.10</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.40</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>8800</td></tr>
        <tr><td>Розничная цена: </td><td>27 678.00</td></tr>
        <tr><td>Оптовая цена: </td><td>23 526.30</td></tr>
        <tr><td>Цена аренды: </td><td>3 321.36</td></tr>
        <tr><td>Каждый последующий день: </td><td>415.17</td></tr>
        <tr><td>Вес, кг : </td><td>205.76</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.70</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10300</td></tr>
        <tr><td>Розничная цена: </td><td>30 614.00</td></tr>
        <tr><td>Оптовая цена: </td><td>26 021.90</td></tr>
        <tr><td>Цена аренды: </td><td>3 673.68</td></tr>
        <tr><td>Каждый последующий день: </td><td>459.21</td></tr>
        <tr><td>Вес, кг : </td><td>228.42</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.95</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>11800</td></tr>
        <tr><td>Розничная цена: </td><td>34 662.00</td></tr>
        <tr><td>Оптовая цена: </td><td>29 462.70</td></tr>
        <tr><td>Цена аренды: </td><td>4 159.44</td></tr>
        <tr><td>Каждый последующий день: </td><td>519.93</td></tr>
        <tr><td>Вес, кг : </td><td>255.08</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.25</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>13300</td></tr>
        <tr><td>Розничная цена: </td><td>37 598.00</td></tr>
        <tr><td>Оптовая цена: </td><td>31 958.30</td></tr>
        <tr><td>Цена аренды: </td><td>4 511.76</td></tr>
        <tr><td>Каждый последующий день: </td><td>563.97</td></tr>
        <tr><td>Вес, кг : </td><td>277.74</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.50</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>14800</td></tr>
        <tr><td>Розничная цена: </td><td>40 534.00</td></tr>
        <tr><td>Оптовая цена: </td><td>34 453.90</td></tr>
        <tr><td>Цена аренды: </td><td>4 864.08</td></tr>
        <tr><td>Каждый последующий день: </td><td>608.01</td></tr>
        <tr><td>Вес, кг : </td><td>300.40</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.80</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-uvt15_2">
				<div class='h6 text-center'>Вышка-тура УВТ-15(площадка 2,0*1,5 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2800<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>16 324.00</td></tr>
        <tr><td>Оптовая цена: </td><td>13 875.40</td></tr>
        <tr><td>Цена аренды: </td><td>1 958.88</td></tr>
        <tr><td>Каждый последующий день: </td><td>244.86</td></tr>
        <tr><td>Вес, кг : </td><td>114.10</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.60</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>4300<sup>*</sup></td></tr>
        <tr><td>Розничная цена: </td><td>19 344.00</td></tr>
        <tr><td>Оптовая цена: </td><td>16 442.40</td></tr>
        <tr><td>Цена аренды: </td><td>2 321.28</td></tr>
        <tr><td>Каждый последующий день: </td><td>290.16</td></tr>
        <tr><td>Вес, кг : </td><td>137.80</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.85</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>5800</td></tr>
        <tr><td>Розничная цена: </td><td>24 556.00</td></tr>
        <tr><td>Оптовая цена: </td><td>20 872.60</td></tr>
        <tr><td>Цена аренды: </td><td>2 946.72</td></tr>
        <tr><td>Каждый последующий день: </td><td>368.34</td></tr>
        <tr><td>Вес, кг : </td><td>174.46</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.15</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>7300</td></tr>
        <tr><td>Розничная цена: </td><td>27 576.00</td></tr>
        <tr><td>Оптовая цена: </td><td>23 439.60</td></tr>
        <tr><td>Цена аренды: </td><td>3 309.12</td></tr>
        <tr><td>Каждый последующий день: </td><td>413.64</td></tr>
        <tr><td>Вес, кг : </td><td>198.16</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.45</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>8800</td></tr>
        <tr><td>Розничная цена: </td><td>30 596.00</td></tr>
        <tr><td>Оптовая цена: </td><td>26 006.60</td></tr>
        <tr><td>Цена аренды: </td><td>3 671.52</td></tr>
        <tr><td>Каждый последующий день: </td><td>458.94</td></tr>
        <tr><td>Вес, кг : </td><td>221.86</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>1.75</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>10300</td></tr>
        <tr><td>Розничная цена: </td><td>33 616.00</td></tr>
        <tr><td>Оптовая цена: </td><td>28 573.60</td></tr>
        <tr><td>Цена аренды: </td><td>4 033.92</td></tr>
        <tr><td>Каждый последующий день: </td><td>504.24</td></tr>
        <tr><td>Вес, кг : </td><td>245.56</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>11800</td></tr>
        <tr><td>Розничная цена: </td><td>37 748.00</td></tr>
        <tr><td>Оптовая цена: </td><td>32 085.80</td></tr>
        <tr><td>Цена аренды: </td><td>4 529.76</td></tr>
        <tr><td>Каждый последующий день: </td><td>566.22</td></tr>
        <tr><td>Вес, кг : </td><td>273.26</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.30</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>13300</td></tr>
        <tr><td>Розничная цена: </td><td>40 768.00</td></tr>
        <tr><td>Оптовая цена: </td><td>34 652.80</td></tr>
        <tr><td>Цена аренды: </td><td>4 892.16</td></tr>
        <tr><td>Каждый последующий день: </td><td>611.52</td></tr>
        <tr><td>Вес, кг : </td><td>296.96</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.60</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>14800</td></tr>
        <tr><td>Розничная цена: </td><td>43 788.00</td></tr>
        <tr><td>Оптовая цена: </td><td>37 219.80</td></tr>
        <tr><td>Цена аренды: </td><td>5 254.56</td></tr>
        <tr><td>Каждый последующий день: </td><td>656.82</td></tr>
        <tr><td>Вес, кг : </td><td>320.66</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>2.90</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
			<div class="tab-block" id="prices-smp4">
				<div class='h6 text-center'>Строительный помост СМП-4 (площадка 1,5*0,5 м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>2910</td></tr>
        <tr><td>Розничная цена: </td><td>6 117.00</td></tr>
        <tr><td>Оптовая цена: </td><td>5 199.45</td></tr>
        <tr><td>Цена аренды: </td><td>734.04</td></tr>
        <tr><td>Каждый последующий день: </td><td>91.76</td></tr>
        <tr><td>Вес, кг : </td><td>50.16</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>3880</td></tr>
        <tr><td>Розничная цена: </td><td>7 323.00</td></tr>
        <tr><td>Оптовая цена: </td><td>6 224.55</td></tr>
        <tr><td>Цена аренды: </td><td>878.76</td></tr>
        <tr><td>Каждый последующий день: </td><td>109.85</td></tr>
        <tr><td>Вес, кг : </td><td>59.74</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>

			<div class="tab-block" id="prices-ps15">
				<div class='h6 text-center'>Строительный помост ПС-1,5(площадка 1,5*0,7м.)</div>
				
      <table class='tableMob shadow mb-3 bg-white rounded'>
        <tr><td>Высота вышки (общая), мм: </td><td>1500</td></tr>
        <tr><td>Розничная цена: </td><td>6 320.00</td></tr>
        <tr><td>Оптовая цена: </td><td>5 372.00</td></tr>
        <tr><td>Цена аренды: </td><td>758.40</td></tr>
        <tr><td>Каждый последующий день: </td><td>94.80</td></tr>
        <tr><td>Вес, кг : </td><td>27.00</td></tr>
        <tr><td>Объём М<sup>3</sup>: </td><td>0.00</td></tr>
        <tr>
        <td colspan='2'><div class='buy-btn btn-red getorderform' data-typeProd='vyshki-turaMob'>Оформить заказ</div></td> 
       </tr>
      </table>
      			</div>
		</div>
	</div>
</section>
	<section>
	<div class="container elements-section" id="elements-section" style="clear: both;">
		<h2 class="h1 text-center">Элементы строительных лесов</h2>
		<div class="row">
			<div class="col-md-6  col-xs-12">
				<div class="element">
					
					<a href="./nastily-dlya-stroitelnyh-lesov.php">
					<img src="~/assets/img/ehlementy-stroitelnyh-lesov/nastily-dlya-stroitelnyh-lesov.jpg" alt="">
					Настилы для лесов</a>
				</div>
			</div>
			<div class="col-md-6 col-xs-12">
				<div class="element">
					<a href="./lestnicy-dlya-stroitelnyh-lesov.php">
					<img src="~/assets/img/ehlementy-stroitelnyh-lesov/lestnicy-dlya-stroitelnyh-lesov.jpg" alt="">	
					Лестницы для лесов</a>
				</div>
			</div>
			<div class="col-md-6 col-xs-12">
				<div class="element">
					<a href="https://xn----8sbemb9a1be.xn--p1ai/homuty-dlya-lesov.php">
					<img src="~/assets/img/ehlementy-stroitelnyh-lesov/homuty-dlya-stroitelnyh-lesov.jpg" alt="">	
					Хомуты для лесов</a>
				</div>
			</div>
			<div class="col-md-6 col-xs-12">
				<div class="element">
					<a href="#">
					<img src="~/assets/img/ehlementy-stroitelnyh-lesov/ehlementy-stroitelnyh-lesov.jpg" alt="">	
					Другие элеметы</a>
				</div>
			</div>
		</div>
	</div>
</section>

</div>

</template>

<script>

import { Tabs, Tab } from 'vue-slim-tabs'


export default {

components: {
    Tabs, Tab
},

}
</script>

<style>

</style>
