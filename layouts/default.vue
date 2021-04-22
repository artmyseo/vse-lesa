<template>
<div>
<section class="topblock">
		<div class="header">
			<div class="container">
				<div class="row">
					<div class="col-md-8 col-xs-12">
						<a class="logo" href="/">
							<img class="retina-hidden" src="~/assets/img/logo.png" alt="Комбинат Строительных Конструкций"><img
								class="retina-show" src="~/assets/img/logo-top@2x.png"
								alt="Комбинат Строительных Конструкций"></a>
						<div class="desccomp">
							<b>Завод строительных лесов:</b><br> производство, аренда и продажа металлоконструкций
						</div>
					</div>
					<div class="col-md-4 col-xs-12">
						<div class="phoneblock">
							<div class="phone"><a href="tel: +7 (800) 700-25-19">8 (800)<b>700-25-19</b></a></div>
							<a data-toggle="modal" data-target=".backСall" class="callme">Заказать обратный звонок</a>
						</div>
						<div class="messenger">
							<a href="//wa.me/79255186487" rel="whatsapp"></a>
							<a href="viber://chat?number=79255186487" rel="viber"></a>
							<a title="Telegram" href="tg://resolve?domain=pkmdnprom" rel="telegram"></a>
						</div>
					</div>
				</div>
			</div>
		</div>

		<div class="info-top">
			<div class="container">
				<div class="row">
					<div class="col-md-8 info">
						<div class="info-row"><span>Строительные леса</span></div>
						<div class="clearfix"></div>
						<div class="info-row">всех видов</div>
						<div class="clearfix"></div>
						<div class="info-row">с гарантией <span>от производителя</span></div>
					</div>
					<div class="col-md-4">
						<div class="formwrapper">
							<div class="topform">
								<div class="callgoform">Закажите строительные леса сейчас и<br><span>получите скидку
										15%</span><br>
									<span class="doptext">При заказе на сумму от 235 000 руб.</span></div>
								<form class="callMeForm">
									<div class="inputs">
										<div class="form-group">
											<input type="text" class="form-control" id="cmname" name="name"
												placeholder="Ваше имя">
										</div>
										<div class="centerfull">
											<div class="cmline"></div>
										</div>
										<div class="form-group">
											<input type="text" class="form-control phoneInput" id="cmphone" name="phone"
												placeholder="Ваш телефон">
										</div>
										<div class="centerfull">
											<div class="cmline"></div>
										</div>
										<div class="form-group">
											<input type="text" class="form-control" id="cmemail" name="email"
												placeholder="Ваш e-mail (необязательно)">
										</div>
									</div>
									<div class="clearfix"></div>
									<div class="checkbox">
										<label>
											<input type="checkbox" data-toggle="checkbox" name="subscribe" checked>
											Подписаться на акции и спецпредложения
										</label>
									</div>
									<div class="centerfull">
										<button type="submit" class="btn btn-order">ЗАКАЗАТЬ СТРОИТЕЛЬНЫЕ ЛЕСА</button>
									</div>
								</form>
							</div>
						</div>

					</div>
				</div>
			</div>
		</div>
	</section>
	<section class="topmenu">
		<div class="conrainer">
			<div class="btn-group top-btn-group hidden-sm hidden-md hidden-lg" role="group">
				<button type="button" class="btn btn-left orderlink">Заказ<br>лесов</button>
				<button type="button" class="btn btn-right newcalc">Расчет<br>лесов</button>
			</div>
			<nav role="navigation" class="navbar">
				<!-- Логотип и мобильное меню -->
				<div class="navbar-header">
					<button type="button" data-target="#navbarCollapse" data-toggle="collapse" class="navbar-toggle">
						<span class="sr-only">Toggle navigation</span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
				</div>
				<!-- Навигационное меню -->
				<div id="navbarCollapse" class="collapse navbar-collapse">
					<ul class="nav navbar-nav">
						<li class="rama"><NuxtLink to="/ramnye-lesa">Рамные леса</NuxtLink></li>
						<li class="klin"><NuxtLink to="/klinovye-lesa">Клиновые леса</NuxtLink></li>
						<li class="shtir"><NuxtLink to="/shtyrevye-lesa">Штыревые леса</NuxtLink></li>
						<li class="homut"><NuxtLink to="/homutovye-lesa">Хомутовые леса</NuxtLink></li>
						<li class="tura"><a href="vyshki-tura.php">Вышки-тура</a></li>
						<li><a class="comparison">Сравнить цены</a></li>
						<li class="uslugi"><a href="arenda">Аренда</a></li>
						<li class="uslugi dropdown"><a href="" id="drop1" class="dropdown-toggle" data-toggle="dropdown">Услуги<span class="caret"></span></a> 
							<ul class="dropdown-menu" aria-labelledby="drop1">
								<li><a href="#">Монтаж лесов</a></li>
								<li><a href="/ocinkovannye-stroitelnye-lesa">Оцинковка лесов и вышек</a></li>
								<li><a href="#">3D модели лесов</a></li>
								<li><a href="#">Выкуп б/у лесов</a></li>
							</ul>
						</li>
						<li class="contacts"><a href="contacts">Контакты</a></li>
						<li class="phone hidden-sm">8 (800) 700-25-19</li>
					</ul>
				</div>
			</nav>
		</div>
	</section>

	<section class="line-lesa">
		<div class="container">
			<div class="row">
				<div class="col-md-2 col-xs-6 lesa-block lb-rama fastlink">
          <NuxtLink to="/ramnye-lesa">
					<div class="title">Рамные<br> леса</div>
					<div class="icon icon-rama"></div>
          <div class="overlay"></div>
          </NuxtLink>
				</div>
				<div class="col-md-2 col-xs-6 lesa-block lb-klin fastlink">
          <NuxtLink to="/klinovye-lesa">
					<div class="title">Клиновые<br> леса</div>
					<div class="icon icon-klin"></div>
          <div class="overlay"></div>
          </NuxtLink>
				</div>
				<div class="col-md-2 col-xs-6 lesa-block lb-shtir fastlink">
          <NuxtLink to="/shtyrevye-lesa">
					<div class="title">Штыревые<br> леса</div>
					<div class="icon icon-shtir"></div>
          <div class="overlay"></div>
          </NuxtLink>
				</div>
				<div class="col-md-2 col-xs-6 lesa-block lb-homut fastlink">
          <NuxtLink to="/homutovye-lesa">
					<div class="title">Хомутовые<br> леса</div>
					<div class="icon icon-homut"></div>
          <div class="overlay"></div>
          </NuxtLink>
				</div>
				<div class="col-md-2 col-xs-6 lesa-block lb-vyshki fastlink">
					<div class="title">Вышки <br> тура</div>
					<div class="icon icon-vyshki"></div>
          <div class="overlay"></div>
				</div>
				<div class="col-md-2 col-xs-6 lesa-block lb-elements fastlink"  id='homuty'>
					<div class="title">Элементы<br> лесов</div>
					<div class="icon icon-element"></div>
          <div class="overlay"></div>
				</div>
			</div>
		</div>
