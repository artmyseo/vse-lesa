<template>

<div>
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
								<div class="col-md-6 col-xs-12">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/31Ue7G5Ffy4?rel=0" frameborder="0" allowfullscreen></iframe>
								</div>
								<div class="col-md-6 col-xs-12">
									<iframe width="100%" height="315" src="https://www.youtube.com/embed/wOEi_EoE0gY?rel=0" frameborder="0" allowfullscreen></iframe>
								</div>
							</div>
						</tab>
					</tabs>	

					<div class="discountblock" :class="{inview: checkView(0)}">
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
	
						
							<div class="col-sm-6 productbuttons">
								<div class="btn-group " role="group">
									<button type="button" data-nameprod='Рамные леса серии ЛР-10' class="btn btn-black-custom report">Комплектация</button>
									<button type="button" class="btn btn-black-custom save">Сохранить</button>
								</div>
								<button class="btn btn-danger-fill-custom cart getorderform" data-typeProd='lesa' @click="showModal = true">Оформить заказ</button>
							</div>
							<input type="hidden" name="datas">
							<input type="hidden" name="datajson">
						
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
    scrollTop: '',
    scrollBottom: '',
    animate: '',
	max: 235000,
	val: 234800,
	showModal: false
   };
},
  methods: {
    checkView(e){
      if(this.animate){
    //    let element = this.animate[e];
    //    let elTop = element.offsetTop;
    //    let elBottom = element.offsetTop + element.scrollHeight;
	
    if(this.scrollBottom > 1000){
          return true;
       } else {
          return false;
    	}
      }
    },
    scrollHandler(){
      this.scrollBottom = window.scrollY + window.innerHeight;
      this.scrollTop = window.scrollY;
    }
  },
  mounted(){
    this.scrollTop = window.scrollY;
    this.scrollBottom = window.scrollY + window.innerHeight;
    window.addEventListener('scroll', _.throttle(this.scrollHandler, 300))
    this.animate = document.querySelectorAll(".discountblock")
  }


  }
</script>

<style scoped>

.discountblock{
	opacity: 0.1;	
}

.inview{
	opacity: 1;
	transition: 1.5s;
}

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

