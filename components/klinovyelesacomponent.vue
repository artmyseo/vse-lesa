<template>
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
					<div class="col-md-12">

					<tabs class="nav nav-text nav-stacked">
    					<tab title="Описание">
								<p class="justifyfull">Строительные леса клинового типа являются надежными и универсальными, простыми в монтаже и демонтаже, что обеспечивает огромный спрос на них. Используются при ремонтно-строительных работах домов, в судостроении, при установке концертных площадок и сцен для шоу-программ. Что касается способа крепления, то клин забивают и расклинивают во фланцевый замок, который устроен таким образом, что самопроизвольное выпадение клина невозможно. Максимальная высота установки клиновых лесов варьируется от 60 до 100 м. Изготавливаются из труб диаметром 48 мм, при этом нагрузка при фасадных работах – 200 кг/м&sup2; (при каменной кладке – 500 кг/м&sup2;).</p>
								<div class="row">
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_1.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_1_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_2.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_2_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_3.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_3_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_4.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_4_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_5.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_5_s.jpg" alt="..."><span></span></a></div>
									<div class="col-sm-2 col-xs-4"><a data-lightbox="klinovyelesa" class="imagelink" href="/assets/photo/klinovye-lesa/klinovye-lesa_6.jpg"><img class="b-lazy img-thumbnail" src="~/assets/photo/klinovye-lesa/klinovye-lesa_6_s.jpg" alt="..."><span></span></a></div>
								</div>
						</tab>
						<tab title="Видео">
							<div class="row">
								<div class="col-md-6 col-xs-12">
										<iframe width="100%" height="315" src="https://www.youtube.com/embed/cuMiD0OeZcA?rel=0" frameborder="0" allowfullscreen></iframe>
									</div>
								<div class="col-md-6 col-xs-12">
										<iframe width="100%" height="315" src="https://www.youtube.com/embed/zzLM14bbz2k?rel=0" frameborder="0" allowfullscreen></iframe>
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
</template>

<script>
import { Tabs, Tab } from 'vue-slim-tabs'

export default {

components: {
    Tabs, Tab
},
  }
</script>