</section>


 


    <Nuxt />







 

<section class="how-work">
	<div class="container">
		<div class="row">
			<div class="col-md-12" style="text-align: center;">
				<div class="title-block">
					<h2>Как мы работаем</h2>
					<span></span>
				</div>
			</div>
		</div>
		<div class="row how-work-blocks">
			<div class="col-sm-2 block">
				<div class="title-block">Связь с<br>менеджером</div>
				<div class="icon icon-1"></div>
			</div>
			<div class="col-sm-2 block la">
				<div class="title-block">Оформление<br>заявки</div>
				<div class="icon icon-2"></div>
			</div>
			<div class="col-sm-2 block la">
				<div class="title-block">Согласование<br>заказа</div>
				<div class="icon icon-3"></div>
			</div>
			<div class="col-sm-2 block la">
				<div class="title-block">Оплата<br>заказа</div>
				<div class="icon icon-4"></div>
			</div>
			<div class="col-sm-2 block la">
				<div class="title-block">Доставка<br>или самовывоз</div>
				<div class="icon icon-5"></div>
			</div>
			<div class="col-sm-2 block la">
				<div class="title-block">Взаимовыгодное<br>сотрудничество</div>
				<div class="icon icon-6"></div>
			</div>
		</div>
	</div>
</section>

<section class="mapCont">
	<div id="bigmap" class="hidden-xs"></div>
	<div class="topline">
		<div class="container">
			<div class="row">
				<div class="col-md-12" style="text-align: center;">
					<div class="title-block">
						<h2>Контакты</h2>
						<span></span>
					</div>
				</div>
			</div>
			<div class="row">
				<div class="col-sm-4 col-xs-12 locItem goto" data-goto="serpuhov">
					<div class="town">СЕРПУХОВ</div>
					<div class="addr">Московское ш., д. 53</div>
					<div class="phone">Тел.: +7 (495) 518-64-87</div>
					<div class="mphone">Моб. тел.: + 7 (925) 518-64-87</div>
					<div class="email">E-mail: <span>
							<script>var x1,x2,x3,x4,x5,x6,x7; x1='<a href="'; x1+='mai'; x1+='lto:'; x2 ='&#115;&#97;&#108;&#101;&#115;'; x3 ='&#64;'; x4 ='&#109;&#100;&#110;&#45;&#112;&#114;&#111;&#109;&#46;&#114;&#117;'; x5 ='">'; x6 = x2+'&#64;'+x4 ; x7 ='</a>';document.write(x1+x2+x3+x4+x5+x6+x7);</script><noscript>[Включите JavaScript]</noscript></span></div>
				</div>
				<div class="col-sm-4 col-xs-12 locItem goto" data-goto="unecha">
					<div class="town">Унеча</div>
					<div class="addr">ул.Крупской, д. 12</div>
					<div class="phone">Тел.: +7 (4832) 33-27-48</div>
					<div class="mphone">Моб. тел.: +7 (910) 237-69-35</div>
					<div class="email">E-mail: <span>
							<script>document.write('<' + 'a' + ' ' + 'h' + 'r' + 'e' + 'f' + '=' + "'" + '&' + '#' + '1' + '0' + '9' + ';' + '&' + '#' + '9' + '7' + ';' + 'i' + '&' + '#' + '1' + '0' +
									'8' + ';' + 't' + 'o' + '&' + '#' + '5' + '8' + ';' + 's' + '&' + '#' + '1' + '1' + '6' + ';' + '&' + '#' + '9' + '7' + ';' + '&' + '#' + '1' + '0' +
									'8' + ';' + '&' + '#' + '1' + '1' + '8' + ';' + '%' + '6' + '9' + '&' + '#' + '6' + '4' + ';' + 'm' + 'a' + 'i' + 'l' + '&' + '#' + '4' + '6' + ';' +
									'r' + '&' + '#' + '3' + '7' + ';' + '&' + '#' + '5' + '5' + ';' + '&' + '#' + '5' + '3' + ';' + "'" + '>' + '&' + '#' + '1' + '1' + '5' + ';' + '&' +
									'#' + '1' + '1' + '6' + ';' + '&' + '#' + '9' + '7' + ';' + 'l' + '&' + '#' + '1' + '1' + '8' + ';' + 'i' + '&' + '#' + '6' + '4' + ';' + 'm' + '&' +
									'#' + '9' + '7' + ';' + 'i' + 'l' + '&' + '#' + '4' + '6' + ';' + 'r' + '&' + '#' + '1' + '1' + '7' + ';' + '<' + '/' + 'a' + '>');</script>
							<noscript>[Включите JavaScript]</noscript></span></div>
				</div>
				<div class="col-sm-4 col-xs-12 locItem goto" data-goto="kazan">
					<div class="town">Казань</div>
					<div class="addr">ул. Гвардейская, д. 53</div>
					<div class="phone">Тел.: +7 (8432) 03-31-42</div>
					<div class="mphone">Моб. тел.: +7 (926) 085-75-22</div>
					<div class="email">E-mail: <span>
							<script>document.write('<' + 'a' + ' ' + 'h' + 'r' + 'e' + 'f' + '=' + "'" + 'm' + '&' + '#' + '9' + '7' + ';' + 'i' + 'l' + 't' + '&' + '#' + '1' + '1' + '1' + ';' + '&' +
									'#' + '5' + '8' + ';' + 'm' + 'd' + '&' + '#' + '1' + '1' + '0' + ';' + '&' + '#' + '4' + '5' + ';' + 'k' + '%' + '6' + '1' + 'z' + 'a' + 'n' + '&' +
									'#' + '3' + '7' + ';' + '&' + '#' + '5' + '2' + ';' + '0' + '&' + '#' + '1' + '0' + '9' + ';' + 'a' + '&' + '#' + '3' + '7' + ';' + '6' + '9' + 'l' +
									'&' + '#' + '4' + '6' + ';' + '%' + '7' + '2' + '&' + '#' + '1' + '1' + '7' + ';' + "'" + '>' + 'm' + 'd' + 'n' + '-' + '&' + '#' + '1' + '0' + '7' +
									';' + 'a' + 'z' + 'a' + '&' + '#' + '1' + '1' + '0' + ';' + '&' + '#' + '6' + '4' + ';' + 'm' + 'a' + 'i' + '&' + '#' + '1' + '0' + '8' + ';' + '&' +
									'#' + '4' + '6' + ';' + 'r' + 'u' + '<' + '/' + 'a' + '>');</script><noscript>[Включите JavaScript]</noscript></span></div>
				</div>
			</div>
		</div>
	</div>
