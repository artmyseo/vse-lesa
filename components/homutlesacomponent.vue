<template>
    <section class="lesa-section homut-section" id="homut-section">
	<div class="topbar topbarhomut">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<div class="namesection">
						<a href="/homutovye-lesa">Хомутовые леса</a>
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
				<div class="col-md-12">
					<tabs class="nav nav-text nav-stacked">
    					<tab title="Описание">
							<p class="justifyfull">Строительные леса хомутового типа используются при работах со сложными объектами, устанавливаются даже в самых труднодоступных местах. Например, используются для фасадных или высотных работ, реставрации памятников, храмов и т.д. Представляют собой трубчатые многоярусные и многосекционные металлоконструкции, все элементы которых соединяются поворотными и глухими хомутами. Высота данного вида лесов варьируется от 30 до 80 м, а нагрузка при фасадных работах – 200 кг/м&sup2; (при каменной кладке – от 300 до 500 кг/м&sup2; в зависимости от вида хомутовых лесов).</p>
							<div class="row">
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_1_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_2_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_3_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_4_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_5_s.jpg" alt="..."><span></span></a></div>
								<div class="col-sm-2 col-xs-4"><a data-lightbox="homutovyelesa" class="imagelink" href="/photo/homutovye-lesa/homutovye-lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/homutovye-lesa/homutovye-lesa_6_s.jpg" alt="..."><span></span></a></div>
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
</template>

<script>
import { Tabs, Tab } from 'vue-slim-tabs'

export default {

components: {
    Tabs, Tab
},
  }
</script>

