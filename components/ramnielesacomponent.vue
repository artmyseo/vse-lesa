<template>
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
    					<tab title="Описание" class="desc">
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
						<tab title="Видео" class="video">
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
</template>

<script>
import { Tabs, Tab } from 'vue-slim-tabs'

export default {

components: {
    Tabs, Tab
},
  }
</script>