</section>
<section class="footer">
	<div class="container">
		<div class="row">
			<div class="col-sm-5 namecomp">
				<b>Завод строительных лесов:</b><br>производство, аренда и продажа металлоконструкций
			</div>
			<div class="col-sm-3">
				<div class="title-soc">мы в соцсетях:</div>
				<ul class="socicons">
					<li><a href="https://vk.com/stroitelnye_lesa" alt="Мы Вконтакте" class="icon-1"></a></li>
					<li><a href="https://www.facebook.com/%D0%9B%D0%B5%D1%81%D0%B0-%D0%A1%D1%82%D1%80%D0%BE%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-812341352180293"
							alt="Мы на Facebook" class="icon-2"></a></li>
					<li><a href="https://twitter.com/lesa_stroy" alt="Мы в Twitter" class="icon-3"></a></li>
				</ul>
			</div>
			<div class="col-sm-4 android" alt="Расчет строительных лесов для Android"
				onClick="window.location='https://play.google.com/store/apps/details?id=ru.mdnvizit.scaffoldcalc'">
				Скачать приложение для
				<span>Android</span>
			</div>
		</div>
		<div class="row lesaRow">

			<div class="col-md-8 col-xs-12">
				<div class="row">
					<div class="col-md-6 col-sm-6">
						<h3><a class="animlink" href="https://lesa-rama.ru/">РАМНЫЕ ЛЕСА</a></h3>
						<span class="border"></span>
						<div class="clearfix"></div>
						<ul>
							<li><a class="animlink" href="https://lesa-rama.ru/lr-10.php" target='_blank'>ЛР-10</a></li>
							<li><a class="animlink" href="https://lesa-rama.ru/lrp-20.php" target='_blank'>ЛРП 2000-20</a></li>
							<li><a class="animlink" href="https://lesa-rama.ru/lrp-40.php" target='_blank'>ЛРП 2000-40</a></li>
							<li><a class="animlink" href="https://lesa-rama.ru/lrp-60.php" target='_blank'>ЛРП 2000-60</a></li>
							<li><a class="animlink" href="https://lesa-rama.ru/lrp-80.php" target='_blank'>ЛРП 2000-80</a></li>
							<li><a class="animlink" href="https://lesa-rama.ru/lrp-100.php" target='_blank'>ЛРП 2000-100</a></li>
							<!-- end ul -->
						</ul>
					</div>

					<div class="col-md-6 col-sm-6">
						<h3><a class="animlink" href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/">ХОМУТОВЫЕ ЛЕСА</a></h3>
						<span class="border"></span>
						<div class="clearfix"></div>
						<ul>
							<li><a class="animlink"
									href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/xomutovyie-lesa/lh-30-l.html" target='_blank'>ЛХ 30-Л</a>
							</li>
							<li><a class="animlink"
									href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/xomutovyie-lesa/xomutovyie-lesa-lx-40.html" target='_blank'>ЛХ
									40</a></li>
							<li><a class="animlink"
									href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/xomutovyie-lesa/lh-40-us.html" target='_blank'>ЛХ
									40-УС</a></li>
							<li><a class="animlink"
									href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/xomutovyie-lesa/lh-60.html" target='_blank'>ЛХ 60</a></li>
							<li><a class="animlink"
									href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/xomutovyie-lesa/lh-80-v.html" target='_blank'>ЛХ 80-В</a>
							</li>
							<li><a class="animlink"
									href="//xn----8sbemb9adpb9aelx4g.xn--p1ai/xomutovyie-lesa/lh-80-v.html" target='_blank'>ЛХ 80-УС</a>
							</li>
							<!-- end ul -->
						</ul>
					</div>
					<div class="col-md-6 col-sm-6">
						<h3><a class="animlink" href="https://klinovye-lesa.ru/" target='_blank'>КЛИНОВЫЕ ЛЕСА</a></h3>
						<span class="border"></span>
						<div class="clearfix"></div>
						<ul>
							<li><a class="animlink" href="https://klinovye-lesa.ru/lsk-60.php" target='_blank'>ЛСК-60</a></li>
							<li><a class="animlink" href="https://klinovye-lesa.ru/lsk-100.php" target='_blank'>ЛСК-100</a></li>
						</ul>
						<!-- end ul -->
					</div>
					<div class="col-md-6 col-sm-6">
						<h3><a class="animlink" href="//xn----8sbelbb5b9apc9dubd.xn--p1ai/" target='_blank'>ШТЫРЕВЫЕ ЛЕСА</a></h3>
						<span class="border"></span>
						<div class="clearfix"></div>
						<ul>
							<li><a class="animlink"
									href="//xn----8sbelbb5b9apc9dubd.xn--p1ai/shtyirevyie-lesa/lsh-50.html" target='_blank'>ЛШ-50</a>
							</li>
							<li><a class="animlink"
									href="//xn----8sbelbb5b9apc9dubd.xn--p1ai/shtyirevyie-lesa/lsh-100.html" target='_blank'>ЛШ-100</a>
							</li>
							<!-- end ul -->
						</ul>
					</div>

					<div class="col-md-6 col-sm-6">
						<h3><a class="animlink" href="https://xn----8sbeyj2bni4b3a.xn--p1ai/" target='_blank'>ВЫШКИ-ТУРА</a></h3>
						<span class="border"></span>
						<div class="clearfix"></div>
					</div>
					<div class="col-md-6 col-sm-6">
						<h3><a class="animlink" href="https://formworks.ru/" target='_blank'>Объемная опалубка</a></h3>
						<span class="border"></span>
						<div class="clearfix"></div>
					</div>
				</div>
			</div>

			<div class="col-md-4 col-xs-12">

				<div class="contact">
					<h3>ПОЛЕЗНАЯ ИНФОРМАЦИЯ</h3>
					<span class="border"></span>
					<div class="clearfix"></div>
					<ul>
						<li><a href="o_kompanii.php">О компании</a></li>
						<li><a href="contacts.php">Контакты</a></li>
						<li><a href="https://xn----8sbemb9a1be.xn--p1ai/articles.php">Статьи</a></li>
						<li><a data-toggle="modal" data-target="#siteMap">Карта сайта</a></li>
						<li><a href="fotogalereya.php">Фото-Видео галерея</a></li>
					</ul>
					<p><b>Телефоны менеджеров отдела продаж:</b></p>
					<span class="border"></span>
					<div class="clearfix"></div>
					<p>Инна Михайлова <a href="tel: +7 (926) 085-77-54">+7 (926) 085-77-54</a></p>
					<p>Марина Езерская <a href="tel: +7 (926) 085-77-95">+7 (926) 085-77-95</a></p>
					<p>Надежда Шестакова <a href="tel: +7 (926) 085-74-94">+7 (926) 085-74-94</a></p>
					<p><b>Телефон менеджера отдела аренды:</b></p>
					<p>Светлана Елисеева <a href="tel: +7 (966) 331-14-97">+7 (966) 331-14-97</a></p>
				</div>

			</div>

		</div>
	</div>
