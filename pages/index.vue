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

<ramnielesa />

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

		<Tabvishkaprice />
		
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

mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()
      setTimeout(() => this.$nuxt.$loading.finish(), 2000)
    })
  }

}
</script>

<style>

</style>