</section>

<div class="modal fade modalOrder customModal zoom-out 2" tabindex="-1" role="dialog">
	<div class="modal-dialog modal-md">
		<div class="modal-content">
			<form class="orderForm">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span
							aria-hidden="true">&times;</span></button>
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
		</div><!-- /.modal-content -->
	</div><!-- /.modal-dialog -->
</div>


<input type="hidden" name="ip" value="2a00:ab00:1103:7:10::1">
<input type="hidden" name="referer" value="https://xn----8sbemb9a1be.xn--p1ai:80/pagesInCache/index_cache.php">

<!--MDN Calculators-->
<script src="//lesa-sales.ru/calculator/js/rama.php" async></script>
<script src="//lesa-sales.ru/calculator/js/klin2.php" async></script>
<!-- <script src="https://xn----8sbemb9a1be.xn--p1ai/js/klin2.php" async></script> -->
<script src="//lesa-sales.ru/calculator/js/shtir.php" async></script>
<script src="//lesa-sales.ru/calculator/js/homut2.php" async></script>
<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->

<script src="/bootstrap3/js/bootstrap.min.js" defer></script>
<!-- MDN -->
<script type="text/javascript" src="//lesa-sales.ru/email/helpers/popup.js?v=1.2"></script>
<link href="//lesa-sales.ru/email/helpers/popup.css?v=1.2" rel="stylesheet" type="text/css" media="all" />


<!-- Canvas -->
<!-- <script src="js/canvas/html2canvas.min.js"></script>
							<script src="js/canvas/jquery.plugin.html2canvas.js"></script>
							
							<script>
							
								html2canvas(document.querySelector('.product')).then(canvas => {
								    document.body.appendChild(canvas);
								    console.log('test');
								});
							
							</script> -->


	<div class="modal fade reportModal" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">

      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Элементы</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>

      <div class="table-source">
        <div class="h6">Исходные данные</div>
        <table></table>
      </div>
      
      <div class="table-elements">
        <div class="h6">Элементы конструкции</div>
        <table></table>
      </div>
    </div>
  </div>
</div>



<div class="modal fade" id="FormTable" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
        <h4 class="modal-title" id="myModalLabel">Оформление заявки <span class="formTableTitle"></span></h4>
      </div>
      <div class="modal-body">
        <form class="puForm">
          <span>Оставьте контактные данные и мы свяжемся с Вами!</span>
          <p><input type="text" name="name" placeholder="Введите ваше имя"></p>
          <p><input type="text" name="phone" placeholder="Введите ваш телефон"></p>
          <p><input type="text" name="email" placeholder="Введите ваш email"></p>
          <div class="checkbox_personalInformation form-group">
              <input type="checkbox" class="personalInformation" name="personalInformation">
						  <label class="custom-control-label" for="personalInformationVseLesa">Я согласен с условиями политики конфиденциальности <a href="https://xn----8sbemb9a1be.xn--p1ai/personal_information.php" target="_blank">Подробнее</a></label>
            </div>
        </form>

        <div class="arendaBlock">
          <div class="countRent">
            <span>Количество дней аренды </span>
            <div class="countGroup" data-placement="top" data-content="Минимальное количество дней аренды: 30 дней">
                <div class="minus TabRentcount active"></div>
                <input class="form-control countItem" name="countElement" id="count1Elem1" value="30">
                <div class="plus TabRentcount active"></div>
            </div>
          </div>

          <div class="fix_price_rent"></div>
          <div class="price_rent"></div>
        </div>

      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Закрыть</button>
        <button type="button" class="btn btn-primary submitFormTable">Отправить</button>
      </div>
    </div>
  </div>
</div>


<div class="modal fade" id="comparison" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">

      <div class="row headerComparison"> 

        <div class="col-xs-12 col-md-2">
          <img src="~/assets/img/logo.png" alt="">
        </div>
        <div class="col-xs-12 col-md-10">
          <span>ООО "Производственная компания МДН-Пром" г.Cерпухов<br> 
            <a href="#">8 (800) 700-25-19</a> /
            <a href="mailto:sales@mdn-prom.ru">sales@mdn-prom.ru</a>
          </span>

        </div>

        <button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>

      </div>

      <div class="row comparisonTable">

        <div class="col-xs-12 col-md-3"><span>Сравнательная таблица</span></div>

        <div class="col-xs-12 col-md-9">

          <ul class="nav nav-pills nav-justified tableComparison">
            <li class="active"><a href="#byu" data-toggle="tab">Покупки строительных лесов</a></li>
            <li><a href="#rent" data-toggle="tab">Аренды строительных лесов (стоимость за 30 дней)</a></li>
          </ul>

        </div>
      </div>

      <div class="row initialData">
        <div class="col-md-8"><span>Исходные данные расчета строительных лесов</span></div>
        <div class="col-md-4">

          <div rel="height" class="initialDataShow">
            <p>Высота</p>
            <span></span>
          </div>
          <div rel="lenght" class="initialDataShow">
            <p>Длина</p>
            <span></span>
          </div>
          <div rel="nastil" class="initialDataShow">
            <p>Настилов</p>
            <span></span>
          </div>

        </div>
      </div>

      <div class="row" rel="select">
          <div class="col-xs-12">
            <span><span>*</span> Выберите комлпект лесов для оформления заявки</span>
          </div>
      </div>

      <div class="row">
        <div class="col-xs-12">
       
          <div class="tab-content">

            <div class="tab-pane fade in active" id="byu">

              <div class="row buy text-center">

                <div class="col-xs-12 col-md-6">
                  <table rel="ramlesa" data-id="1">
                    <tr>
                      <th colspan="6">Рамные леса <span class="priceLink" data-html="true" data-container="body" data-toggle="popover" data-placement="bottom" data-content='
                <div class="price-block">
                  <div class="title">Прайс Рамные леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>
                    <!-- <div data-html="true" data-container="body" data-toggle="popover" data-placement="bottom" data-content="test">?</div> -->
                  <tr class="typeRam">
                    <td>ЛР-10 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>10 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>32x1.5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-20 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>20 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>30x30x1.5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-40 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>40 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>42x1.5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-60 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>60 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>42x2 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-80 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>80 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>48x2 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-100 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>100 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>48x3 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                  </tr>

                  <tr class="summ">
                    <td rel="0"></td>
                    <td rel="1"></td>
                    <td rel="2"></td>
                    <td rel="3"></td>
                    <td rel="5"></td>
                    <td rel="4"></td>
                  </tr>

                  <tr class="summChecked">
                    <td><input rel="0" type="checkbox" value="ЛР-10"></td>
                    <td><input rel="1" type="checkbox" value="ЛПР-20"></td>
                    <td><input rel="2" type="checkbox" value="ЛРП-40"></td>
                    <td><input rel="3" type="checkbox" value="ЛРП-60"></td>
                    <td><input rel="5" type="checkbox" value="ЛРП-80"></td>
                    <td><input rel="4" type="checkbox" value="ЛРП-100"></td>
                  </tr>

                  </table>
                </div>

                <div class="col-xs-12 col-md-6">
                  <table rel="homutlesa" data-id="4">
                    <tr>
                      <th colspan="6">Хомутовые леса <span class="priceLink" data-container="body" data-html="true" data-toggle="popover" data-placement="bottom" data-content='
                <div class="price-block">
                  <div class="title">Прайс Хомутовые леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_homutovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_homutovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>

                    <tr>
                      <td>ЛХ-30-Л <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>30 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>3 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>42 мм</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>150 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛХ-40 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>40 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>3 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48*1,5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛХ-40-УС <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>40 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>2 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48*3 мм</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>250 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛХ-60 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>60 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>2,5 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48*2 мм</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛХ-80-В <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>80 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>2,5 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48*3 мм</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛХ-80-УС <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>80 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>2 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>57*3 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>250 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    </tr>

                    <tr class="summ">
                      <td rel="0"></td>
                      <td rel="1"></td>
                      <td rel="2"></td>
                      <td rel="3"></td>
                      <td rel="4"></td>
                      <td rel="5"></td>
                    </tr>

                    <tr class="summChecked">
                      <td><input rel="0" type="checkbox" value="ЛХ-30Л"></td>
                      <td><input rel="1" type="checkbox" value="ЛХ-40"></td>
                      <td><input rel="2" type="checkbox" value="ЛХ-40-УС"></td>
                      <td><input rel="2" type="checkbox" value="ЛХ-60"></td>
                      <td><input rel="4" type="checkbox" value="ЛХ-80-В"></td>
                      <td><input rel="5" type="checkbox" value="ЛХ-80-УС"></td>
                    </tr>

                  </table>
                </div>

                <div class="col-xs-12 col-md-6">
                  <table rel="klinlesa" data-id="2">
                    <tr>
                      <th colspan="2">Клиновые леса <span class="priceLink" data-container="body" data-toggle="popover" data-placement="bottom" data-html="true" data-content='
                <div class="price-block">
                  <div class="title">Прайс Клиновые леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_klinovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_klinovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>

                    <tr>
                      <td>ЛСК-60 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>60 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>2 м.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                        <tr><td>Ширина яруса:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48*2 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛСК-100 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>100 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>2 м.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                        <tr><td>Ширина яруса:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48*3 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    </tr>

                    <tr class="summ">
                      <td rel="0"></td>
                      <td rel="1"></td>
                    </tr>

                    <tr class="summChecked">
                      <td><input rel="0" type="checkbox" value="ЛСК-60"></td>
                      <td><input rel="1" type="checkbox" value="ЛСК-100"></td>
                    </tr>

                  </table>
                </div>

                <div class="col-xs-12 col-md-6">
                  <table rel="ShtirLesa" data-id="3">
                    <tr>
                      <th colspan="2">Штыревые леса <span class="priceLink" data-container="body" data-toggle="popover" data-placement="bottom" data-html="true" data-content='
                <div class="price-block">
                  <div class="title">Прайс Штыревые леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_shtirevye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_shtirevye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>

                    <tr>
                      <td>ЛШ-50 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>50 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>1,5 / 2 / 2,5/ 3 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>48 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                      <td>ЛШ-100 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>100 м.</td></tr>
                        <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Шаг яруса вдоль стены:</td><td>1,5 / 2 / 2,5/ 3 м.</td></tr>
                        <tr><td>Несущая труба:</td><td>57*3 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    </tr>

                    <tr class="summ">
                      <td rel="0"></td>
                      <td rel="1"></td>
                    </tr>

                    <tr class="summChecked">
                      <td><input rel="0" type="checkbox" value="ЛШ-50"></td>
                      <td><input rel="1" type="checkbox" value="ЛШ-100"></td>
                    </tr>

                  </table>
                </div>

                <div class="col-xs-12">
                  <div class="row text-center">
                    <button data-buyandrent="buy" type="button" data-id="1" data-type="1" data-title="" class="btn btn-info getProductComparison">Оформить заказ</button>
                    <form method="POST" target="formwindow">
                        <input type="hidden" name='SumRamLesa'>
                        <input type="hidden" name='SumHomutLesa'>
                        <input type="hidden" name='SumKlintLesa'>
                        <input type="hidden" name='SumShtirLesa'>
                        <input type="hidden" name='buyAndrent'>
                        <button type="button" class="btn btn-success saveTable" data-type="byu">Сохранить</button>
                    </form>
                  </div>
                </div>

              </div>
              
            </div>

            <div class="tab-pane fade" id="rent">
              <div class="row rent text-center">

                <div class="col-xs-12 col-md-6">
                  <table data-id="1" rel="ramlesa">
                    <tr>
                      <th colspan="6">Рамные леса <span class="priceLink" data-html="true" data-container="body" data-toggle="popover" data-placement="bottom" data-content='
                <div class="price-block">
                  <div class="title">Прайс Рамные леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>
                  <tr>
                    <td>ЛР-10 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>10 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>32x1.5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-20 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>20 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>30x30x1.5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-40 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>40 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>42x1.5 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-60 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>60 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>42x2 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-80 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>80 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>48x2 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                    <td>ЛРП-100 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                      <table>
                        <tr><td>Макс. высота:</td><td>100 м.</td></tr>
                        <tr><td>Кратность по длине:</td><td>2 / 3 м.</td></tr>
                        <tr><td>Шаг яруса по высоте:</td><td>2 м.</td></tr>
                        <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                        <tr><td>Несущая труба:</td><td>48x3 мм.</td></tr>
                        <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                      </table>
                    ">?</span></td>
                  </tr>

                  <tr class="summ">
                    <td rel="0"></td>
                    <td rel="1"></td>
                    <td rel="2"></td>
                    <td rel="3"></td>
                    <td rel="5"></td>
                    <td rel="4"></td>
                  </tr>

                  <tr class="summChecked">
                    <td><input rel="0" type="checkbox" value="ЛР-10"></td>
                    <td><input rel="1" type="checkbox" value="ЛПР-20"></td>
                    <td><input rel="2" type="checkbox" value="ЛРП-40"></td>
                    <td><input rel="3" type="checkbox" value="ЛРП-60"></td>
                    <td><input rel="4" type="checkbox" value="ЛРП-80"></td>
                    <td><input rel="5" type="checkbox" value="ЛРП-100"></td>
                  </tr>

                  </table>
                </div>

                <div class="col-xs-12 col-md-6">
                  <table data-id="4" rel="homutlesa">
                    <tr>
                      <th colspan="6">Хомутовые леса <span class="priceLink" data-container="body" data-html="true" data-toggle="popover" data-placement="bottom" data-content='
                <div class="price-block">
                  <div class="title">Прайс Хомутовые леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_homutovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_homutovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>

                    <tr>
                      <td>ЛХ-30-Л <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>30 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>3 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>42 мм</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>150 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛХ-40 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>40 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>3 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48*1,5 мм.</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛХ-40-УС <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>40 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>2 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48*3 мм</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>250 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛХ-60 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>60 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>2,5 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48*2 мм</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛХ-80-В <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>80 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>2,5 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48*3 мм</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛХ-80-УС <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>80 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>2 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>57*3 мм.</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>250 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                    </tr>

                    <tr class="summ">
                      <td rel="0"></td>
                      <td rel="1"></td>
                      <td rel="2"></td>
                      <td rel="3"></td>
                      <td rel="4"></td>
                      <td rel="5"></td>
                    </tr>

                    <tr class="summChecked">
                      <td><input rel="0" type="checkbox" value="ЛХ-30Л"></td>
                      <td><input rel="1" type="checkbox" value="ЛХ-40"></td>
                      <td><input rel="2" type="checkbox" value="ЛХ-40-УС"></td>
                      <td><input rel="3" type="checkbox" value="ЛХ-60"></td>
                      <td><input rel="4" type="checkbox" value="ЛХ-80-В"></td>
                      <td><input rel="5" type="checkbox" value="ЛХ-80-УС"></td>
                    </tr>

                  </table>
                </div>

                <div class="col-xs-12 col-md-6">
                  <table data-id="2" rel="klinlesa">
                    <tr>
                      <th colspan="2">Клиновые леса <span class="priceLink" data-container="body" data-toggle="popover" data-placement="bottom" data-html="true" data-content='
                <div class="price-block">
                  <div class="title">Прайс Клиновые леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_klinovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_klinovye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>

                    <tr>
                      <td>ЛСК-60 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>60 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>2 м.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                          <tr><td>Ширина яруса:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48*2 мм.</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛСК-100 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>100 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>2 м.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                          <tr><td>Ширина яруса:</td><td>1 / 1,2 / 1,5 / 2 / 2,5 / 3 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48*3 мм.</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                    </tr>

                    <tr class="summ">
                      <td rel="0"></td>
                      <td rel="1"></td>
                    </tr>

                    <tr class="summChecked">
                      <td><input rel="0" type="checkbox" value="ЛСК-60"></td>
                      <td><input rel="1" type="checkbox" value="ЛСК-100"></td>
                    </tr>

                  </table>
                </div>

                <div class="col-xs-12 col-md-6">
                  <table data-id="3" rel="ShtirLesa">
                    <tr>
                      <th colspan="2">Штыревые леса <span class="priceLink" data-container="body" data-toggle="popover" data-placement="bottom" data-html="true" data-content='
                <div class="price-block">
                  <div class="title">Прайс Штыревые леса</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_shtirevye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" download href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_shtirevye_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Общие элементы лесов</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_obshie_elementy_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Хомуты</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_homuty_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>
                <div class="price-block">
                  <div class="title">Прайс Настилы</div>
                  <div class="price-links">
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-eye" aria-hidden="true"></i> Посмотреть</a>
                    <a target="_blank" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" class="btn btn-danger btn-xs"><i class="fa fa-download" aria-hidden="true"></i> Скачать</a>
                  </div>
                </div>'>(Прайс-листы)</span></th>
                    </tr>

                    <tr>
                      <td>ЛШ-50 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>50 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>1,5 / 2 / 2,5/ 3 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>48 мм.</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                        <td>ЛШ-100 <span data-html="true" data-container="body" data-toggle="popover" data-placement="top" data-content="
                        <table>
                          <tr><td>Макс. высота:</td><td>100 м.</td></tr>
                          <tr><td>Высота яруса:</td><td>регулируемая</td></tr>
                          <tr><td>Кол-во ярусов настилов: </td><td>не менее 3 шт.</td></tr>
                          <tr><td>Шаг яруса вдоль стены:</td><td>1,5 / 2 / 2,5/ 3 м.</td></tr>
                          <tr><td>Несущая труба:</td><td>57*3 мм.</td></tr>
                          <tr><td>Макс. нагрузка:</td><td>200 кг/м²</td></tr>
                        </table>
                      ">?</span></td>
                    </tr>

                    <tr class="summ">
                      <td rel="0"></td>
                      <td rel="1"></td>
                    </tr>

                    <tr class="summChecked">
                      <td><input rel="0" type="checkbox" value="ЛШ-50"></td>
                      <td><input rel="1" type="checkbox" value="ЛШ-100"></td>
                    </tr>

                  </table>
                </div>

                <div class="col-xs-12">
                  <div class="row text-center">
                    <button data-buyandrent="rent" type="button" data-id="1" data-type="1" data-title="" class="btn btn-info getProductComparison">Оформить заказ</button>
                    <form method="POST" target="formwindow">
                        <input type="hidden" name='SumRamLesa'>
                        <input type="hidden" name='SumHomutLesa'>
                        <input type="hidden" name='SumKlintLesa'>
                        <input type="hidden" name='SumShtirLesa'>
                        <input type="hidden" name='buyAndrent'>
                        <button type="button" class="btn btn-success saveTable" data-type="rent">Сохранить</button>
                    </form>
                  </div>
                </div>

              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
</div>



<div class="modal fade" id="FormTableComparison" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
        <h4 class="modal-title" id="myModalLabel">Оформление заявки <span class="formTableTitle"></span></h4>
      </div>
      <div class="modal-body">
        <form class="comparison">
          <span>Оставьте контактные данные и мы свяжемся с Вами!</span>
          <p><input type="text" name="name" placeholder="Введите ваше имя"></p>
          <p><input type="text" name="phone" placeholder="Введите ваш телефон"></p>
          <p><input type="text" name="email" placeholder="Введите ваш email"></p>
        </form>

        <div class="arendaBlock">
          <div class="countRent">
            <span>Количество дней аренды </span>
            <div class="countGroup" data-placement="top" data-content="Минимальное количество дней аренды: 30 дней">
                <div class="minus TabRentcount active"></div>
                <input class="form-control countItem" name="countElement" id="count1Elem2" value="30">
                <div class="plus TabRentcount active"></div>
            </div>
          </div>
        </div>

      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Закрыть</button>
        <button type="button" class="btn btn-primary submitComparison">Отправить</button>
      </div>
    </div>
  </div>
</div>


<div class="modal fade callMe" id="FormModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Оформление заявки</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <div class="model"></div>
        <div class="size"><input type="text" name="height" value="" readonly></div>
        <div class="countGroup">
          <span>Аренда,дней</span>
          <div class="recountTab minus"></div>
          <input type="text" value="30">
          <div class="recountTab plus"></div>
        </div>
      </div>
      <div class="modal-footer">
        <form class="orderform">
          <input type="text" name="formname" placeholder="Ваше имя">
          <input type="text" name="formphone" placeholder="Ваш телефон">
          <input type="text" name="formemail" placeholder="Ваш e-mail">
          <input type="hidden" name="subj" value="">
          <div class="submitform"><span>ОТПРАВИТЬ ЗАЯВКУ</span></div>
        </form>
      </div>
    </div>
  </div>
</div>


<!-- Modal -->
<div class="modal fade" id="siteMap" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
        <h4 class="modal-title" id="myModalLabel">Карта сайта</h4>
      </div>
      <div class="modal-body">
        <p><a href="ramnye-lesa.php" target="_blank">Рамные леса</a></p>
        <p><a href="klinovye-lesa.php" target="_blank">Клиновые леса</a></p>
        <p><a href="shtyrevye-lesa.php" target="_blank">Штыревые леса</a></p>
        <p><a href="homutovye-lesa.php" target="_blank">Хомутовые леса</a></p>
        <p><a href="vyshki-tura.php" target="_blank">Вышки тура</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/arenda.php" target="_blank">Аренда</a></p>
        <p><a href="contacts.php" target="_blank">Контакты</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/o_kompanii.php" target="_blank">О компании</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/articles.php" target="_blank">Статьи</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/fotogalereya.php" target="_blank">Фото-Видео галерея</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/ocinkovannye-stroitelnye-lesa.php" target="_blank">Оцинковка лесов и вышек</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/konstrukciya-stroitelnyh-lesov.php" target="_blank">Конструкция строительных лесов</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/kupit-zavodskie-lesa-vygodno.php" target="_blank">Почему купить заводские леса выгодно</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/metallicheskie-stroitelnye-lesa.php" target="_blank">Металлические строительные леса. История появления.</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/ramnye-ocinkovannye-lesa.php" target="_blank">Рамные оцинкованные леса</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/razlichiya-stroitelnyh-lesov.php" target="_blank">Различия строительных вышек-тура и лесов</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/shtyrevye-ocinkovannye-lesa.php" target="_blank">Штыревые оцинкованные леса</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/obrabotka-stroitelnyh-lesov.php" target="_blank">Антикоррозийная обработка строительных лесов</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/vyshki-tury-konstrukciya-preimushchestva.php" target="_blank">Вышки-тура: эксплуатационная сфера, преимущества</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/nestandartnye-klinovye-i-homutovye-lesa.php" target="_blank">Нестандартные клиновые и хомутовые леса</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/nastily-dlya-lesov.php" target="_blank">Настилы для строительных лесов</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/fasadnye-lesa.php" target="_blank">Фасадные леса</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/pravila-pri-rabote-na-stroitelnyh-lesah.php" target="_blank">Правила при работе на строительных лесах</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/nesushchie-lesa-pod-opalubku.php" target="_blank">Несущие леса под опалубку</a></p>
        <p><a href="https://xn----8sbemb9a1be.xn--p1ai/kronshtejn-k-lesam-i-fasadam-dlya-musorosbrosa.php" target="_blank">Пластиковый мусоропровод</a></p>
      </div>
    </div>
  </div>
</div>

<div class="modal fade errorModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
      <div class="modal-content">

        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>
          <h4 class="modal-title" id="mySmallModalLabel"></h4>
        </div>
        <div class="modal-body">
          
        </div>
      </div><!-- /.modal-content -->
    </div><!-- /.modal-dialog -->
</div>


</div>	


</template>

<style>

</style>
