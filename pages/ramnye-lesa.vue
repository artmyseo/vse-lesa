<template>
<div>
 
  <ramnielesacomponent />
	
	<div class="container select-type-lesov">
		<div class="row">
			
			     
			<div class="h2 text-center">Выберите тип лесов <span class="caret"></span></div>

			          <ul class="nav nav-pills nav-justified">
			            <li class="active"><a href="#lr10" tabindex="-1" data-toggle="tab" aria-expanded="false">ЛР-10</a></li>
			            <li class=""><a href="#lr20" tabindex="-1" data-toggle="tab" aria-expanded="true">ЛРП 2000-20</a></li>
			            <li class=""><a href="#lr40" tabindex="-1" data-toggle="tab" aria-expanded="true">ЛРП 2000-40</a></li>
			            <li class=""><a href="#lr60" tabindex="-1" data-toggle="tab" aria-expanded="true">ЛРП 2000-60</a></li>
			            <li class=""><a href="#lr80" tabindex="-1" data-toggle="tab" aria-expanded="true">ЛРП 2000-80</a></li>
			            <li class=""><a href="#lr100" tabindex="-1" data-toggle="tab" aria-expanded="true">ЛРП 2000-100</a></li>
			          </ul>
			        
			    

			    <div id="myTabContent" class="tab-content">
			          <div class="tab-pane fade active in" id="lr10">
			            <div class="table-lr">
			            	<div class="container">
			            		<div class="row">
			            			<div class="h2">Скомплектовать рамные леса ЛР-10</div>
			            		</div>
			            		<div class="row">
			            			
			            			<ul class="nav nav-pills nav-justified">
			            				<li class="active"><a href="#detailed-report" data-toggle="tab">Подробный расчет покупки</a></li>
			            				<li id="detailed-arendalist"><a href="#detailed-arenda" data-toggle="tab">Подробный расчет аренды</a></li>
			            				<li><a href="#characteristic" data-toggle="tab">Характеристика</a></li>
			            				<li><a href="#description" data-toggle="tab">Описание</a></li>
			            				<li><a href="#document" data-toggle="tab">Документы</a></li>
			            			</ul>
			            			<div class="tab-content">
			            				<div class="tab-pane fade in active" id="detailed-report">
			            						<div class="general-calculation">
			            							<table data-tab="1">
			            								<tr>
			            									<th rowspan="2">Элементы</th>
			            									<th rowspan="2">Количество</th>
			            									<th rowspan="2">Вес</th>
			            									<th colspan="2">Цена, руб. /шт.</th>
			            									<th colspan="2" class="tbarenda">Стоимость аренды</th>
			            								</tr>
			            								<tr>
			            									<th>Розница</th>
			            									<th>ОПТ</th>
			            									<th class="tbarenda">Первые 30 дней</th>
			            									<th class="tbarenda">+ 1 след.день</th>
			            								</tr>
			            								<tr rel="Рама с лестницей 32*1,5 мм.">
			<td data-test="Прайс/Рамные леса">Рама с лестницей 32*1,5 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">7.61</td>  
			<td rel="priceR">971.00</td>
			<td rel="PriceD">825.35</td>
			<td rel="ArendaAR">194.20</td>
			<td rel="ArendaP">2.91</td>				
			</tr><tr rel="Рама без лестницы 32*1,5 мм.">
			<td data-test="Прайс/Рамные леса">Рама без лестницы 32*1,5 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.69</td>  
			<td rel="priceR">796.00</td>
			<td rel="PriceD">676.60</td>
			<td rel="ArendaAR">159.20</td>
			<td rel="ArendaP">2.39</td>				
			</tr><tr rel="Диагональ 3 м.">
			<td data-test="Прайс/Рамные леса">Диагональ 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">3.69</td>  
			<td rel="priceR">567.00</td>
			<td rel="PriceD">481.95</td>
			<td rel="ArendaAR">113.40</td>
			<td rel="ArendaP">1.70</td>				
			</tr><tr rel="Горизонталь 3 м.">
			<td data-test="Прайс/Рамные леса">Горизонталь 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.62</td>  
			<td rel="priceR">294.00</td>
			<td rel="PriceD">249.90</td>
			<td rel="ArendaAR">58.80</td>
			<td rel="ArendaP">0.88</td>				
			</tr><tr rel="Ригель 3 м.">
			<td data-test="Прайс/Рамные леса">Ригель 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.81</td>  
			<td rel="priceR">841.00</td>
			<td rel="PriceD">714.85</td>
			<td rel="ArendaAR">168.20</td>
			<td rel="ArendaP">2.52</td>				
			</tr><tr rel="Кронштейн 32 мм.">
			<td data-test="Прайс/Общие элементы лесов">Кронштейн 32 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.68</td>  
			<td rel="priceR">207.00</td>
			<td rel="PriceD">175.95</td>
			<td rel="ArendaAR">41.40</td>
			<td rel="ArendaP">0.62</td>				
			</tr><tr rel="Настил деревянный 0,75*0,95 м. (25 мм.)">
			<td data-test="Прайс/Настилы">Настил деревянный 0,75*0,95 м. (25 мм.)</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">13.00</td>  
			<td rel="priceR">353.00</td>
			<td rel="PriceD">300.05</td>
			<td rel="ArendaAR">70.60</td>
			<td rel="ArendaP">1.06</td>				
			</tr><tr rel="Связь стартовая ЛР-10">
			<td data-test="Прайс/Рамные леса">Связь стартовая ЛР-10</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.20</td>  
			<td rel="priceR">252.00</td>
			<td rel="PriceD">214.20</td>
			<td rel="ArendaAR">50.40</td>
			<td rel="ArendaP">0.76</td>				
			</tr>			            								<tr class="demo collapse" rel="Горизонталь 2 м.">
      <td data-test="Прайс/Рамные леса">Горизонталь 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.50</td>  
      <td rel="priceR">245.00</td>
      <td rel="PriceD">208.25</td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td data-test="Прайс/Рамные леса">Диагональ 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">513.00</td>
      <td rel="PriceD">436.05</td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 30*30 мм.">
      <td data-test="Прайс/Общие элементы лесов">Домкрат 0,35 м. 30*30 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.00</td>  
      <td rel="priceR">694.00</td>
      <td rel="PriceD">589.90</td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.40</td>  
      <td rel="priceR">402.00</td>
      <td rel="PriceD">341.70</td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td data-test="Прайс/Общие элементы лесов">Молниеприемник с заземлением 3,6 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">2 086.00</td>
      <td rel="PriceD">1 773.10</td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 2,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">2 235.00</td>
      <td rel="PriceD">1 899.75</td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 3,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">2 701.00</td>
      <td rel="PriceD">2 295.85</td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 2*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.02</td>  
      <td rel="priceR">2 547.00</td>
      <td rel="PriceD">2 164.95</td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 3*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">20.09</td>  
      <td rel="priceR">3 459.00</td>
      <td rel="PriceD">2 940.15</td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">660.00</td>
      <td rel="PriceD">561.00</td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,2х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.00</td>  
      <td rel="priceR">823.00</td>
      <td rel="PriceD">699.55</td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.50</td>  
      <td rel="priceR">987.00</td>
      <td rel="PriceD">838.95</td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.00</td>  
      <td rel="priceR">1 316.00</td>
      <td rel="PriceD">1 118.60</td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 644.00</td>
      <td rel="PriceD">1 397.40</td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 3,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 806.00</td>
      <td rel="PriceD">1 535.10</td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.12</td>  
      <td rel="priceR">514.00</td>
      <td rel="PriceD">436.90</td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.42</td>  
      <td rel="priceR">607.00</td>
      <td rel="PriceD">515.95</td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.54</td>  
      <td rel="priceR">1 079.00</td>
      <td rel="PriceD">917.15</td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.89</td>  
      <td rel="priceR">1 185.00</td>
      <td rel="PriceD">1 007.25</td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 300 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.39</td>  
      <td rel="priceR">214.00</td>
      <td rel="PriceD">181.90</td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 400 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.52</td>  
      <td rel="priceR">313.00</td>
      <td rel="PriceD">266.05</td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 500 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.66</td>  
      <td rel="priceR">443.00</td>
      <td rel="PriceD">376.55</td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (32*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полурама ограждения 1 м. (32*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.20</td>  
      <td rel="priceR">498.00</td>
      <td rel="PriceD">423.30</td>
      <td rel="ArendaAR">99.60</td>
      <td rel="ArendaP">1.49</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (32*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полустойка 1 м. (32*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.20</td>  
      <td rel="priceR">191.00</td>
      <td rel="PriceD">162.35</td>
      <td rel="ArendaAR">38.20</td>
      <td rel="ArendaP">0.57</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 32*1,5 мм.">
      <td data-test="Прайс/Рамные леса">Рама торцевая 32*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.17</td>  
      <td rel="priceR">971.00</td>
      <td rel="PriceD">825.35</td>
      <td rel="ArendaAR">194.20</td>
      <td rel="ArendaP">2.91</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.25</td>  
      <td rel="priceR">719.00</td>
      <td rel="PriceD">611.15</td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 446.00</td>
      <td rel="PriceD">1 229.10</td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">1 823.00</td>
      <td rel="PriceD">1 549.55</td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 2 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.24</td>  
      <td rel="priceR">548.00</td>
      <td rel="PriceD">465.80</td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 3 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.94</td>  
      <td rel="priceR">925.00</td>
      <td rel="PriceD">786.25</td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 4 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.82</td>  
      <td rel="priceR">1 546.00</td>
      <td rel="PriceD">1 314.10</td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 6 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">12.07</td>  
      <td rel="priceR">1 965.00</td>
      <td rel="PriceD">1 670.25</td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr>			            								<tr>
			            									<td width="34%">Итого:</td>
			            									<td width="12%"></td>
			            									<td width="10%" rel="vessItog"></td>
			            									<td width="11%" rel="totalSumR"></td>
			            									<td width="11%" rel="totalOpt"></td>
			            									<td width="11%" rel="ArendaD"></td>
			            									<td width="11%" rel="ArendaPI"></td>
			            								</tr>
			            							</table>
			            						</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="buy" type="button" data-target="#FormTable" data-id="1" data-type="1" data-title="ЛР-10" class="btn btn-info getProduct">Купить рамные леса</button>
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="1" data-type="1" data-title="ЛР-10" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Доп. элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade in" id="detailed-arenda">
			            					<div class="general-calculationRent">
			            						<table data-tab="2">
			            							<tr>
			            								<th rowspan="2">Элементы</th>
			            								<th rowspan="2">Количество</th>
			            								<th colspan="2">Стоимость аренды</th>
			            							</tr>
			            							<tr>
			            								<th>Первые 30 дней</th>
			            								<th>+ 1 след.день</th>
													</tr>			
			            							<tr rel="Рама с лестницей 32*1,5 мм.">
      <td>Рама с лестницей 32*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">194.20</td>
      <td rel="ArendaP">2.91</td>        
      </tr><tr rel="Рама без лестницы 32*1,5 мм.">
      <td>Рама без лестницы 32*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">159.20</td>
      <td rel="ArendaP">2.39</td>        
      </tr><tr rel="Диагональ 3 м.">
      <td>Диагональ 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">113.40</td>
      <td rel="ArendaP">1.70</td>        
      </tr><tr rel="Горизонталь 3 м.">
      <td>Горизонталь 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">58.80</td>
      <td rel="ArendaP">0.88</td>        
      </tr><tr rel="Ригель 3 м.">
      <td>Ригель 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">168.20</td>
      <td rel="ArendaP">2.52</td>        
      </tr><tr rel="Кронштейн 32 мм.">
      <td>Кронштейн 32 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">41.40</td>
      <td rel="ArendaP">0.62</td>        
      </tr><tr rel="Настил деревянный 0,75*0,95 м. (25 мм.)">
      <td>Настил деревянный 0,75*0,95 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">70.60</td>
      <td rel="ArendaP">1.06</td>        
      </tr><tr rel="Связь стартовая ЛР-10">
      <td>Связь стартовая ЛР-10</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">50.40</td>
      <td rel="ArendaP">0.76</td>        
      </tr>			            							<tr class="demo collapse" rel="Горизонталь 2 м.">
      <td>Горизонталь 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 30*30 мм.">
      <td>Домкрат 0,35 м. 30*30 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td>Диагональ 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td>Ригель 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td>Ригель усиленный (ферма) 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td>Ригель усиленный (ферма) 3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 32*1,5 мм.">
      <td>Рама торцевая 32*1,5 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">194.20</td>
      <td rel="ArendaP">2.91</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (32*1,5 мм.)">
      <td>Полурама ограждения 1 м. (32*1,5 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">99.60</td>
      <td rel="ArendaP">1.49</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (32*1,5 мм.)">
      <td>Полустойка 1 м. (32*1,5 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">38.20</td>
      <td rel="ArendaP">0.57</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td>Ограждение 1,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td>Ограждение 1,2х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td>Ограждение 1,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td>Ограждение 2,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td>Ограждение 2,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td>Ограждение 3,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td>Настил комбинированный 2,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td>Настил комбинированный 3,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td>Настил металлический 2*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td>Настил металлический 3*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td>Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td>Планка под кронштейн 300 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td>Планка под кронштейн 400 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td>Планка под кронштейн 500 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td>Стабилизирующая опора 2 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td>Стабилизирующая опора 3 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td>Стабилизирующая опора 4 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem35 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td>Стабилизирующая опора 6 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem36 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr>			            							<tr>
			            								<td>Итого:</td>
			            								<td></td>
			            								<td rel="ArendaD"></td>
			            								<td rel="ArendaPI"></td>
			            							</tr>
			            						</table>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="2" data-title="ЛР-10" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Дополнительные элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade characteristic" id="characteristic">
			            					<table>
			            						<tr>
			            							<th>Марка лесов</th>
			            							<th>ЛР-10</th>
			            						</tr>
			            						<tr>
			            							<td>Максимальная высота установки</td>
			            							<td>10 м</td>
			            						</tr>
			            						<tr>
			            							<td>Высота яруса</td>
			            							<td>2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Шаг яруса вдоль стены</td>
			            							<td>3 м / 2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Ширина яруса</td>
			            							<td>0,7 м</td>
			            						</tr>
			            						<tr>
			            							<td>Количество ярусов настилов, не менее</td>
			            							<td>3 шт. (1 рабочий + 2 страховочных)</td>
			            						</tr>
			            						<tr>
			            							<td>Нагрузка <br> для отделочных работ <br> для каменной или кирпичной кладки</td>
			            							<td> <br>до 200ПА(кг/м<sup>2</sup>) <br> Не предусмотрено</td>
			            						</tr>
			            						<tr>
			            							<td>Рама изготовлена из трубы</td>
			            							<td>32*1,5 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Размер рамы</td>
			            							<td>2*0,7 м</td>
			            						</tr>
			            						<tr>
			            							<td>Горизонталь/Диагональ изготовлена из трубы</td>
			            							<td>25 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Длина горизонтали/Диагонали <br> на длину ячейки 2 м <br> на длину ячейки 3 м</td>
			            							<td><br>2054 мм/2395 мм <br> 3054 мм /3295 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Ригель изготовлен из трубы</td>
			            							<td>60*30*1,5 мм</td>
			            						</tr>
			            					</table>
			            				</div>
			            				<div class="tab-pane fade" id="description">
			            					<div class="col-sm-6 col-xs-12">
			            						<div class="h4">Элементы</div>
			            						<ol class="listElemsTab">
			            							<li><span data-id="1">Рама с лестницей</span></li>
			            							<li><span data-id="2">Рама без лестницы</span></li>
			            							<li><span data-id="3">Горизонталь</span></li>
			            							<li><span data-id="4">Диагональ</span></li>
			            							<li><span data-id="5">Ригель</span></li>
			            							<li><span data-id="6">Настил деревянный</span></li>
			            							<li><span data-id="7">Подпятник</span></li>
			            							<li><span data-id="8">Полурама</span></li>
			            						</ol>
			            						<div class="h4">Дополнительные элементы к рамным лесам, не указанные на изображении:</div>
			            						<ul>
			            							<li>Анкерный кронштейн</li>
			            							<li>Выносная консоль</li>
			            							<li>Домкрат</li>
			            							<li>Кронштейн</li>
			            							<li>Настил металлический</li>
			            							<li>Отбортовочный деревянный элемент</li>
			            							<li>Отбортовочный металлический элемент</li>
			            							<li>Планка под кронштейн</li>
			            							<li>Полустойка</li>
			            							<li>Рама торцевая</li>
			            							<li>Ригель усиленный</li>
			            							<li>Стабилизирующая опора</li>
			            							<li>Фасадная сетка</li>
			            							<li>Хомуты кованые оцинкованные</li>
			            							<li>Хомутовая стяжка</li>
			            						</ul>
			            					</div>
			            					<div class="col-sm-6 col-xs-12">
			            						<div class="imageElemsTab">
			            							<img src="/img/tableram.png" alt="">
			            							<div class="pointsTab">
			            								<div data-id="1" class="point active">1</div>
			            								<div data-id="2" class="point">2</div>
			            								<div data-id="3" class="point">3</div>
			            								<div data-id="4" class="point">4</div>
			            								<div data-id="5" class="point">5</div>
			            								<div data-id="6" class="point">6</div>
			            								<div data-id="7" class="point">7</div>
			            								<div data-id="8" class="point">8</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="col-sm-12">
			            						<div class="h4">
			            							<p>Среди всех аналогов рамные строительные леса заслуженно считаются самыми выгодными в финансовом плане, а также одними из самых простых сборно-разборных подмостей в плане монтажа. Представленная модель, абсолютно удобная и безопасная для интенсивного эксплуатирования, собирается на высоту до 10 м. В ее основе лежат маршевые рамы – несущие стальные элементы, устанавливающиеся в вертикальном положении для достижения нужной высоты подмостей. Они представляют собой сварные прямоугольные каркасы, внутри которых могут находиться прочные перекладины (для образования лестницы, и, соответственно, перемещения строителей между ярусами).</p>
			            							<p>Конструкция всех моделей фасадных средств подмащивания включает в себя следующие элементы:</p>
			            							
			            							<ol>
			            								<li>Башмаки – стальные изделия из опорной пластины и приваренной посередине вертикальной трубки для стыковки с несущими рамами. Их назначение состоит в распределении нагрузки под подмостями. Также встречается название «подпятники».</li>
			            								<li>Горизонтальные связи – трубчатые детали, связывающие противоположно установленные рамы, и факультативно выполняющие роль ограждений.</li>
			            								<li>Диагонали – Х-образные элементы из двух скрепленных посередине труб, которые соединяют две рамы и защищают каркас лесов от кручения. Именно благодаря диагоналям подмости бывают жесткими и, соответственно, безопасными для интенсивного эксплуатирования. При этом данные элементы, как и горизонтали, дополнительно выступают в роли ограждений.</li>
			            								<li>Ригели – металлические элементы, укладывающиеся между двумя противоположными рамами для последующей установки на них строительных настилов.</li>
			            								<li>Усиленный ригель – ригель, предназначенный для работ с повышенным уровнем нагрузки. Так, если обычно допустимая нагрузка не превышает 200 кг/м2, то с усиленными ригелями ее можно увеличить до 500 кг/м2. Также встречается название «ферма».</li>
			            								<li>Настилы – элементы, образующие рабочую поверхность. Без них строители не смогли бы выполнять свои рабочие функции, в связи с чем к данным деталям предъявляются достаточно жесткие требования. Могут производиться из древесины (более дешевый и быстрый в исполнении, но вполне эффективный вариант) или металла (обладают перфорированной поверхностью, максимальной долговечностью и безопасностью).</li>
			            								<li>Кронштейны – стальные изделия, необходимые для крепления каркаса рамочных средств подмащивания к стене во избежание опрокидывания подмостей.</li>
			            							</ol>
			            
			            							<p>Следовательно, можно смело утверждать, что фасадные леса заслуженно считаются современным оборудованием для безопасного и результативного осуществления широкого перечня работ (например, кладки, отделки, реставрации, монтажа и т.д.). К тому же они характеризуются выгодной ценой, что однозначно говорит в их пользу. Профессионалы в разных сферах предпочитают заказывать именно этот вид вспомогательных подмостей, причем, популярностью пользуется не только приобретение металлоконструкций, но и их аренда (если позволяет срок проведения строительных работ).</p>
			            							<p>Наша компания предлагает рамные леса серии ЛР, которые производятся в полном соответствии с ТУ 5225-004-18171908-2017 «Леса строительные рамные. Технические условия».</p>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade text-center" id="document">
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на рамные леса</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на элементы лесов</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" target="_blank">Прайс на настилы</a></div>
			            					<div class="col-lg-6"><a class="linkPasport" href="documentViewer_pk_mdnprom/pasport/ramnye-lesa.pdf" target="_blank">Скачать паспорт</a></div>
			            					<div class="col-lg-6"><a class="linkCertificate" href="documentViewer_pk_mdnprom/pasport/sertifikat.jpg " target="_blank">Сертификат</a></div>
			            				</div>
			            			</div>
			            		</div>
			            	</div>
			            </div>
			          </div>
			          <div class="tab-pane fade" id="lr20">
			            <div class="table-lr">
			            	<div class="container">
			            		<div class="row">
			            			<div class="h2">Скомплектовать рамные леса ЛРП 2000-20</div>
			            		</div>
			            		<div class="row">
			            			<!-- Nav tabs -->
			            			<ul class="nav nav-pills nav-justified">
			            				<li class="active"><a href="#detailed-report_T3" data-toggle="tab">Подробный расчет покупки</a></li>
			            				<li id="detailed-arendalist"><a href="#detailed-arenda_T3" data-toggle="tab">Подробный расчет аренды</a></li>
			            				<li><a href="#characteristic_T3" data-toggle="tab">Характеристика</a></li>
			            				<li><a href="#description_T3" data-toggle="tab">Описание</a></li>
			            				<li><a href="#document_T3" data-toggle="tab">Документы</a></li>
			            			</ul>
			            			<!-- Tab panes -->
			            			<div class="tab-content">
			            				<div class="tab-pane fade in active" id="detailed-report_T3">
			            					<div class="table-container">
			            						<div class="general-calculation">
			            							<table data-tab="3">
			            								<tr>
			            									<th rowspan="2">Элементы</th>
			            									<th rowspan="2">Количество</th>
			            									<th rowspan="2">Вес</th>
			            									<th colspan="2">Цена, руб. /шт.</th>
			            									<th colspan="2" class="tbarenda">Стоимость аренды</th>
			            								</tr>
			            								<tr>
			            									<th>Розница</th>
			            									<th>ОПТ</th>
			            									<th class="tbarenda">Первые 30 дней</th>
			            									<th class="tbarenda">+ 1 след.день</th>
			            								</tr>
			            								<tr rel="Рама с лестницей 30*30*1,5 мм.">
			<td data-test="Прайс/Рамные леса">Рама с лестницей 30*30*1,5 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">9.99</td>  
			<td rel="priceR">1 162.00</td>
			<td rel="PriceD">987.70</td>
			<td rel="ArendaAR">232.40</td>
			<td rel="ArendaP">3.49</td>				
			</tr><tr rel="Рама без лестницы 30*30*1,5 мм.">
			<td data-test="Прайс/Рамные леса">Рама без лестницы 30*30*1,5 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">7.91</td>  
			<td rel="priceR">1 024.00</td>
			<td rel="PriceD">870.40</td>
			<td rel="ArendaAR">204.80</td>
			<td rel="ArendaP">3.07</td>				
			</tr><tr rel="Диагональ 3 м.">
			<td data-test="Прайс/Рамные леса">Диагональ 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">3.69</td>  
			<td rel="priceR">567.00</td>
			<td rel="PriceD">481.95</td>
			<td rel="ArendaAR">113.40</td>
			<td rel="ArendaP">1.70</td>				
			</tr><tr rel="Горизонталь 3 м.">
			<td data-test="Прайс/Рамные леса">Горизонталь 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.62</td>  
			<td rel="priceR">294.00</td>
			<td rel="PriceD">249.90</td>
			<td rel="ArendaAR">58.80</td>
			<td rel="ArendaP">0.88</td>				
			</tr><tr rel="Ригель 3 м.">
			<td data-test="Прайс/Рамные леса">Ригель 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.81</td>  
			<td rel="priceR">841.00</td>
			<td rel="PriceD">714.85</td>
			<td rel="ArendaAR">168.20</td>
			<td rel="ArendaP">2.52</td>				
			</tr><tr rel="Кронштейн 30*30 мм.">
			<td data-test="Прайс/Общие элементы лесов">Кронштейн 30*30 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.68</td>  
			<td rel="priceR">207.00</td>
			<td rel="PriceD">175.95</td>
			<td rel="ArendaAR">41.40</td>
			<td rel="ArendaP">0.62</td>				
			</tr><tr rel="Подпятник 30*30 мм.">
			<td data-test="Прайс/Общие элементы лесов">Подпятник 30*30 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.45</td>  
			<td rel="priceR">98.00</td>
			<td rel="PriceD">83.30</td>
			<td rel="ArendaAR">19.60</td>
			<td rel="ArendaP">0.29</td>				
			</tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
			<td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (25 мм.)</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">18.00</td>  
			<td rel="priceR">342.00</td>
			<td rel="PriceD">290.70</td>
			<td rel="ArendaAR">68.40</td>
			<td rel="ArendaP">1.03</td>				
			</tr>			            								<tr class="demo collapse" rel="Горизонталь 2 м.">
      <td data-test="Прайс/Рамные леса">Горизонталь 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.50</td>  
      <td rel="priceR">245.00</td>
      <td rel="PriceD">208.25</td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td data-test="Прайс/Рамные леса">Диагональ 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">513.00</td>
      <td rel="PriceD">436.05</td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 30*30 мм.">
      <td data-test="Прайс/Общие элементы лесов">Домкрат 0,35 м. 30*30 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.00</td>  
      <td rel="priceR">694.00</td>
      <td rel="PriceD">589.90</td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.40</td>  
      <td rel="priceR">402.00</td>
      <td rel="PriceD">341.70</td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td data-test="Прайс/Общие элементы лесов">Молниеприемник с заземлением 3,6 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">2 086.00</td>
      <td rel="PriceD">1 773.10</td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">9.00</td>  
      <td rel="priceR">277.00</td>
      <td rel="PriceD">235.45</td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">36.00</td>  
      <td rel="priceR">756.00</td>
      <td rel="PriceD">642.60</td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 2,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">2 235.00</td>
      <td rel="PriceD">1 899.75</td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 3,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">2 701.00</td>
      <td rel="PriceD">2 295.85</td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 2*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.02</td>  
      <td rel="priceR">2 547.00</td>
      <td rel="PriceD">2 164.95</td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 3*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">20.09</td>  
      <td rel="priceR">3 459.00</td>
      <td rel="PriceD">2 940.15</td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">660.00</td>
      <td rel="PriceD">561.00</td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,2х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.00</td>  
      <td rel="priceR">823.00</td>
      <td rel="PriceD">699.55</td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.50</td>  
      <td rel="priceR">987.00</td>
      <td rel="PriceD">838.95</td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.00</td>  
      <td rel="priceR">1 316.00</td>
      <td rel="PriceD">1 118.60</td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 644.00</td>
      <td rel="PriceD">1 397.40</td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 3,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 806.00</td>
      <td rel="PriceD">1 535.10</td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.82</td>  
      <td rel="priceR">407.00</td>
      <td rel="PriceD">345.95</td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.12</td>  
      <td rel="priceR">514.00</td>
      <td rel="PriceD">436.90</td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.42</td>  
      <td rel="priceR">607.00</td>
      <td rel="PriceD">515.95</td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.19</td>  
      <td rel="priceR">663.00</td>
      <td rel="PriceD">563.55</td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.54</td>  
      <td rel="priceR">1 079.00</td>
      <td rel="PriceD">917.15</td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.89</td>  
      <td rel="priceR">1 185.00</td>
      <td rel="PriceD">1 007.25</td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 300 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.39</td>  
      <td rel="priceR">214.00</td>
      <td rel="PriceD">181.90</td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 400 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.52</td>  
      <td rel="priceR">313.00</td>
      <td rel="PriceD">266.05</td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 500 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.66</td>  
      <td rel="priceR">443.00</td>
      <td rel="PriceD">376.55</td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (30*30*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полурама ограждения 1 м. (30*30*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">705.00</td>
      <td rel="PriceD">599.25</td>
      <td rel="ArendaAR">141.00</td>
      <td rel="ArendaP">2.12</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (30*30*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полустойка 1 м. (30*30*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.75</td>  
      <td rel="priceR">285.00</td>
      <td rel="PriceD">242.25</td>
      <td rel="ArendaAR">57.00</td>
      <td rel="ArendaP">0.86</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 30*30*1,5 мм.">
      <td data-test="Прайс/Рамные леса">Рама торцевая 30*30*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.61</td>  
      <td rel="priceR">1 108.00</td>
      <td rel="PriceD">941.80</td>
      <td rel="ArendaAR">221.60</td>
      <td rel="ArendaP">3.32</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.25</td>  
      <td rel="priceR">719.00</td>
      <td rel="PriceD">611.15</td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 446.00</td>
      <td rel="PriceD">1 229.10</td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">1 823.00</td>
      <td rel="PriceD">1 549.55</td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 2 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.24</td>  
      <td rel="priceR">548.00</td>
      <td rel="PriceD">465.80</td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 3 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.94</td>  
      <td rel="priceR">925.00</td>
      <td rel="PriceD">786.25</td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 4 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.82</td>  
      <td rel="priceR">1 546.00</td>
      <td rel="PriceD">1 314.10</td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 6 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem35 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">12.07</td>  
      <td rel="priceR">1 965.00</td>
      <td rel="PriceD">1 670.25</td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr>			            								<tr>
			            									<td width="34%">Итого:</td>
			            									<td width="12%"></td>
			            									<td width="10%" rel="vessItog"></td>
			            									<td width="11%" rel="totalSumR"></td>
			            									<td width="11%" rel="totalOpt"></td>
			            									<td width="11%" rel="ArendaD"></td>
			            									<td width="11%" rel="ArendaPI"></td>
			            								</tr>
			            							</table>
			            						</div>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="buy" data-target="#FormTable" type="button" data-id="3" data-type="2" data-title="ЛРП 2000-20" class="btn btn-info getProduct">Купить рамные леса</button>
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="3" data-type="2" data-title="ЛРП 2000-20" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Доп. элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade in" id="detailed-arenda_T3">
			            					<div class="general-calculationRent">
			            						<table data-tab="4">
			            							<tr>
			            								<th rowspan="2">Элементы</th>
			            								<th rowspan="2">Количество</th>
			            								<th colspan="2">Стоимость аренды</th>
			            							</tr>
			            							<tr>
			            								<th>Первые 30 дней</th>
			            								<th>+ 1 след.день</th>
			            							</tr>
			            							<tr rel="Рама с лестницей 30*30*1,5 мм.">
      <td>Рама с лестницей 30*30*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">232.40</td>
      <td rel="ArendaP">3.49</td>        
      </tr><tr rel="Рама без лестницы 30*30*1,5 мм.">
      <td>Рама без лестницы 30*30*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">204.80</td>
      <td rel="ArendaP">3.07</td>        
      </tr><tr rel="Горизонталь 3 м.">
      <td>Горизонталь 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">58.80</td>
      <td rel="ArendaP">0.88</td>        
      </tr><tr rel="Диагональ 3 м.">
      <td>Диагональ 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">113.40</td>
      <td rel="ArendaP">1.70</td>        
      </tr><tr rel="Ригель 3 м.">
      <td>Ригель 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">168.20</td>
      <td rel="ArendaP">2.52</td>        
      </tr><tr rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr rel="Подпятник 30*30 мм.">
      <td>Подпятник 30*30 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">19.60</td>
      <td rel="ArendaP">0.29</td>        
      </tr><tr rel="Полурама ограждения 1 м. (30*30*1,5 мм.)">
      <td>Полурама ограждения 1 м. (30*30*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">141.00</td>
      <td rel="ArendaP">2.12</td>        
      </tr>			            							<tr class="demo collapse" rel="Домкрат 0,35 м. 30*30 мм.">
      <td>Домкрат 0,35 м. 30*30 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td>Диагональ 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td>Горизонталь 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 30*30*1,5 мм.">
      <td>Рама торцевая 30*30*1,5 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">221.60</td>
      <td rel="ArendaP">3.32</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td>Ригель 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td>Ригель усиленный (ферма) 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td>Ригель усиленный (ферма) 3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td>Стабилизирующая опора 2 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td>Стабилизирующая опора 3 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td>Стабилизирующая опора 4 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td>Стабилизирующая опора 6 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (30*30*1,5 мм.)">
      <td>Полустойка 1 м. (30*30*1,5 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">57.00</td>
      <td rel="ArendaP">0.86</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td>Ограждение 1,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td>Ограждение 1,2х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td>Ограждение 1,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td>Ограждение 2,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td>Ограждение 2,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td>Ограждение 3,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Кронштейн 30*30 мм.">
      <td>Кронштейн 30*30 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">41.40</td>
      <td rel="ArendaP">0.62</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td>Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td>Настил комбинированный 2,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td>Настил комбинированный 3,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (25 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">68.40</td>
      <td rel="ArendaP">1.03</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td>Настил металлический 2*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr>	
			            							<tr>
			            								<td>Итого:</td>
			            								<td></td>
			            								<td rel="ArendaD"></td>
			            								<td rel="ArendaPI"></td>
			            							</tr>
			            						</table>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="4" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Дополнительные элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade characteristic" id="characteristic_T3">
			            					<table>
			            						<tr>
			            							<th>Марка лесов</th>
			            							<th>ЛРП-20</th>
			            						</tr>
			            						<tr>
			            							<td>Максимальная высота установки</td>
			            							<td>20 м</td>
			            						</tr>
			            						<tr>
			            							<td>Высота яруса</td>
			            							<td>2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Шаг яруса вдоль стены</td>
			            							<td>3 м / 2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Ширина яруса</td>
			            							<td>1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Количество ярусов настилов, не менее</td>
			            							<td>3 шт. (1 рабочий + 2 страховочных)</td>
			            						</tr>
			            						<tr>
			            							<td>Нагрузка <br> для отделочных работ <br> для каменной или кирпичной кладки</td>
			            							<td> <br>до 200ПА(кг/м<sup>2</sup>) <br> Не предусмотрено</td>
			            						</tr>
			            						<tr>
			            							<td>Рама изготовлена из трубы</td>
			            							<td>30*30*1,5 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Размер рамы</td>
			            							<td>2*1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Горизонталь/Диагональ изготовлена из трубы</td>
			            							<td>25 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Длина горизонтали/Диагонали <br> на длину ячейки 2 м <br> на длину ячейки 3 м</td>
			            							<td><br>2054 мм/2395 мм <br> 3054 мм /3295 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Ригель изготовлен из трубы</td>
			            							<td>60*30*1,5 мм</td>
			            						</tr>
			            					</table>
			            				</div>
			            				<div class="tab-pane fade" id="description_T3">
			            					<div class="col-sm-6">
			            						<div class="h4">Элементы</div>
			            						<ol class="listElemsTab">
			            							<li><span data-id="1">Рама с лестницей</span></li>
			            							<li><span data-id="2">Рама без лестницы</span></li>
			            							<li><span data-id="3">Горизонталь</span></li>
			            							<li><span data-id="4">Диагональ</span></li>
			            							<li><span data-id="5">Ригель</span></li>
			            							<li><span data-id="6">Настил деревянный</span></li>
			            							<li><span data-id="7">Подпятник</span></li>
			            							<li><span data-id="8">Полурама</span></li>
			            						</ol>
			            						<div class="h4">Дополнительные элементы к рамным лесам, не указанные на изображении:</div>
			            						<ul>
			            							<li>Анкерный кронштейн</li>
			            							<li>Выносная консоль</li>
			            							<li>Домкрат</li>
			            							<li>Кронштейн</li>
			            							<li>Настил металлический</li>
			            							<li>Отбортовочный деревянный элемент</li>
			            							<li>Отбортовочный металлический элемент</li>
			            							<li>Планка под кронштейн</li>
			            							<li>Полустойка</li>
			            							<li>Рама торцевая</li>
			            							<li>Ригель усиленный</li>
			            							<li>Стабилизирующая опора</li>
			            							<li>Фасадная сетка</li>
			            							<li>Хомуты кованые оцинкованные</li>
			            							<li>Хомутовая стяжка</li>
			            						</ul>
			            					</div>
			            					<div class="col-sm-6">
			            						<div class="imageElemsTab">
			            							<img src="/img/tableram.png" alt="">	
			            							<div class="pointsTab">
			            								<div data-id="1" class="point active">1</div>
			            								<div data-id="2" class="point">2</div>
			            								<div data-id="3" class="point">3</div>
			            								<div data-id="4" class="point">4</div>
			            								<div data-id="5" class="point">5</div>
			            								<div data-id="6" class="point">6</div>
			            								<div data-id="7" class="point">7</div>
			            								<div data-id="8" class="point">8</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="col-sm-12">
			            <div class="h4">
			            	<p>Среди всех аналогов рамные строительные леса заслуженно считаются самыми выгодными в финансовом плане, а также одними из самых простых сборно-разборных подмостей в плане монтажа. Представленная модель, абсолютно удобная и безопасная для интенсивного эксплуатирования, собирается на высоту до 20 м. В ее основе лежат маршевые рамы – несущие стальные элементы, устанавливающиеся в вертикальном положении для достижения нужной высоты подмостей. Они представляют собой сварные прямоугольные каркасы, внутри которых могут находиться прочные перекладины (для образования лестницы, и, соответственно, перемещения строителей между ярусами).</p>
			            	<p>Конструкция всех моделей фасадных средств подмащивания включает в себя следующие элементы:</p>
			            	
			            	<ol>
			            		<li>Башмаки – стальные изделия из опорной пластины и приваренной посередине вертикальной трубки для стыковки с несущими рамами. Их назначение состоит в распределении нагрузки под подмостями. Также встречается название «подпятники».</li>
			            		<li>Горизонтальные связи – трубчатые детали, связывающие противоположно установленные рамы, и факультативно выполняющие роль ограждений.</li>
			            		<li>Диагонали – Х-образные элементы из двух скрепленных посередине труб, которые соединяют две рамы и защищают каркас лесов от кручения. Именно благодаря диагоналям подмости бывают жесткими и, соответственно, безопасными для интенсивного эксплуатирования. При этом данные элементы, как и горизонтали, дополнительно выступают в роли ограждений.</li>
			            		<li>Ригели – металлические элементы, укладывающиеся между двумя противоположными рамами для последующей установки на них строительных настилов.</li>
			            		<li>Усиленный ригель – ригель, предназначенный для работ с повышенным уровнем нагрузки. Так, если обычно допустимая нагрузка не превышает 200 кг/м2, то с усиленными ригелями ее можно увеличить до 500 кг/м2. Также встречается название «ферма».</li>
			            		<li>Настилы – элементы, образующие рабочую поверхность. Без них строители не смогли бы выполнять свои рабочие функции, в связи с чем к данным деталям предъявляются достаточно жесткие требования. Могут производиться из древесины (более дешевый и быстрый в исполнении, но вполне эффективный вариант) или металла (обладают перфорированной поверхностью, максимальной долговечностью и безопасностью).</li>
			            		<li>Кронштейны – стальные изделия, необходимые для крепления каркаса рамочных средств подмащивания к стене во избежание опрокидывания подмостей.</li>
			            	</ol>

			            	<p>Следовательно, можно смело утверждать, что фасадные леса заслуженно считаются современным оборудованием для безопасного и результативного осуществления широкого перечня работ (например, кладки, отделки, реставрации, монтажа и т.д.). К тому же они характеризуются выгодной ценой, что однозначно говорит в их пользу. Профессионалы в разных сферах предпочитают заказывать именно этот вид вспомогательных подмостей, причем, популярностью пользуется не только приобретение металлоконструкций, но и их аренда (если позволяет срок проведения строительных работ).</p>
			            	<p>Наша компания предлагает рамные леса серии ЛР, которые производятся в полном соответствии с ТУ 5225-004-18171908-2017 «Леса строительные рамные. Технические условия».</p>
			            </div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade text-center" id="document_T3">
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на рамные леса</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на элементы лесов</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" target="_blank">Прайс на настилы</a></div>
			            					<div class="col-lg-6"><a class="linkPasport" href="documentViewer_pk_mdnprom/pasport/ramnye-lesa.pdf" target="_blank">Скачать паспорт</a></div>
			            					<div class="col-lg-6"><a class="linkCertificate" href="documentViewer_pk_mdnprom/pasport/sertifikat.jpg " target="_blank">Сертификат</a></div>
			            				</div>
			            			</div>
			            		</div>
			            	</div>
			            </div>
			          </div>
			          <div class="tab-pane fade" id="lr40">
			            <div class="table-lr">
			            	<div class="container">
			            		<div class="row">
			            			<div class="h2">Скомплектовать рамные леса ЛРП 2000-40</div>
			            		</div>
			            		<div class="row">
			            			<!-- Nav tabs -->	
			            			<ul class="nav nav-pills nav-justified">
			            				<li class="active"><a href="#detailed-report_T4" data-toggle="tab">Подробный расчет покупки</a></li>
			            				<li id="detailed-arendalist"><a href="#detailed-arenda_T4" data-toggle="tab">Подробный расчет аренды</a></li>
			            				<li><a href="#characteristic_T4" data-toggle="tab">Характеристика</a></li>
			            				<li><a href="#description_T4" data-toggle="tab">Описание</a></li>
			            				<li><a href="#document_T4" data-toggle="tab">Документы</a></li>
			            			</ul>
			            			<!-- Tab panes -->	
			            			<div class="tab-content">
			            				<div class="tab-pane fade in active" id="detailed-report_T4">
			            					<div class="table-container">
			            						<div class="general-calculation">
			            							<table data-tab="5">
			            								<tr>
			            									<th rowspan="2">Элементы</th>
			            									<th rowspan="2">Количество</th>
			            									<th rowspan="2">Вес</th>
			            									<th colspan="2">Цена, руб. /шт.</th>
			            									<th colspan="2" class="tbarenda">Стоимость аренды</th>
			            								</tr>
			            								<tr>
			            									<th>Розница</th>
			            									<th>ОПТ</th>
			            									<th class="tbarenda">Первые 30 дней</th>
			            									<th class="tbarenda">+ 1 след.день</th>
			            								</tr>
			            								<tr rel="Рама с лестницей 42*1,5 мм.">
			<td data-test="Прайс/Рамные леса">Рама с лестницей 42*1,5 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">10.98</td>  
			<td rel="priceR">1 326.00</td>
			<td rel="PriceD">1 127.10</td>
			<td rel="ArendaAR">265.20</td>
			<td rel="ArendaP">3.98</td>				
			</tr><tr rel="Рама без лестницы 42*1,5 мм.">
			<td data-test="Прайс/Рамные леса">Рама без лестницы 42*1,5 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">8.90</td>  
			<td rel="priceR">1 180.00</td>
			<td rel="PriceD">1 003.00</td>
			<td rel="ArendaAR">236.00</td>
			<td rel="ArendaP">3.54</td>				
			</tr><tr rel="Диагональ 3 м.">
			<td data-test="Прайс/Рамные леса">Диагональ 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">3.69</td>  
			<td rel="priceR">567.00</td>
			<td rel="PriceD">481.95</td>
			<td rel="ArendaAR">113.40</td>
			<td rel="ArendaP">1.70</td>				
			</tr><tr rel="Горизонталь 3 м.">
			<td data-test="Прайс/Рамные леса">Горизонталь 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.62</td>  
			<td rel="priceR">294.00</td>
			<td rel="PriceD">249.90</td>
			<td rel="ArendaAR">58.80</td>
			<td rel="ArendaP">0.88</td>				
			</tr><tr rel="Ригель 3 м.">
			<td data-test="Прайс/Рамные леса">Ригель 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.81</td>  
			<td rel="priceR">841.00</td>
			<td rel="PriceD">714.85</td>
			<td rel="ArendaAR">168.20</td>
			<td rel="ArendaP">2.52</td>				
			</tr><tr rel="Кронштейн 42 мм.">
			<td data-test="Прайс/Общие элементы лесов">Кронштейн 42 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.68</td>  
			<td rel="priceR">207.00</td>
			<td rel="PriceD">175.95</td>
			<td rel="ArendaAR">41.40</td>
			<td rel="ArendaP">0.62</td>				
			</tr><tr rel="Подпятник 42 мм.">
			<td data-test="Прайс/Общие элементы лесов">Подпятник 42 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.60</td>  
			<td rel="priceR">98.00</td>
			<td rel="PriceD">83.30</td>
			<td rel="ArendaAR">19.60</td>
			<td rel="ArendaP">0.29</td>				
			</tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
			<td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (25 мм.)</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">18.00</td>  
			<td rel="priceR">342.00</td>
			<td rel="PriceD">290.70</td>
			<td rel="ArendaAR">68.40</td>
			<td rel="ArendaP">1.03</td>				
			</tr>			            								<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.95</td>  
      <td rel="priceR">409.00</td>
      <td rel="PriceD">347.65</td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.05</td>  
      <td rel="priceR">537.00</td>
      <td rel="PriceD">456.45</td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.15</td>  
      <td rel="priceR">661.00</td>
      <td rel="PriceD">561.85</td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td data-test="Прайс/Рамные леса">Горизонталь 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.50</td>  
      <td rel="priceR">245.00</td>
      <td rel="PriceD">208.25</td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td data-test="Прайс/Рамные леса">Диагональ 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">513.00</td>
      <td rel="PriceD">436.05</td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 42 мм.">
      <td data-test="Прайс/Общие элементы лесов">Домкрат 0,35 м. 42 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.50</td>  
      <td rel="priceR">694.00</td>
      <td rel="PriceD">589.90</td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.40</td>  
      <td rel="priceR">402.00</td>
      <td rel="PriceD">341.70</td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td data-test="Прайс/Общие элементы лесов">Молниеприемник с заземлением 3,6 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">2 086.00</td>
      <td rel="PriceD">1 773.10</td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">9.00</td>  
      <td rel="priceR">277.00</td>
      <td rel="PriceD">235.45</td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">36.00</td>  
      <td rel="priceR">756.00</td>
      <td rel="PriceD">642.60</td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 2,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">2 235.00</td>
      <td rel="PriceD">1 899.75</td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 3,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">2 701.00</td>
      <td rel="PriceD">2 295.85</td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 2*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.02</td>  
      <td rel="priceR">2 547.00</td>
      <td rel="PriceD">2 164.95</td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 3*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">20.09</td>  
      <td rel="priceR">3 459.00</td>
      <td rel="PriceD">2 940.15</td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">660.00</td>
      <td rel="PriceD">561.00</td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,2х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.00</td>  
      <td rel="priceR">823.00</td>
      <td rel="PriceD">699.55</td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.50</td>  
      <td rel="priceR">987.00</td>
      <td rel="PriceD">838.95</td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.00</td>  
      <td rel="priceR">1 316.00</td>
      <td rel="PriceD">1 118.60</td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 644.00</td>
      <td rel="PriceD">1 397.40</td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 3,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 806.00</td>
      <td rel="PriceD">1 535.10</td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.82</td>  
      <td rel="priceR">407.00</td>
      <td rel="PriceD">345.95</td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.12</td>  
      <td rel="priceR">514.00</td>
      <td rel="PriceD">436.90</td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.42</td>  
      <td rel="priceR">607.00</td>
      <td rel="PriceD">515.95</td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.19</td>  
      <td rel="priceR">663.00</td>
      <td rel="PriceD">563.55</td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.54</td>  
      <td rel="priceR">1 079.00</td>
      <td rel="PriceD">917.15</td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.89</td>  
      <td rel="priceR">1 185.00</td>
      <td rel="PriceD">1 007.25</td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 300 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.39</td>  
      <td rel="priceR">214.00</td>
      <td rel="PriceD">181.90</td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 400 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.52</td>  
      <td rel="priceR">313.00</td>
      <td rel="PriceD">266.05</td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 500 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.66</td>  
      <td rel="priceR">443.00</td>
      <td rel="PriceD">376.55</td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (42*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полурама ограждения 1 м. (42*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.15</td>  
      <td rel="priceR">878.00</td>
      <td rel="PriceD">746.30</td>
      <td rel="ArendaAR">175.60</td>
      <td rel="ArendaP">2.63</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (42*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полустойка 1 м. (42*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.85</td>  
      <td rel="priceR">285.00</td>
      <td rel="PriceD">242.25</td>
      <td rel="ArendaAR">57.00</td>
      <td rel="ArendaP">0.86</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 42*1,5 мм.">
      <td data-test="Прайс/Рамные леса">Рама торцевая 42*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem35 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">9.61</td>  
      <td rel="priceR">1 326.00</td>
      <td rel="PriceD">1 127.10</td>
      <td rel="ArendaAR">265.20</td>
      <td rel="ArendaP">3.98</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem36 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.25</td>  
      <td rel="priceR">719.00</td>
      <td rel="PriceD">611.15</td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem37 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 446.00</td>
      <td rel="PriceD">1 229.10</td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem38 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">1 823.00</td>
      <td rel="PriceD">1 549.55</td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 2 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem39 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.24</td>  
      <td rel="priceR">548.00</td>
      <td rel="PriceD">465.80</td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 3 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem40 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.94</td>  
      <td rel="priceR">925.00</td>
      <td rel="PriceD">786.25</td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 4 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem41 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.82</td>  
      <td rel="priceR">1 546.00</td>
      <td rel="PriceD">1 314.10</td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 6 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem43 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">12.07</td>  
      <td rel="priceR">1 965.00</td>
      <td rel="PriceD">1 670.25</td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem44 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">826.00</td>
      <td rel="PriceD">702.10</td>
      <td rel="ArendaAR">165.20</td>
      <td rel="ArendaP">2.48</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem45 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.70</td>  
      <td rel="priceR">926.00</td>
      <td rel="PriceD">787.10</td>
      <td rel="ArendaAR">185.20</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem46 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.20</td>  
      <td rel="priceR">1 050.00</td>
      <td rel="PriceD">892.50</td>
      <td rel="ArendaAR">210.00</td>
      <td rel="ArendaP">3.15</td>        
      </tr>			            								<tr>
			            									<td width="34%">Итого:</td>
			            									<td width="12%"></td>
			            									<td width="10%" rel="vessItog"></td>
			            									<td width="11%" rel="totalSumR"></td>
			            									<td width="11%" rel="totalOpt"></td>
			            									<td width="11%" rel="ArendaD"></td>
			            									<td width="11%" rel="ArendaPI"></td>
			            								</tr>
			            							</table>
			            						</div>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="buy" data-target="#FormTable" type="button" data-id="5" data-type="3" data-title="ЛРП 2000-40" class="btn btn-info getProduct">Купить рамные леса</button>
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="5" data-type="3" data-title="ЛРП 2000-40" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Доп. элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade in" id="detailed-arenda_T4">
			            					<div class="general-calculationRent">
			            						<table data-tab="6">
			            							<tr>
			            								<th rowspan="2">Элементы</th>
			            								<th rowspan="2">Количество</th>
			            								<th colspan="2">Стоимость аренды</th>
			            							</tr>
			            							<tr>
			            								<th>Первые 30 дней</th>
			            								<th>+ 1 след.день</th>
			            							</tr>
			            							<tr rel="Рама с лестницей 42*1,5 мм.">
      <td>Рама с лестницей 42*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">265.20</td>
      <td rel="ArendaP">3.98</td>        
      </tr><tr rel="Рама без лестницы 42*1,5 мм.">
      <td>Рама без лестницы 42*1,5 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">236.00</td>
      <td rel="ArendaP">3.54</td>        
      </tr><tr rel="Горизонталь 3 м.">
      <td>Горизонталь 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">58.80</td>
      <td rel="ArendaP">0.88</td>        
      </tr><tr rel="Диагональ 3 м.">
      <td>Диагональ 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">113.40</td>
      <td rel="ArendaP">1.70</td>        
      </tr><tr rel="Ригель 3 м.">
      <td>Ригель 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">168.20</td>
      <td rel="ArendaP">2.52</td>        
      </tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">68.40</td>
      <td rel="ArendaP">1.03</td>        
      </tr><tr rel="Подпятник 42 мм.">
      <td>Подпятник 42 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">19.60</td>
      <td rel="ArendaP">0.29</td>        
      </tr><tr rel="Полурама ограждения 1 м. (42*1,5 мм.)">
      <td>Полурама ограждения 1 м. (42*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">175.60</td>
      <td rel="ArendaP">2.63</td>        
      </tr>			            							<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td>Горизонталь 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 42 мм.">
      <td>Домкрат 0,35 м. 42 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td>Диагональ 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Кронштейн 42 мм.">
      <td>Кронштейн 42 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">41.40</td>
      <td rel="ArendaP">0.62</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td>Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td>Настил комбинированный 2,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td>Настил комбинированный 3,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td>Настил металлический 2*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td>Настил металлический 3*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td>Ограждение 1,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td>Ограждение 1,2х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td>Ограждение 1,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td>Ограждение 2,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td>Ограждение 2,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td>Ограждение 3,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td>Планка под кронштейн 300 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td>Планка под кронштейн 400 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td>Планка под кронштейн 500 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (42*1,5 мм.)">
      <td>Полустойка 1 м. (42*1,5 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">57.00</td>
      <td rel="ArendaP">0.86</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 42*1,5 мм.">
      <td>Рама торцевая 42*1,5 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">265.20</td>
      <td rel="ArendaP">3.98</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td>Ригель 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td>Ригель усиленный (ферма) 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td>Ригель усиленный (ферма) 3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td>Стабилизирующая опора 2 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td>Стабилизирующая опора 3 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td>Стабилизирующая опора 4 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td>Стабилизирующая опора 6 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">165.20</td>
      <td rel="ArendaP">2.48</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.20</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">210.00</td>
      <td rel="ArendaP">3.15</td>        
      </tr>	
			            							<tr>
			            								<td>Итого:</td>
			            								<td></td>
			            								<td rel="ArendaD"></td>
			            								<td rel="ArendaPI"></td>
			            							</tr>
			            						</table>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="6" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Дополнительные элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade characteristic" id="characteristic_T4">
			            					<table>
			            						<tr>
			            							<th>Марка лесов</th>
			            							<th>ЛРП-40</th>
			            						</tr>
			            						<tr>
			            							<td>Максимальная высота установки</td>
			            							<td>40 м</td>
			            						</tr>
			            						<tr>
			            							<td>Высота яруса</td>
			            							<td>2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Шаг яруса вдоль стены</td>
			            							<td>3 м / 2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Ширина яруса</td>
			            							<td>1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Количество ярусов настилов, не менее</td>
			            							<td>3 шт. (1 рабочий + 2 страховочных)</td>
			            						</tr>
			            						<tr>
			            							<td>Нагрузка <br> для отделочных работ <br> для каменной или кирпичной кладки</td>
			            							<td> <br>до 200ПА(кг/м<sup>2</sup>) <br> Не предусмотрено</td>
			            						</tr>
			            						<tr>
			            							<td>Рама изготовлена из трубы</td>
			            							<td>42*1,5 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Размер рамы</td>
			            							<td>2*1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Горизонталь/Диагональ изготовлена из трубы</td>
			            							<td>25 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Длина горизонтали/Диагонали <br> на длину ячейки 2 м <br> на длину ячейки 3 м</td>
			            							<td><br>2054 мм/2395 мм <br> 3054 мм /3295 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Ригель изготовлен из трубы</td>
			            							<td>60*30*1,5 мм</td>
			            						</tr>
			            					</table>
			            				</div>
			            				<div class="tab-pane fade" id="description_T4">
			            					<div class="col-sm-6">
			            						<div class="h4">Элементы</div>
			            						<ol class="listElemsTab">
			            							<li><span data-id="1">Рама с лестницей</span></li>
			            							<li><span data-id="2">Рама без лестницы</span></li>
			            							<li><span data-id="3">Горизонталь</span></li>
			            							<li><span data-id="4">Диагональ</span></li>
			            							<li><span data-id="5">Ригель</span></li>
			            							<li><span data-id="6">Настил деревянный</span></li>
			            							<li><span data-id="7">Подпятник</span></li>
			            							<li><span data-id="8">Полурама</span></li>
			            						</ol>
			            						<div class="h4">Дополнительные элементы к рамным лесам, не указанные на изображении:</div>
			            						<ul>
			            							<li>Анкерный кронштейн</li>
			            							<li>Выносная консоль</li>
			            							<li>Домкрат</li>
			            							<li>Кронштейн</li>
			            							<li>Настил металлический</li>
			            							<li>Отбортовочный деревянный элемент</li>
			            							<li>Отбортовочный металлический элемент</li>
			            							<li>Планка под кронштейн</li>
			            							<li>Полустойка</li>
			            							<li>Рама торцевая</li>
			            							<li>Ригель усиленный</li>
			            							<li>Стабилизирующая опора</li>
			            							<li>Фасадная сетка</li>
			            							<li>Хомуты кованые оцинкованные</li>
			            							<li>Хомутовая стяжка</li>
			            						</ul>
			            					</div>
			            					<div class="col-sm-6">
			            						<div class="imageElemsTab">
			            							<img src="/img/tableram.png" alt="">	
			            							<div class="pointsTab">
			            								<div data-id="1" class="point active">1</div>
			            								<div data-id="2" class="point">2</div>
			            								<div data-id="3" class="point">3</div>
			            								<div data-id="4" class="point">4</div>
			            								<div data-id="5" class="point">5</div>
			            								<div data-id="6" class="point">6</div>
			            								<div data-id="7" class="point">7</div>
			            								<div data-id="8" class="point">8</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="col-sm-12">
			            		<div class="h4">
			            			<p>Среди всех аналогов рамные строительные леса заслуженно считаются самыми выгодными в финансовом плане, а также одними из самых простых сборно-разборных подмостей в плане монтажа. Представленная модель, абсолютно удобная и безопасная для интенсивного эксплуатирования, собирается на высоту до 40 м. В ее основе лежат маршевые рамы – несущие стальные элементы, устанавливающиеся в вертикальном положении для достижения нужной высоты подмостей. Они представляют собой сварные прямоугольные каркасы, внутри которых могут находиться прочные перекладины (для образования лестницы, и, соответственно, перемещения строителей между ярусами).</p>
			            			<p>Конструкция всех моделей фасадных средств подмащивания включает в себя следующие элементы:</p>
			            			
			            			<ol>
			            				<li>Башмаки – стальные изделия из опорной пластины и приваренной посередине вертикальной трубки для стыковки с несущими рамами. Их назначение состоит в распределении нагрузки под подмостями. Также встречается название «подпятники».</li>
			            				<li>Горизонтальные связи – трубчатые детали, связывающие противоположно установленные рамы, и факультативно выполняющие роль ограждений.</li>
			            				<li>Диагонали – Х-образные элементы из двух скрепленных посередине труб, которые соединяют две рамы и защищают каркас лесов от кручения. Именно благодаря диагоналям подмости бывают жесткими и, соответственно, безопасными для интенсивного эксплуатирования. При этом данные элементы, как и горизонтали, дополнительно выступают в роли ограждений.</li>
			            				<li>Ригели – металлические элементы, укладывающиеся между двумя противоположными рамами для последующей установки на них строительных настилов.</li>
			            				<li>Усиленный ригель – ригель, предназначенный для работ с повышенным уровнем нагрузки. Так, если обычно допустимая нагрузка не превышает 200 кг/м2, то с усиленными ригелями ее можно увеличить до 500 кг/м2. Также встречается название «ферма».</li>
			            				<li>Настилы – элементы, образующие рабочую поверхность. Без них строители не смогли бы выполнять свои рабочие функции, в связи с чем к данным деталям предъявляются достаточно жесткие требования. Могут производиться из древесины (более дешевый и быстрый в исполнении, но вполне эффективный вариант) или металла (обладают перфорированной поверхностью, максимальной долговечностью и безопасностью).</li>
			            				<li>Кронштейны – стальные изделия, необходимые для крепления каркаса рамочных средств подмащивания к стене во избежание опрокидывания подмостей.</li>
			            			</ol>

			            			<p>Следовательно, можно смело утверждать, что фасадные леса заслуженно считаются современным оборудованием для безопасного и результативного осуществления широкого перечня работ (например, кладки, отделки, реставрации, монтажа и т.д.). К тому же они характеризуются выгодной ценой, что однозначно говорит в их пользу. Профессионалы в разных сферах предпочитают заказывать именно этот вид вспомогательных подмостей, причем, популярностью пользуется не только приобретение металлоконструкций, но и их аренда (если позволяет срок проведения строительных работ).</p>
			            			<p>Наша компания предлагает рамные леса серии ЛР, которые производятся в полном соответствии с ТУ 5225-004-18171908-2017 «Леса строительные рамные. Технические условия».</p>
			            		</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade text-center" id="document_T4">
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на рамные леса</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на элементы лесов</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" target="_blank">Прайс на настилы</a></div>
			            					<div class="col-lg-6"><a class="linkPasport" href="documentViewer_pk_mdnprom/pasport/ramnye-lesa.pdf" target="_blank">Скачать паспорт</a></div>
			            					<div class="col-lg-6"><a class="linkCertificate" href="documentViewer_pk_mdnprom/pasport/sertifikat.jpg " target="_blank">Сертификат</a></div>
			            				</div>
			            			</div>
			            		</div>
			            	</div>
			            </div>
			          </div>
			          <div class="tab-pane fade" id="lr60">
			            <div class="table-lr">
			            	<div class="container">
			            		<div class="row">
			            			<div class="h2">Скомплектовать рамные леса ЛРП 2000-60</div>
			            		</div>
			            		<div class="row">
			            			<!-- Nav tabs -->	
			            			<ul class="nav nav-pills nav-justified">
			            				<li class="active"><a href="#detailed-report_T5" data-toggle="tab">Подробный расчет покупки</a></li>
			            				<li id="detailed-arendalist"><a href="#detailed-arenda_T5" data-toggle="tab">Подробный расчет аренды</a></li>
			            				<li><a href="#characteristic_T5" data-toggle="tab">Характеристика</a></li>
			            				<li><a href="#description_T5" data-toggle="tab">Описание</a></li>
			            				<li><a href="#document_T5" data-toggle="tab">Документы</a></li>
			            			</ul>
			            			<!-- Tab panes -->	
			            			<div class="tab-content">
			            				<div class="tab-pane fade in active" id="detailed-report_T5">
			            					<div class="table-container">
			            						<div class="general-calculation">
			            							<table data-tab="7">
			            								<tr>
			            									<th rowspan="2">Элементы</th>
			            									<th rowspan="2">Количество</th>
			            									<th rowspan="2">Вес</th>
			            									<th colspan="2">Цена, руб. /шт.</th>
			            									<th colspan="2" class="tbarenda">Стоимость аренды</th>
			            								</tr>
			            								<tr>
			            									<th>Розница</th>
			            									<th>ОПТ</th>
			            									<th class="tbarenda">Первые 30 дней</th>
			            									<th class="tbarenda">+ 1 след.день</th>
			            								</tr>
			            								<tr rel="Рама с лестницей 42*2 мм.">
			<td data-test="Прайс/Рамные леса">Рама с лестницей 42*2 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">13.42</td>  
			<td rel="priceR">1 506.00</td>
			<td rel="PriceD">1 280.10</td>
			<td rel="ArendaAR">301.20</td>
			<td rel="ArendaP">4.52</td>				
			</tr><tr rel="Рама без лестницы 42*2 мм.">
			<td data-test="Прайс/Рамные леса">Рама без лестницы 42*2 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">10.87</td>  
			<td rel="priceR">1 356.00</td>
			<td rel="PriceD">1 152.60</td>
			<td rel="ArendaAR">271.20</td>
			<td rel="ArendaP">4.07</td>				
			</tr><tr rel="Диагональ 3 м.">
			<td data-test="Прайс/Рамные леса">Диагональ 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">3.69</td>  
			<td rel="priceR">567.00</td>
			<td rel="PriceD">481.95</td>
			<td rel="ArendaAR">113.40</td>
			<td rel="ArendaP">1.70</td>				
			</tr><tr rel="Горизонталь 3 м.">
			<td data-test="Прайс/Рамные леса">Горизонталь 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.62</td>  
			<td rel="priceR">294.00</td>
			<td rel="PriceD">249.90</td>
			<td rel="ArendaAR">58.80</td>
			<td rel="ArendaP">0.88</td>				
			</tr><tr rel="Ригель 3 м.">
			<td data-test="Прайс/Рамные леса">Ригель 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.81</td>  
			<td rel="priceR">841.00</td>
			<td rel="PriceD">714.85</td>
			<td rel="ArendaAR">168.20</td>
			<td rel="ArendaP">2.52</td>				
			</tr><tr rel="Кронштейн 42 мм.">
			<td data-test="Прайс/Общие элементы лесов">Кронштейн 42 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.68</td>  
			<td rel="priceR">207.00</td>
			<td rel="PriceD">175.95</td>
			<td rel="ArendaAR">41.40</td>
			<td rel="ArendaP">0.62</td>				
			</tr><tr rel="Подпятник 42 мм.">
			<td data-test="Прайс/Общие элементы лесов">Подпятник 42 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.60</td>  
			<td rel="priceR">98.00</td>
			<td rel="PriceD">83.30</td>
			<td rel="ArendaAR">19.60</td>
			<td rel="ArendaP">0.29</td>				
			</tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
			<td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (25 мм.)</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">18.00</td>  
			<td rel="priceR">342.00</td>
			<td rel="PriceD">290.70</td>
			<td rel="ArendaAR">68.40</td>
			<td rel="ArendaP">1.03</td>				
			</tr>			            								<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.95</td>  
      <td rel="priceR">409.00</td>
      <td rel="PriceD">347.65</td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.05</td>  
      <td rel="priceR">537.00</td>
      <td rel="PriceD">456.45</td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.15</td>  
      <td rel="priceR">661.00</td>
      <td rel="PriceD">561.85</td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td data-test="Прайс/Рамные леса">Горизонталь 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.50</td>  
      <td rel="priceR">245.00</td>
      <td rel="PriceD">208.25</td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td data-test="Прайс/Рамные леса">Диагональ 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">513.00</td>
      <td rel="PriceD">436.05</td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 42 мм.">
      <td data-test="Прайс/Общие элементы лесов">Домкрат 0,35 м. 42 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.50</td>  
      <td rel="priceR">694.00</td>
      <td rel="PriceD">589.90</td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.40</td>  
      <td rel="priceR">402.00</td>
      <td rel="PriceD">341.70</td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td data-test="Прайс/Общие элементы лесов">Молниеприемник с заземлением 3,6 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">2 086.00</td>
      <td rel="PriceD">1 773.10</td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">9.00</td>  
      <td rel="priceR">277.00</td>
      <td rel="PriceD">235.45</td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">36.00</td>  
      <td rel="priceR">756.00</td>
      <td rel="PriceD">642.60</td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 2,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">2 235.00</td>
      <td rel="PriceD">1 899.75</td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 3,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">2 701.00</td>
      <td rel="PriceD">2 295.85</td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 2*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.02</td>  
      <td rel="priceR">2 547.00</td>
      <td rel="PriceD">2 164.95</td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 3*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">20.09</td>  
      <td rel="priceR">3 459.00</td>
      <td rel="PriceD">2 940.15</td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">660.00</td>
      <td rel="PriceD">561.00</td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,2х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.00</td>  
      <td rel="priceR">823.00</td>
      <td rel="PriceD">699.55</td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.50</td>  
      <td rel="priceR">987.00</td>
      <td rel="PriceD">838.95</td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.00</td>  
      <td rel="priceR">1 316.00</td>
      <td rel="PriceD">1 118.60</td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 644.00</td>
      <td rel="PriceD">1 397.40</td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 3,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 806.00</td>
      <td rel="PriceD">1 535.10</td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.82</td>  
      <td rel="priceR">407.00</td>
      <td rel="PriceD">345.95</td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.12</td>  
      <td rel="priceR">514.00</td>
      <td rel="PriceD">436.90</td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.42</td>  
      <td rel="priceR">607.00</td>
      <td rel="PriceD">515.95</td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.19</td>  
      <td rel="priceR">663.00</td>
      <td rel="PriceD">563.55</td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.54</td>  
      <td rel="priceR">1 079.00</td>
      <td rel="PriceD">917.15</td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.89</td>  
      <td rel="priceR">1 185.00</td>
      <td rel="PriceD">1 007.25</td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 300 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.39</td>  
      <td rel="priceR">214.00</td>
      <td rel="PriceD">181.90</td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 400 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.52</td>  
      <td rel="priceR">313.00</td>
      <td rel="PriceD">266.05</td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 500 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.66</td>  
      <td rel="priceR">443.00</td>
      <td rel="PriceD">376.55</td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (42*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полурама ограждения 1 м. (42*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.15</td>  
      <td rel="priceR">878.00</td>
      <td rel="PriceD">746.30</td>
      <td rel="ArendaAR">175.60</td>
      <td rel="ArendaP">2.63</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (42*1,5 мм.)">
      <td data-test="Прайс/Рамные леса">Полустойка 1 м. (42*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.85</td>  
      <td rel="priceR">285.00</td>
      <td rel="PriceD">242.25</td>
      <td rel="ArendaAR">57.00</td>
      <td rel="ArendaP">0.86</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 42*2 мм.">
      <td data-test="Прайс/Рамные леса">Рама торцевая 42*2 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">11.58</td>  
      <td rel="priceR">1 506.00</td>
      <td rel="PriceD">1 280.10</td>
      <td rel="ArendaAR">301.20</td>
      <td rel="ArendaP">4.52</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem35 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.25</td>  
      <td rel="priceR">719.00</td>
      <td rel="PriceD">611.15</td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem36 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 446.00</td>
      <td rel="PriceD">1 229.10</td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem37 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">1 823.00</td>
      <td rel="PriceD">1 549.55</td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 2 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem38 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.24</td>  
      <td rel="priceR">548.00</td>
      <td rel="PriceD">465.80</td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 3 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem38 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.94</td>  
      <td rel="priceR">925.00</td>
      <td rel="PriceD">786.25</td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 4 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem39 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.82</td>  
      <td rel="priceR">1 546.00</td>
      <td rel="PriceD">1 314.10</td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 6 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem40 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">12.07</td>  
      <td rel="priceR">1 965.00</td>
      <td rel="PriceD">1 670.25</td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem41 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">826.00</td>
      <td rel="PriceD">702.10</td>
      <td rel="ArendaAR">165.20</td>
      <td rel="ArendaP">2.48</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem42 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.70</td>  
      <td rel="priceR">926.00</td>
      <td rel="PriceD">787.10</td>
      <td rel="ArendaAR">185.20</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem43 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.20</td>  
      <td rel="priceR">1 050.00</td>
      <td rel="PriceD">892.50</td>
      <td rel="ArendaAR">210.00</td>
      <td rel="ArendaP">3.15</td>        
      </tr>			            								<tr>
			            									<td width="34%">Итого:</td>
			            									<td width="12%"></td>
			            									<td width="10%" rel="vessItog"></td>
			            									<td width="11%" rel="totalSumR"></td>
			            									<td width="11%" rel="totalOpt"></td>
			            									<td width="11%" rel="ArendaD"></td>
			            									<td width="11%" rel="ArendaPI"></td>
			            								</tr>
			            							</table>
			            						</div>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="buy" data-target="#FormTable" type="button" data-id="7" data-type="4" data-title="ЛРП 2000-60" class="btn btn-info getProduct">Купить рамные леса</button>
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="7" data-type="4" data-title="ЛРП 2000-60" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Доп. элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade in" id="detailed-arenda_T5">
			            					<div class="general-calculationRent">
			            						<table data-tab="8">
			            							<tr>
			            								<th rowspan="2">Элементы</th>
			            								<th rowspan="2">Количество</th>
			            								<th colspan="2">Стоимость аренды</th>
			            							</tr>
			            							<tr>
			            								<th>Первые 30 дней</th>
			            								<th>+ 1 след.день</th>
			            							</tr>
			            							<tr rel="Рама с лестницей 42*2 мм.">
      <td>Рама с лестницей 42*2 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">301.20</td>
      <td rel="ArendaP">4.52</td>        
      </tr><tr rel="Рама без лестницы 42*2 мм.">
      <td>Рама без лестницы 42*2 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">271.20</td>
      <td rel="ArendaP">4.07</td>        
      </tr><tr rel="Горизонталь 3 м.">
      <td>Горизонталь 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">58.80</td>
      <td rel="ArendaP">0.88</td>        
      </tr><tr rel="Диагональ 3 м.">
      <td>Диагональ 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">113.40</td>
      <td rel="ArendaP">1.70</td>        
      </tr><tr rel="Ригель 3 м.">
      <td>Ригель 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">168.20</td>
      <td rel="ArendaP">2.52</td>        
      </tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">68.40</td>
      <td rel="ArendaP">1.03</td>        
      </tr><tr rel="Подпятник 42 мм.">
      <td>Подпятник 42 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">19.60</td>
      <td rel="ArendaP">0.29</td>        
      </tr><tr rel="Полурама ограждения 1 м. (42*1,5 мм.)">
      <td>Полурама ограждения 1 м. (42*1,5 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">175.60</td>
      <td rel="ArendaP">2.63</td>        
      </tr>			            							<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td>Горизонталь 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 42 мм.">
      <td>Домкрат 0,35 м. 42 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">138.80</td>
      <td rel="ArendaP">2.08</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td>Диагональ 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Кронштейн 42 мм.">
      <td>Кронштейн 42 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">41.40</td>
      <td rel="ArendaP">0.62</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td>Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td>Настил комбинированный 2,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td>Настил комбинированный 3,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td>Настил металлический 2*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td>Настил металлический 3*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td>Ограждение 1,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td>Ограждение 1,2х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td>Ограждение 1,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td>Ограждение 2,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td>Ограждение 2,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td>Ограждение 3,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td>Планка под кронштейн 300 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td>Планка под кронштейн 400 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td>Планка под кронштейн 500 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (42*1,5 мм.)">
      <td>Полустойка 1 м. (42*1,5 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">57.00</td>
      <td rel="ArendaP">0.86</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 42*2 мм.">
      <td>Рама торцевая 42*2 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">301.20</td>
      <td rel="ArendaP">4.52</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td>Ригель 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td>Ригель усиленный (ферма) 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td>Ригель усиленный (ферма) 3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td>Стабилизирующая опора 2 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td>Стабилизирующая опора 3 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td>Стабилизирующая опора 4 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td>Стабилизирующая опора 6 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 1,5 м. 42 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">165.20</td>
      <td rel="ArendaP">2.48</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 2 м. 42 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.20</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 3 м. 42 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">210.00</td>
      <td rel="ArendaP">3.15</td>        
      </tr>	
			            							<tr>
			            								<td>Итого:</td>
			            								<td></td>
			            								<td rel="ArendaD"></td>
			            								<td rel="ArendaPI"></td>
			            							</tr>
			            						</table>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="8" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Дополнительные элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade characteristic" id="characteristic_T5">
			            					<table>
			            						<tr>
			            							<th>Марка лесов</th>
			            							<th>ЛРП-60</th>
			            						</tr>
			            						<tr>
			            							<td>Максимальная высота установки</td>
			            							<td>60 м</td>
			            						</tr>
			            						<tr>
			            							<td>Высота яруса</td>
			            							<td>2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Шаг яруса вдоль стены</td>
			            							<td>3 м / 2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Ширина яруса</td>
			            							<td>1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Количество ярусов настилов, не менее</td>
			            							<td>3 шт. (1 рабочий + 2 страховочных)</td>
			            						</tr>
			            						<tr>
			            							<td>Нагрузка <br> для отделочных работ <br> для каменной или кирпичной кладки</td>
			            							<td> <br>до 200ПА(кг/м<sup>2</sup>) <br> до 500ПА(кг/м<sup>2</sup>)</td>
			            						</tr>
			            						<tr>
			            							<td>Рама изготовлена из трубы</td>
			            							<td>42*2 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Размер рамы</td>
			            							<td>2*1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Горизонталь/Диагональ изготовлена из трубы</td>
			            							<td>25 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Длина горизонтали/Диагонали <br> на длину ячейки 2 м <br> на длину ячейки 3 м</td>
			            							<td><br>2054 мм/2395 мм <br> 3054 мм /3295 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Ригель изготовлен из трубы</td>
			            							<td>60*30*1,5 мм</td>
			            						</tr>
			            					</table>
			            				</div>
			            				<div class="tab-pane fade" id="description_T5">
			            					<div class="col-sm-6">
			            						<div class="h4">Элементы</div>
			            						<ol class="listElemsTab">
			            							<li><span data-id="1">Рама с лестницей</span></li>
			            							<li><span data-id="2">Рама без лестницы</span></li>
			            							<li><span data-id="3">Горизонталь</span></li>
			            							<li><span data-id="4">Диагональ</span></li>
			            							<li><span data-id="5">Ригель</span></li>
			            							<li><span data-id="6">Настил деревянный</span></li>
			            							<li><span data-id="7">Подпятник</span></li>
			            							<li><span data-id="8">Полурама</span></li>
			            						</ol>
			            						<div class="h4">Дополнительные элементы к рамным лесам, не указанные на изображении:</div>
			            						<ul>
			            							<li>Анкерный кронштейн</li>
			            							<li>Выносная консоль</li>
			            							<li>Домкрат</li>
			            							<li>Кронштейн</li>
			            							<li>Настил металлический</li>
			            							<li>Отбортовочный деревянный элемент</li>
			            							<li>Отбортовочный металлический элемент</li>
			            							<li>Планка под кронштейн</li>
			            							<li>Полустойка</li>
			            							<li>Рама торцевая</li>
			            							<li>Ригель усиленный</li>
			            							<li>Стабилизирующая опора</li>
			            							<li>Фасадная сетка</li>
			            							<li>Хомуты кованые оцинкованные</li>
			            							<li>Хомутовая стяжка</li>
			            						</ul>
			            					</div>
			            					<div class="col-sm-6">
			            						<div class="imageElemsTab">
			            							<img src="/img/tableram.png" alt="">	
			            							<div class="pointsTab">
			            								<div data-id="1" class="point active">1</div>
			            								<div data-id="2" class="point">2</div>
			            								<div data-id="3" class="point">3</div>
			            								<div data-id="4" class="point">4</div>
			            								<div data-id="5" class="point">5</div>
			            								<div data-id="6" class="point">6</div>
			            								<div data-id="7" class="point">7</div>
			            								<div data-id="8" class="point">8</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="col-sm-12">
			            						<div class="h4">
			            							<p>Среди всех аналогов рамные строительные леса заслуженно считаются самыми выгодными в финансовом плане, а также одними из самых простых сборно-разборных подмостей в плане монтажа. Представленная модель, абсолютно удобная и безопасная для интенсивного эксплуатирования, собирается на высоту до 60 м. В ее основе лежат маршевые рамы – несущие стальные элементы, устанавливающиеся в вертикальном положении для достижения нужной высоты подмостей. Они представляют собой сварные прямоугольные каркасы, внутри которых могут находиться прочные перекладины (для образования лестницы, и, соответственно, перемещения строителей между ярусами).</p>
			            							<p>Конструкция всех моделей фасадных средств подмащивания включает в себя следующие элементы:</p>
			            							
			            							<ol>
			            								<li>Башмаки – стальные изделия из опорной пластины и приваренной посередине вертикальной трубки для стыковки с несущими рамами. Их назначение состоит в распределении нагрузки под подмостями. Также встречается название «подпятники».</li>
			            								<li>Горизонтальные связи – трубчатые детали, связывающие противоположно установленные рамы, и факультативно выполняющие роль ограждений.</li>
			            								<li>Диагонали – Х-образные элементы из двух скрепленных посередине труб, которые соединяют две рамы и защищают каркас лесов от кручения. Именно благодаря диагоналям подмости бывают жесткими и, соответственно, безопасными для интенсивного эксплуатирования. При этом данные элементы, как и горизонтали, дополнительно выступают в роли ограждений.</li>
			            								<li>Ригели – металлические элементы, укладывающиеся между двумя противоположными рамами для последующей установки на них строительных настилов.</li>
			            								<li>Усиленный ригель – ригель, предназначенный для работ с повышенным уровнем нагрузки. Так, если обычно допустимая нагрузка не превышает 200 кг/м2, то с усиленными ригелями ее можно увеличить до 500 кг/м2. Также встречается название «ферма».</li>
			            								<li>Настилы – элементы, образующие рабочую поверхность. Без них строители не смогли бы выполнять свои рабочие функции, в связи с чем к данным деталям предъявляются достаточно жесткие требования. Могут производиться из древесины (более дешевый и быстрый в исполнении, но вполне эффективный вариант) или металла (обладают перфорированной поверхностью, максимальной долговечностью и безопасностью).</li>
			            								<li>Кронштейны – стальные изделия, необходимые для крепления каркаса рамочных средств подмащивания к стене во избежание опрокидывания подмостей.</li>
			            							</ol>

			            							<p>Следовательно, можно смело утверждать, что фасадные леса заслуженно считаются современным оборудованием для безопасного и результативного осуществления широкого перечня работ (например, кладки, отделки, реставрации, монтажа и т.д.). К тому же они характеризуются выгодной ценой, что однозначно говорит в их пользу. Профессионалы в разных сферах предпочитают заказывать именно этот вид вспомогательных подмостей, причем, популярностью пользуется не только приобретение металлоконструкций, но и их аренда (если позволяет срок проведения строительных работ).</p>
			            							<p>Наша компания предлагает рамные леса серии ЛР, которые производятся в полном соответствии с ТУ 5225-004-18171908-2017 «Леса строительные рамные. Технические условия».</p>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade text-center" id="document_T5">
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на рамные леса</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на элементы лесов</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" target="_blank">Прайс на настилы</a></div>
			            					<div class="col-lg-6"><a class="linkPasport" href="documentViewer_pk_mdnprom/pasport/ramnye-lesa.pdf" target="_blank">Скачать паспорт</a></div>
			            					<div class="col-lg-6"><a class="linkCertificate" href="documentViewer_pk_mdnprom/pasport/sertifikat.jpg " target="_blank">Сертификат</a></div>
			            				</div>
			            			</div>
			            		</div>
			            	</div>
			            </div>
			          </div>
			          <div class="tab-pane fade" id="lr80">
			            	<div class="table-lr">
			            		<div class="container">
			            			<div class="row">
			            				<div class="h2">Скомплектовать рамные леса ЛРП 2000-80</div>
			            			</div>
			            			<div class="row">
			            				<!-- Nav tabs -->	
			            				<ul class="nav nav-pills nav-justified">
			            					<li class="active"><a href="#detailed-report_T6" data-toggle="tab">Подробный расчет покупки</a></li>
			            					<li id="detailed-arendalist"><a href="#detailed-arenda_T6" data-toggle="tab">Подробный расчет аренды</a></li>
			            					<li><a href="#characteristic_T6" data-toggle="tab">Характеристика</a></li>
			            					<li><a href="#description_T6" data-toggle="tab">Описание</a></li>
			            					<li><a href="#document_T6" data-toggle="tab">Документы</a></li>
			            				</ul>
			            				<!-- Tab panes -->	
			            				<div class="tab-content">
			            					<div class="tab-pane fade in active" id="detailed-report_T6">
			            						<div class="table-container">
			            							<div class="general-calculation">
			            								<table data-tab="9">
			            									<tr>
			            										<th rowspan="2">Элементы</th>
			            										<th rowspan="2">Количество</th>
			            										<th rowspan="2">Вес</th>
			            										<th colspan="2">Цена, руб. /шт.</th>
			            										<th colspan="2" class="tbarenda">Стоимость аренды</th>
			            									</tr>
			            									<tr>
			            										<th>Розница</th>
			            										<th>ОПТ</th>
			            										<th class="tbarenda">Первые 30 дней</th>
			            										<th class="tbarenda">+ 1 след.день</th>
			            									</tr>
			            									<tr rel="Рама с лестницей 48*2 мм.">
			<td data-test="Прайс/Рамные леса">Рама с лестницей 48*2 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">14.97</td>  
			<td rel="priceR">1 785.00</td>
			<td rel="PriceD">1 517.25</td>
			<td rel="ArendaAR">357.00</td>
			<td rel="ArendaP">5.36</td>				
			</tr><tr rel="Рама без лестницы 48*2 мм.">
			<td data-test="Прайс/Рамные леса">Рама без лестницы 48*2 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">12.90</td>  
			<td rel="priceR">1 512.00</td>
			<td rel="PriceD">1 285.20</td>
			<td rel="ArendaAR">302.40</td>
			<td rel="ArendaP">4.54</td>				
			</tr><tr rel="Диагональ 3 м.">
			<td data-test="Прайс/Рамные леса">Диагональ 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">3.69</td>  
			<td rel="priceR">567.00</td>
			<td rel="PriceD">481.95</td>
			<td rel="ArendaAR">113.40</td>
			<td rel="ArendaP">1.70</td>				
			</tr><tr rel="Горизонталь 3 м.">
			<td data-test="Прайс/Рамные леса">Горизонталь 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.62</td>  
			<td rel="priceR">294.00</td>
			<td rel="PriceD">249.90</td>
			<td rel="ArendaAR">58.80</td>
			<td rel="ArendaP">0.88</td>				
			</tr><tr rel="Ригель 3 м.">
			<td data-test="Прайс/Рамные леса">Ригель 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.81</td>  
			<td rel="priceR">841.00</td>
			<td rel="PriceD">714.85</td>
			<td rel="ArendaAR">168.20</td>
			<td rel="ArendaP">2.52</td>				
			</tr><tr rel="Кронштейн 48 мм.">
			<td data-test="Прайс/Общие элементы лесов">Кронштейн 48 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.68</td>  
			<td rel="priceR">207.00</td>
			<td rel="PriceD">175.95</td>
			<td rel="ArendaAR">41.40</td>
			<td rel="ArendaP">0.62</td>				
			</tr><tr rel="Подпятник 48 мм.">
			<td data-test="Прайс/Общие элементы лесов">Подпятник 48 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.94</td>  
			<td rel="priceR">124.00</td>
			<td rel="PriceD">105.40</td>
			<td rel="ArendaAR">24.80</td>
			<td rel="ArendaP">0.37</td>				
			</tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
			<td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (25 мм.)</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">18.00</td>  
			<td rel="priceR">342.00</td>
			<td rel="PriceD">290.70</td>
			<td rel="ArendaAR">68.40</td>
			<td rel="ArendaP">1.03</td>				
			</tr>			            									<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.95</td>  
      <td rel="priceR">409.00</td>
      <td rel="PriceD">347.65</td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.05</td>  
      <td rel="priceR">537.00</td>
      <td rel="PriceD">456.45</td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.15</td>  
      <td rel="priceR">661.00</td>
      <td rel="PriceD">561.85</td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td data-test="Прайс/Рамные леса">Горизонталь 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.50</td>  
      <td rel="priceR">245.00</td>
      <td rel="PriceD">208.25</td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td data-test="Прайс/Рамные леса">Диагональ 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">513.00</td>
      <td rel="PriceD">436.05</td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 48 мм., пустотелый">
      <td data-test="Одноразовые/Общие элементы лесов">Домкрат 0,35 м. 48 мм., пустотелый</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.50</td>  
      <td rel="priceR">733.00</td>
      <td rel="PriceD">623.05</td>
      <td rel="ArendaAR">146.60</td>
      <td rel="ArendaP">2.20</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.40</td>  
      <td rel="priceR">402.00</td>
      <td rel="PriceD">341.70</td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td data-test="Прайс/Общие элементы лесов">Молниеприемник с заземлением 3,6 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">2 086.00</td>
      <td rel="PriceD">1 773.10</td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">9.00</td>  
      <td rel="priceR">277.00</td>
      <td rel="PriceD">235.45</td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">36.00</td>  
      <td rel="priceR">756.00</td>
      <td rel="PriceD">642.60</td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 2,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">2 235.00</td>
      <td rel="PriceD">1 899.75</td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 3,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">2 701.00</td>
      <td rel="PriceD">2 295.85</td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 2*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.02</td>  
      <td rel="priceR">2 547.00</td>
      <td rel="PriceD">2 164.95</td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 3*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">20.09</td>  
      <td rel="priceR">3 459.00</td>
      <td rel="PriceD">2 940.15</td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">660.00</td>
      <td rel="PriceD">561.00</td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,2х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.00</td>  
      <td rel="priceR">823.00</td>
      <td rel="PriceD">699.55</td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.50</td>  
      <td rel="priceR">987.00</td>
      <td rel="PriceD">838.95</td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.00</td>  
      <td rel="priceR">1 316.00</td>
      <td rel="PriceD">1 118.60</td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 644.00</td>
      <td rel="PriceD">1 397.40</td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 3,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 806.00</td>
      <td rel="PriceD">1 535.10</td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.82</td>  
      <td rel="priceR">407.00</td>
      <td rel="PriceD">345.95</td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.12</td>  
      <td rel="priceR">514.00</td>
      <td rel="PriceD">436.90</td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.42</td>  
      <td rel="priceR">607.00</td>
      <td rel="PriceD">515.95</td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.19</td>  
      <td rel="priceR">663.00</td>
      <td rel="PriceD">563.55</td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.54</td>  
      <td rel="priceR">1 079.00</td>
      <td rel="PriceD">917.15</td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.89</td>  
      <td rel="priceR">1 185.00</td>
      <td rel="PriceD">1 007.25</td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 300 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.39</td>  
      <td rel="priceR">214.00</td>
      <td rel="PriceD">181.90</td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 400 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.52</td>  
      <td rel="priceR">313.00</td>
      <td rel="PriceD">266.05</td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 500 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.66</td>  
      <td rel="priceR">443.00</td>
      <td rel="PriceD">376.55</td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (48*2 мм.)">
      <td data-test="Прайс/Рамные леса">Полурама ограждения 1 м. (48*2 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.30</td>  
      <td rel="priceR">1 356.00</td>
      <td rel="PriceD">1 152.60</td>
      <td rel="ArendaAR">271.20</td>
      <td rel="ArendaP">4.07</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (48*2 мм.)">
      <td data-test="Прайс/Рамные леса">Полустойка 1 м. (48*2 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.90</td>  
      <td rel="priceR">314.00</td>
      <td rel="PriceD">266.90</td>
      <td rel="ArendaAR">62.80</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 48*2 мм.">
      <td data-test="Прайс/Рамные леса">Рама торцевая 48*2 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem35 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">13.61</td>  
      <td rel="priceR">1 785.00</td>
      <td rel="PriceD">1 517.25</td>
      <td rel="ArendaAR">357.00</td>
      <td rel="ArendaP">5.36</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem36 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.25</td>  
      <td rel="priceR">719.00</td>
      <td rel="PriceD">611.15</td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem37 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 446.00</td>
      <td rel="PriceD">1 229.10</td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem38 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">1 823.00</td>
      <td rel="PriceD">1 549.55</td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 2 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem39 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.24</td>  
      <td rel="priceR">548.00</td>
      <td rel="PriceD">465.80</td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 3 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem40 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.94</td>  
      <td rel="priceR">925.00</td>
      <td rel="PriceD">786.25</td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 4 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem41 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.82</td>  
      <td rel="priceR">1 546.00</td>
      <td rel="PriceD">1 314.10</td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 6 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem42 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">12.07</td>  
      <td rel="priceR">1 965.00</td>
      <td rel="PriceD">1 670.25</td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem43 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.10</td>  
      <td rel="priceR">1 002.00</td>
      <td rel="PriceD">851.70</td>
      <td rel="ArendaAR">200.40</td>
      <td rel="ArendaP">3.01</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem44 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.30</td>  
      <td rel="priceR">1 034.00</td>
      <td rel="PriceD">878.90</td>
      <td rel="ArendaAR">206.80</td>
      <td rel="ArendaP">3.10</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem45 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.50</td>  
      <td rel="priceR">1 175.00</td>
      <td rel="PriceD">998.75</td>
      <td rel="ArendaAR">235.00</td>
      <td rel="ArendaP">3.53</td>        
      </tr>			            									<tr>
			            										<td width="34%">Итого:</td>
			            										<td width="12%"></td>
			            										<td width="10%" rel="vessItog"></td>
			            										<td width="11%" rel="totalSumR"></td>
			            										<td width="11%" rel="totalOpt"></td>
			            										<td width="11%" rel="ArendaD"></td>
			            										<td width="11%" rel="ArendaPI"></td>
			            									</tr>
			            								</table>
			            							</div>
			            						</div>
			            						<div class="choice-block">
			            							<div class="container">
			            								<div class="row">
			            									<div class="col-sm-12">
			            										<button data-buyAndrent="buy" data-target="#FormTable" type="button" data-id="9" data-type="5" data-title="ЛРП 2000-80" class="btn btn-info getProduct">Купить рамные леса</button>
			            										<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="9" data-type="5" data-title="ЛРП 2000-80" class="btn btn-danger getProduct">Арендовать</button>
			            										<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Доп. элементы</button>
			            									</div>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="tab-pane fade in" id="detailed-arenda_T6">
			            						<div class="general-calculationRent">
			            							<table data-tab="10">
			            								<tr>
			            									<th rowspan="2">Элементы</th>
			            									<th rowspan="2">Количество</th>
			            									<th colspan="2">Стоимость аренды</th>
			            								</tr>
			            								<tr>
			            									<th>Первые 30 дней</th>
			            									<th>+ 1 след.день</th>
			            								</tr>
			            								<tr rel="Рама с лестницей 48*2 мм.">
      <td>Рама с лестницей 48*2 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">357.00</td>
      <td rel="ArendaP">5.36</td>        
      </tr><tr rel="Рама без лестницы 48*2 мм.">
      <td>Рама без лестницы 48*2 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">302.40</td>
      <td rel="ArendaP">4.54</td>        
      </tr><tr rel="Горизонталь 3 м.">
      <td>Горизонталь 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">58.80</td>
      <td rel="ArendaP">0.88</td>        
      </tr><tr rel="Диагональ 3 м.">
      <td>Диагональ 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">113.40</td>
      <td rel="ArendaP">1.70</td>        
      </tr><tr rel="Ригель 3 м.">
      <td>Ригель 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">168.20</td>
      <td rel="ArendaP">2.52</td>        
      </tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">68.40</td>
      <td rel="ArendaP">1.03</td>        
      </tr><tr rel="Подпятник 48 мм.">
      <td>Подпятник 48 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">24.80</td>
      <td rel="ArendaP">0.37</td>        
      </tr><tr rel="Полурама ограждения 1 м. (48*2 мм.)">
      <td>Полурама ограждения 1 м. (48*2 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">271.20</td>
      <td rel="ArendaP">4.07</td>        
      </tr>			            								<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td>Горизонталь 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 48 мм., пустотелый">
      <td>Домкрат 0,35 м. 48 мм., пустотелый</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">146.60</td>
      <td rel="ArendaP">2.20</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td>Диагональ 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Кронштейн 42 мм.">
      <td>Кронштейн 42 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">41.40</td>
      <td rel="ArendaP">0.62</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td>Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td>Настил комбинированный 2,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td>Настил комбинированный 3,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td>Настил металлический 2*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td>Настил металлический 3*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td>Ограждение 1,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td>Ограждение 1,2х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td>Ограждение 1,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td>Ограждение 2,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td>Ограждение 2,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td>Ограждение 3,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td>Планка под кронштейн 300 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td>Планка под кронштейн 400 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td>Планка под кронштейн 500 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (48*2 мм.)">
      <td>Полустойка 1 м. (48*2 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">62.80</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 48*2 мм.">
      <td>Рама торцевая 48*2 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">357.00</td>
      <td rel="ArendaP">5.36</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td>Ригель 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td>Ригель усиленный (ферма) 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td>Ригель усиленный (ферма) 3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td>Стабилизирующая опора 2 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td>Стабилизирующая опора 3 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td>Стабилизирующая опора 4 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td>Стабилизирующая опора 6 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">200.40</td>
      <td rel="ArendaP">3.01</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">206.80</td>
      <td rel="ArendaP">3.10</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">235.00</td>
      <td rel="ArendaP">3.53</td>        
      </tr>	
			            								<tr>
			            									<td>Итого:</td>
			            									<td></td>
			            									<td rel="ArendaD"></td>
			            									<td rel="ArendaPI"></td>
			            								</tr>
			            							</table>
			            						</div>
			            						<div class="choice-block">
			            							<div class="container">
			            								<div class="row">
			            									<div class="col-sm-12">
			            										<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="10" class="btn btn-danger getProduct">Арендовать</button>
			            										<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Дополнительные элементы</button>
			            									</div>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="tab-pane fade characteristic" id="characteristic_T6">
			            						<table>
			            							<tr>
			            								<th>Марка лесов</th>
			            								<th>ЛРП-80</th>
			            							</tr>
			            							<tr>
			            								<td>Максимальная высота установки</td>
			            								<td>80 м</td>
			            							</tr>
			            							<tr>
			            								<td>Высота яруса</td>
			            								<td>2 м</td>
			            							</tr>
			            							<tr>
			            								<td>Шаг яруса вдоль стены</td>
			            								<td>3 м / 2 м</td>
			            							</tr>
			            							<tr>
			            								<td>Ширина яруса</td>
			            								<td>1 м</td>
			            							</tr>
			            							<tr>
			            								<td>Количество ярусов настилов, не менее</td>
			            								<td>3 шт. (1 рабочий + 2 страховочных)</td>
			            							</tr>
			            							<tr>
			            								<td>Нагрузка <br> для отделочных работ <br> для каменной или кирпичной кладки</td>
			            								<td> <br>до 200ПА(кг/м<sup>2</sup>) <br> до 500ПА(кг/м<sup>2</sup>)</td>
			            							</tr>
			            							<tr>
			            								<td>Рама изготовлена из трубы</td>
			            								<td>48*2 мм</td>
			            							</tr>
			            							<tr>
			            								<td>Размер рамы</td>
			            								<td>2*1 м</td>
			            							</tr>
			            							<tr>
			            								<td>Горизонталь/Диагональ изготовлена из трубы</td>
			            								<td>25 мм</td>
			            							</tr>
			            							<tr>
			            								<td>Длина горизонтали/Диагонали <br> на длину ячейки 2 м <br> на длину ячейки 3 м</td>
			            								<td><br>2054 мм/2395 мм <br> 3054 мм /3295 мм</td>
			            							</tr>
			            							<tr>
			            								<td>Ригель изготовлен из трубы</td>
			            								<td>60*30*1,5 мм</td>
			            							</tr>
			            						</table>
			            					</div>
			            					<div class="tab-pane fade" id="description_T6">
			            						<div class="col-sm-6">
			            							<div class="h4">Элементы</div>
			            							<ol class="listElemsTab">
			            								<li><span data-id="1">Рама с лестницей</span></li>
			            								<li><span data-id="2">Рама без лестницы</span></li>
			            								<li><span data-id="3">Горизонталь</span></li>
			            								<li><span data-id="4">Диагональ</span></li>
			            								<li><span data-id="5">Ригель</span></li>
			            								<li><span data-id="6">Настил деревянный</span></li>
			            								<li><span data-id="7">Подпятник</span></li>
			            								<li><span data-id="8">Полурама</span></li>
			            							</ol>
			            							<div class="h4">Дополнительные элементы к рамным лесам, не указанные на изображении:</div>
			            							<ul>
			            								<li>Анкерный кронштейн</li>
			            								<li>Выносная консоль</li>
			            								<li>Домкрат</li>
			            								<li>Кронштейн</li>
			            								<li>Настил металлический</li>
			            								<li>Отбортовочный деревянный элемент</li>
			            								<li>Отбортовочный металлический элемент</li>
			            								<li>Планка под кронштейн</li>
			            								<li>Полустойка</li>
			            								<li>Рама торцевая</li>
			            								<li>Ригель усиленный</li>
			            								<li>Стабилизирующая опора</li>
			            								<li>Фасадная сетка</li>
			            								<li>Хомуты кованые оцинкованные</li>
			            								<li>Хомутовая стяжка</li>
			            							</ul>
			            						</div>
			            						<div class="col-sm-6">
			            							<div class="imageElemsTab">
			            								<img src="/img/tableram.png" alt="">	
			            								<div class="pointsTab">
			            									<div data-id="1" class="point active">1</div>
			            									<div data-id="2" class="point">2</div>
			            									<div data-id="3" class="point">3</div>
			            									<div data-id="4" class="point">4</div>
			            									<div data-id="5" class="point">5</div>
			            									<div data-id="6" class="point">6</div>
			            									<div data-id="7" class="point">7</div>
			            									<div data-id="8" class="point">8</div>
			            								</div>
			            							</div>
			            						</div>
			            						<div class="col-sm-12">
			            <div class="h4">
			            	<p>Среди всех аналогов рамные строительные леса заслуженно считаются самыми выгодными в финансовом плане, а также одними из самых простых сборно-разборных подмостей в плане монтажа. Представленная модель, абсолютно удобная и безопасная для интенсивного эксплуатирования, собирается на высоту до 80 м. В ее основе лежат маршевые рамы – несущие стальные элементы, устанавливающиеся в вертикальном положении для достижения нужной высоты подмостей. Они представляют собой сварные прямоугольные каркасы, внутри которых могут находиться прочные перекладины (для образования лестницы, и, соответственно, перемещения строителей между ярусами).</p>
			            	<p>Конструкция всех моделей фасадных средств подмащивания включает в себя следующие элементы:</p>
			            	
			            	<ol>
			            		<li>Башмаки – стальные изделия из опорной пластины и приваренной посередине вертикальной трубки для стыковки с несущими рамами. Их назначение состоит в распределении нагрузки под подмостями. Также встречается название «подпятники».</li>
			            		<li>Горизонтальные связи – трубчатые детали, связывающие противоположно установленные рамы, и факультативно выполняющие роль ограждений.</li>
			            		<li>Диагонали – Х-образные элементы из двух скрепленных посередине труб, которые соединяют две рамы и защищают каркас лесов от кручения. Именно благодаря диагоналям подмости бывают жесткими и, соответственно, безопасными для интенсивного эксплуатирования. При этом данные элементы, как и горизонтали, дополнительно выступают в роли ограждений.</li>
			            		<li>Ригели – металлические элементы, укладывающиеся между двумя противоположными рамами для последующей установки на них строительных настилов.</li>
			            		<li>Усиленный ригель – ригель, предназначенный для работ с повышенным уровнем нагрузки. Так, если обычно допустимая нагрузка не превышает 200 кг/м2, то с усиленными ригелями ее можно увеличить до 500 кг/м2. Также встречается название «ферма».</li>
			            		<li>Настилы – элементы, образующие рабочую поверхность. Без них строители не смогли бы выполнять свои рабочие функции, в связи с чем к данным деталям предъявляются достаточно жесткие требования. Могут производиться из древесины (более дешевый и быстрый в исполнении, но вполне эффективный вариант) или металла (обладают перфорированной поверхностью, максимальной долговечностью и безопасностью).</li>
			            		<li>Кронштейны – стальные изделия, необходимые для крепления каркаса рамочных средств подмащивания к стене во избежание опрокидывания подмостей.</li>
			            	</ol>

			            	<p>Следовательно, можно смело утверждать, что фасадные леса заслуженно считаются современным оборудованием для безопасного и результативного осуществления широкого перечня работ (например, кладки, отделки, реставрации, монтажа и т.д.). К тому же они характеризуются выгодной ценой, что однозначно говорит в их пользу. Профессионалы в разных сферах предпочитают заказывать именно этот вид вспомогательных подмостей, причем, популярностью пользуется не только приобретение металлоконструкций, но и их аренда (если позволяет срок проведения строительных работ).</p>
			            	<p>Наша компания предлагает рамные леса серии ЛР, которые производятся в полном соответствии с ТУ 5225-004-18171908-2017 «Леса строительные рамные. Технические условия».</p>
			            </div>
			            						</div>
			            					</div>
			            					<div class="tab-pane fade text-center" id="document_T6">
			            						<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на рамные леса</a></div>
												<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на элементы лесов</a></div>
												<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" target="_blank">Прайс на настилы</a></div>
												<div class="col-lg-6"><a class="linkPasport" href="documentViewer_pk_mdnprom/pasport/ramnye-lesa.pdf" target="_blank">Скачать паспорт</a></div>
												<div class="col-lg-6"><a class="linkCertificate" href="documentViewer_pk_mdnprom/pasport/sertifikat.jpg " target="_blank">Сертификат</a></div>
			            					</div>
			            				</div>
			            			</div>
			            		</div>
			            	</div>
			          </div>
			          <div class="tab-pane fade" id="lr100">
			            <div class="table-lr">
			            	<div class="container">
			            		<div class="row">
			            			<div class="h2">Скомплектовать рамные леса ЛРП 2000-100</div>
			            		</div>
			            		<div class="row">
			            			<!-- Nav tabs -->	
			            			<ul class="nav nav-pills nav-justified">
			            				<li class="active"><a href="#detailed-report_T7" data-toggle="tab">Подробный расчет покупки</a></li>
			            				<li id="detailed-arendalist"><a href="#detailed-arenda_T7" data-toggle="tab">Подробный расчет аренды</a></li>
			            				<li><a href="#characteristic_T7" data-toggle="tab">Характеристика</a></li>
			            				<li><a href="#description_T7" data-toggle="tab">Описание</a></li>
			            				<li><a href="#document_T7" data-toggle="tab">Документы</a></li>
			            			</ul>
			            			<!-- Tab panes -->	
			            			<div class="tab-content">
			            				<div class="tab-pane fade in active" id="detailed-report_T7">
			            					<div class="table-container">
			            						<div class="general-calculation">
			            							<table data-tab="11">
			            								<tr>
			            									<th rowspan="2">Элементы</th>
			            									<th rowspan="2">Количество</th>
			            									<th rowspan="2">Вес</th>
			            									<th colspan="2">Цена, руб. /шт.</th>
			            									<th colspan="2" class="tbarenda">Стоимость аренды</th>
			            								</tr>
			            								<tr>
			            									<th>Розница</th>
			            									<th>ОПТ</th>
			            									<th class="tbarenda">Первые 30 дней</th>
			            									<th class="tbarenda">+ 1 след.день</th>
			            								</tr>
			            								<tr rel="Рама с лестницей 48*3 мм.">
			<td data-test="Прайс/Рамные леса">Рама с лестницей 48*3 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">20.49</td>  
			<td rel="priceR">1 944.00</td>
			<td rel="PriceD">1 652.40</td>
			<td rel="ArendaAR">388.80</td>
			<td rel="ArendaP">5.83</td>				
			</tr><tr rel="Рама без лестницы 48*3 мм.">
			<td data-test="Прайс/Рамные леса">Рама без лестницы 48*3 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">18.42</td>  
			<td rel="priceR">1 808.00</td>
			<td rel="PriceD">1 536.80</td>
			<td rel="ArendaAR">361.60</td>
			<td rel="ArendaP">5.42</td>				
			</tr><tr rel="Диагональ 3 м.">
			<td data-test="Прайс/Рамные леса">Диагональ 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">3.69</td>  
			<td rel="priceR">567.00</td>
			<td rel="PriceD">481.95</td>
			<td rel="ArendaAR">113.40</td>
			<td rel="ArendaP">1.70</td>				
			</tr><tr rel="Горизонталь 3 м.">
			<td data-test="Прайс/Рамные леса">Горизонталь 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">1.62</td>  
			<td rel="priceR">294.00</td>
			<td rel="PriceD">249.90</td>
			<td rel="ArendaAR">58.80</td>
			<td rel="ArendaP">0.88</td>				
			</tr><tr rel="Ригель 3 м.">
			<td data-test="Прайс/Рамные леса">Ригель 3 м.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">5.81</td>  
			<td rel="priceR">841.00</td>
			<td rel="PriceD">714.85</td>
			<td rel="ArendaAR">168.20</td>
			<td rel="ArendaP">2.52</td>				
			</tr><tr rel="Кронштейн 48 мм.">
			<td data-test="Прайс/Общие элементы лесов">Кронштейн 48 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.68</td>  
			<td rel="priceR">207.00</td>
			<td rel="PriceD">175.95</td>
			<td rel="ArendaAR">41.40</td>
			<td rel="ArendaP">0.62</td>				
			</tr><tr rel="Подпятник 48 мм.">
			<td data-test="Прайс/Общие элементы лесов">Подпятник 48 мм.</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">0.94</td>  
			<td rel="priceR">124.00</td>
			<td rel="PriceD">105.40</td>
			<td rel="ArendaAR">24.80</td>
			<td rel="ArendaP">0.37</td>				
			</tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
			<td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (25 мм.)</td>
			<td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
			<td rel="vess">18.00</td>  
			<td rel="priceR">342.00</td>
			<td rel="PriceD">290.70</td>
			<td rel="ArendaAR">68.40</td>
			<td rel="ArendaP">1.03</td>				
			</tr>			            								<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.95</td>  
      <td rel="priceR">409.00</td>
      <td rel="PriceD">347.65</td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.05</td>  
      <td rel="priceR">537.00</td>
      <td rel="PriceD">456.45</td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td data-test="Прайс/Общие элементы лесов">Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.15</td>  
      <td rel="priceR">661.00</td>
      <td rel="PriceD">561.85</td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td data-test="Прайс/Рамные леса">Горизонталь 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.50</td>  
      <td rel="priceR">245.00</td>
      <td rel="PriceD">208.25</td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td data-test="Прайс/Рамные леса">Диагональ 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">513.00</td>
      <td rel="PriceD">436.05</td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 48 мм., пустотелый">
      <td data-test="Одноразовые/Общие элементы лесов">Домкрат 0,35 м. 48 мм., пустотелый</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.50</td>  
      <td rel="priceR">733.00</td>
      <td rel="PriceD">623.05</td>
      <td rel="ArendaAR">146.60</td>
      <td rel="ArendaP">2.20</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem16 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">2.40</td>  
      <td rel="priceR">402.00</td>
      <td rel="PriceD">341.70</td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td data-test="Прайс/Общие элементы лесов">Молниеприемник с заземлением 3,6 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem17 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.30</td>  
      <td rel="priceR">2 086.00</td>
      <td rel="PriceD">1 773.10</td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem18 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">9.00</td>  
      <td rel="priceR">277.00</td>
      <td rel="PriceD">235.45</td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td data-test="Прайс/Настилы">Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem19 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">36.00</td>  
      <td rel="priceR">756.00</td>
      <td rel="PriceD">642.60</td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 2,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem20 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">2 235.00</td>
      <td rel="PriceD">1 899.75</td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td data-test="Прайс/Настилы">Настил комбинированный 3,0*0,3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem21 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">2 701.00</td>
      <td rel="PriceD">2 295.85</td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 2*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem22 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.02</td>  
      <td rel="priceR">2 547.00</td>
      <td rel="PriceD">2 164.95</td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td data-test="Прайс/Настилы">Настил металлический 3*0,28 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem23 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">20.09</td>  
      <td rel="priceR">3 459.00</td>
      <td rel="PriceD">2 940.15</td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.00</td>  
      <td rel="priceR">660.00</td>
      <td rel="PriceD">561.00</td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,2х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.00</td>  
      <td rel="priceR">823.00</td>
      <td rel="PriceD">699.55</td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 1,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.50</td>  
      <td rel="priceR">987.00</td>
      <td rel="PriceD">838.95</td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.00</td>  
      <td rel="priceR">1 316.00</td>
      <td rel="PriceD">1 118.60</td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 2,5х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 644.00</td>
      <td rel="PriceD">1 397.40</td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td data-test="Прайс/Общие элементы лесов">Ограждение 3,0х0,5 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 806.00</td>
      <td rel="PriceD">1 535.10</td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem24 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.82</td>  
      <td rel="priceR">407.00</td>
      <td rel="PriceD">345.95</td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem25 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.12</td>  
      <td rel="priceR">514.00</td>
      <td rel="PriceD">436.90</td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem26 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.42</td>  
      <td rel="priceR">607.00</td>
      <td rel="PriceD">515.95</td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem27 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.19</td>  
      <td rel="priceR">663.00</td>
      <td rel="PriceD">563.55</td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem28 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.54</td>  
      <td rel="priceR">1 079.00</td>
      <td rel="PriceD">917.15</td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem29 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.89</td>  
      <td rel="priceR">1 185.00</td>
      <td rel="PriceD">1 007.25</td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 300 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem30 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.39</td>  
      <td rel="priceR">214.00</td>
      <td rel="PriceD">181.90</td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 400 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem31 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.52</td>  
      <td rel="priceR">313.00</td>
      <td rel="PriceD">266.05</td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td data-test="Прайс/Общие элементы лесов">Планка под кронштейн 500 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem32 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">0.66</td>  
      <td rel="priceR">443.00</td>
      <td rel="PriceD">376.55</td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полурама ограждения 1 м. (48*3 мм.)">
      <td data-test="Прайс/Рамные леса">Полурама ограждения 1 м. (48*3 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem34 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.45</td>  
      <td rel="priceR">1 507.00</td>
      <td rel="PriceD">1 280.95</td>
      <td rel="ArendaAR">301.40</td>
      <td rel="ArendaP">4.52</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (48*3 мм.)">
      <td data-test="Прайс/Рамные леса">Полустойка 1 м. (48*3 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem33 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">1.95</td>  
      <td rel="priceR">349.00</td>
      <td rel="PriceD">296.65</td>
      <td rel="ArendaAR">69.80</td>
      <td rel="ArendaP">1.05</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 48*3 мм.">
      <td data-test="Прайс/Рамные леса">Рама торцевая 48*3 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem35 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">19.13</td>  
      <td rel="priceR">1 944.00</td>
      <td rel="PriceD">1 652.40</td>
      <td rel="ArendaAR">388.80</td>
      <td rel="ArendaP">5.83</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem36 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.25</td>  
      <td rel="priceR">719.00</td>
      <td rel="PriceD">611.15</td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 2 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem37 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">10.00</td>  
      <td rel="priceR">1 446.00</td>
      <td rel="PriceD">1 229.10</td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td data-test="Прайс/Рамные леса">Ригель усиленный (ферма) 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem38 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">15.00</td>  
      <td rel="priceR">1 823.00</td>
      <td rel="PriceD">1 549.55</td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 2 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem39 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">3.24</td>  
      <td rel="priceR">548.00</td>
      <td rel="PriceD">465.80</td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 3 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem40 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">4.94</td>  
      <td rel="priceR">925.00</td>
      <td rel="PriceD">786.25</td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 4 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem41 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">7.82</td>  
      <td rel="priceR">1 546.00</td>
      <td rel="PriceD">1 314.10</td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td data-test="Прайс/Общие элементы лесов">Стабилизирующая опора 6 м. (комплект)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem42 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">12.07</td>  
      <td rel="priceR">1 965.00</td>
      <td rel="PriceD">1 670.25</td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem43 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">5.10</td>  
      <td rel="priceR">1 002.00</td>
      <td rel="PriceD">851.70</td>
      <td rel="ArendaAR">200.40</td>
      <td rel="ArendaP">3.01</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem44 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">6.30</td>  
      <td rel="priceR">1 034.00</td>
      <td rel="PriceD">878.90</td>
      <td rel="ArendaAR">206.80</td>
      <td rel="ArendaP">3.10</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)">
      <td data-test="Прайс/Общие элементы лесов">Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem45 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="vess">8.50</td>  
      <td rel="priceR">1 175.00</td>
      <td rel="PriceD">998.75</td>
      <td rel="ArendaAR">235.00</td>
      <td rel="ArendaP">3.53</td>        
      </tr>			            								<tr>
			            									<td width="34%">Итого:</td>
			            									<td width="12%"></td>
			            									<td width="10%" rel="vessItog"></td>
			            									<td width="11%" rel="totalSumR"></td>
			            									<td width="11%" rel="totalOpt"></td>
			            									<td width="11%" rel="ArendaD"></td>
			            									<td width="11%" rel="ArendaPI"></td>
			            								</tr>
			            							</table>
			            						</div>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="buy" data-target="#FormTable" type="button" data-id="11" data-type="6" data-title="ЛРП 2000-100" class="btn btn-info getProduct">Купить рамные леса</button>
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="11" data-type="6" data-title="ЛРП 2000-100" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Доп. элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade in" id="detailed-arenda_T7">
			            					<div class="general-calculationRent">
			            						<table data-tab="12">
			            							<tr>
			            								<th rowspan="2">Элементы</th>
			            								<th rowspan="2">Количество</th>
			            								<th colspan="2">Стоимость аренды</th>
			            							</tr>
			            							<tr>
			            								<th>Первые 30 дней</th>
			            								<th>+ 1 след.день</th>
			            							</tr>
			            							<tr rel="Рама с лестницей 48*3 мм.">
      <td>Рама с лестницей 48*3 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem1 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">388.80</td>
      <td rel="ArendaP">5.83</td>        
      </tr><tr rel="Рама без лестницы 48*3 мм.">
      <td>Рама без лестницы 48*3 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem2 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.60</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr rel="Горизонталь 3 м.">
      <td>Горизонталь 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem4 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">58.80</td>
      <td rel="ArendaP">0.88</td>        
      </tr><tr rel="Диагональ 3 м.">
      <td>Диагональ 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem6 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">113.40</td>
      <td rel="ArendaP">1.70</td>        
      </tr><tr rel="Ригель 3 м.">
      <td>Ригель 3 м.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem8 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">168.20</td>
      <td rel="ArendaP">2.52</td>        
      </tr><tr rel="Настил деревянный 1,05*0,95 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (25 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem12 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">68.40</td>
      <td rel="ArendaP">1.03</td>        
      </tr><tr rel="Подпятник 48 мм.">
      <td>Подпятник 48 мм.</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem14 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">24.80</td>
      <td rel="ArendaP">0.37</td>        
      </tr><tr rel="Полурама ограждения 1 м. (48*3 мм.)">
      <td>Полурама ограждения 1 м. (48*3 мм.)</td>
      <td><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem15 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">301.40</td>
      <td rel="ArendaP">4.52</td>        
      </tr>			            							<tr class="demo collapse" rel="Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 0,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.80</td>
      <td rel="ArendaP">1.23</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">107.40</td>
      <td rel="ArendaP">1.61</td>        
      </tr><tr class="demo collapse" rel="Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом">
      <td>Анкерный кронштейн 1,5 м. (42-48 мм.) с хомутом</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.20</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Горизонталь 2 м.">
      <td>Горизонталь 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem3 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">49.00</td>
      <td rel="ArendaP">0.74</td>        
      </tr><tr class="demo collapse" rel="Домкрат 0,35 м. 48 мм., пустотелый">
      <td>Домкрат 0,35 м. 48 мм., пустотелый</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">146.60</td>
      <td rel="ArendaP">2.20</td>        
      </tr><tr class="demo collapse" rel="Диагональ 2 м.">
      <td>Диагональ 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.60</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Кронштейн 48 мм.">
      <td>Кронштейн 48 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">41.40</td>
      <td rel="ArendaP">0.62</td>        
      </tr><tr class="demo collapse" rel="Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)">
      <td>Кронштейн-опора регулируемая 350-650 мм, 42-48 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">80.40</td>
      <td rel="ArendaP">1.21</td>        
      </tr><tr class="demo collapse" rel="Молниеприемник с заземлением 3,6 м.">
      <td>Молниеприемник с заземлением 3,6 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">417.20</td>
      <td rel="ArendaP">6.26</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,45 м. (25 мм.)">
      <td>Настил деревянный 1,05*0,45 м. (25 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">55.40</td>
      <td rel="ArendaP">0.83</td>        
      </tr><tr class="demo collapse" rel="Настил деревянный 1,05*0,95 м. (40 мм.)">
      <td>Настил деревянный 1,05*0,95 м. (40 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">151.20</td>
      <td rel="ArendaP">2.27</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 2,0*0,3 м.">
      <td>Настил комбинированный 2,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">447.00</td>
      <td rel="ArendaP">6.71</td>        
      </tr><tr class="demo collapse" rel="Настил комбинированный 3,0*0,3 м.">
      <td>Настил комбинированный 3,0*0,3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">540.20</td>
      <td rel="ArendaP">8.10</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 2*0,28 м.">
      <td>Настил металлический 2*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem11 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">509.40</td>
      <td rel="ArendaP">7.64</td>        
      </tr><tr class="demo collapse" rel="Настил металлический 3*0,28 м.">
      <td>Настил металлический 3*0,28 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">691.80</td>
      <td rel="ArendaP">10.38</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,0х0,5 м.">
      <td>Ограждение 1,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.00</td>
      <td rel="ArendaP">1.98</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,2х0,5 м.">
      <td>Ограждение 1,2х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">164.60</td>
      <td rel="ArendaP">2.47</td>        
      </tr><tr class="demo collapse" rel="Ограждение 1,5х0,5 м.">
      <td>Ограждение 1,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">197.40</td>
      <td rel="ArendaP">2.96</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,0х0,5 м.">
      <td>Ограждение 2,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">263.20</td>
      <td rel="ArendaP">3.95</td>        
      </tr><tr class="demo collapse" rel="Ограждение 2,5х0,5 м.">
      <td>Ограждение 2,5х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">328.80</td>
      <td rel="ArendaP">4.93</td>        
      </tr><tr class="demo collapse" rel="Ограждение 3,0х0,5 м.">
      <td>Ограждение 3,0х0,5 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=count1Elem58 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">361.20</td>
      <td rel="ArendaP">5.42</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 1000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 1000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">81.40</td>
      <td rel="ArendaP">1.22</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 2000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 2000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">102.80</td>
      <td rel="ArendaP">1.54</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный дер. эл. 3000х25х150 мм (комплект)">
      <td>Отбортовочный дер. эл. 3000х25х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">121.40</td>
      <td rel="ArendaP">1.82</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 1000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 1000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">132.60</td>
      <td rel="ArendaP">1.99</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 2000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 2000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">215.80</td>
      <td rel="ArendaP">3.24</td>        
      </tr><tr class="demo collapse" rel="Отбортовочный мет. эл. 3000х150 мм (комплект)">
      <td>Отбортовочный мет. эл. 3000х150 мм (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">237.00</td>
      <td rel="ArendaP">3.56</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 300 мм.">
      <td>Планка под кронштейн 300 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">42.80</td>
      <td rel="ArendaP">0.64</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 400 мм.">
      <td>Планка под кронштейн 400 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">62.60</td>
      <td rel="ArendaP">0.94</td>        
      </tr><tr class="demo collapse" rel="Планка под кронштейн 500 мм.">
      <td>Планка под кронштейн 500 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem5 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">88.60</td>
      <td rel="ArendaP">1.33</td>        
      </tr><tr class="demo collapse" rel="Полустойка 1 м. (48*3 мм.)">
      <td>Полустойка 1 м. (48*3 мм.)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem13 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">69.80</td>
      <td rel="ArendaP">1.05</td>        
      </tr><tr class="demo collapse" rel="Рама торцевая 48*3 мм.">
      <td>Рама торцевая 48*3 мм.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">388.80</td>
      <td rel="ArendaP">5.83</td>        
      </tr><tr class="demo collapse" rel="Ригель 2 м.">
      <td>Ригель 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem7 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">143.80</td>
      <td rel="ArendaP">2.16</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 2 м.">
      <td>Ригель усиленный (ферма) 2 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem9 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">289.20</td>
      <td rel="ArendaP">4.34</td>        
      </tr><tr class="demo collapse" rel="Ригель усиленный (ферма) 3 м.">
      <td>Ригель усиленный (ферма) 3 м.</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">364.60</td>
      <td rel="ArendaP">5.47</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 2 м. (комплект)">
      <td>Стабилизирующая опора 2 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">109.60</td>
      <td rel="ArendaP">1.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 3 м. (комплект)">
      <td>Стабилизирующая опора 3 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">185.00</td>
      <td rel="ArendaP">2.78</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 4 м. (комплект)">
      <td>Стабилизирующая опора 4 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">309.20</td>
      <td rel="ArendaP">4.64</td>        
      </tr><tr class="demo collapse" rel="Стабилизирующая опора 6 м. (комплект)">
      <td>Стабилизирующая опора 6 м. (комплект)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">393.00</td>
      <td rel="ArendaP">5.90</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 1,5 м. 48 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">200.40</td>
      <td rel="ArendaP">3.01</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 2 м. 48 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">206.80</td>
      <td rel="ArendaP">3.10</td>        
      </tr><tr class="demo collapse" rel="Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)">
      <td>Хомутовая стяжка 3 м. 48 мм. (с двумя хомутами)</td>
      <td ><div class="production2">
            <div class="productTable">
              <div class="rowcalc">
                <div class="countGroup">
                <div class="minus TabRecount active"></div>
                <input class="form-control" name="countElement" id=countElem10 value="0">
                <div class="plus TabRecount active"></div>
                </div>
              </div>
            </div>
          </div></td>
      <td rel="ArendaAR">235.00</td>
      <td rel="ArendaP">3.53</td>        
      </tr>	
			            							<tr>
			            								<td>Итого:</td>
			            								<td></td>
			            								<td rel="ArendaD"></td>
			            								<td rel="ArendaPI"></td>
			            							</tr>
			            						</table>
			            					</div>
			            					<div class="choice-block">
			            						<div class="container">
			            							<div class="row">
			            								<div class="col-sm-12">
			            									<button data-buyAndrent="rent" data-target="#FormTable" type="button" data-id="12" class="btn btn-danger getProduct">Арендовать</button>
			            									<button type="button" class="btn btn-warning" data-toggle="collapse" data-target=".demo" >Дополнительные элементы</button>
			            								</div>
			            							</div>
			            						</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade characteristic" id="characteristic_T7">
			            					<table>
			            						<tr>
			            							<th>Марка лесов</th>
			            							<th>ЛРП-100</th>
			            						</tr>
			            						<tr>
			            							<td>Максимальная высота установки</td>
			            							<td>100 м</td>
			            						</tr>
			            						<tr>
			            							<td>Высота яруса</td>
			            							<td>2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Шаг яруса вдоль стены</td>
			            							<td>3 м / 2 м</td>
			            						</tr>
			            						<tr>
			            							<td>Ширина яруса</td>
			            							<td>1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Количество ярусов настилов, не менее</td>
			            							<td>3 шт. (1 рабочий + 2 страховочных)</td>
			            						</tr>
			            						<tr>
			            							<td>Нагрузка <br> для отделочных работ <br> для каменной или кирпичной кладки</td>
			            							<td> <br>до 200ПА(кг/м<sup>2</sup>) <br> до 500ПА(кг/м<sup>2</sup>)</td>
			            						</tr>
			            						<tr>
			            							<td>Рама изготовлена из трубы</td>
			            							<td>48*3 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Размер рамы</td>
			            							<td>2*1 м</td>
			            						</tr>
			            						<tr>
			            							<td>Горизонталь/Диагональ изготовлена из трубы</td>
			            							<td>25 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Длина горизонтали/Диагонали <br> на длину ячейки 2 м <br> на длину ячейки 3 м</td>
			            							<td><br>2054 мм/2395 мм <br> 3054 мм /3295 мм</td>
			            						</tr>
			            						<tr>
			            							<td>Ригель изготовлен из трубы</td>
			            							<td>60*30*1,5 мм</td>
			            						</tr>
			            					</table>
			            				</div>
			            				<div class="tab-pane fade" id="description_T7">
			            					<div class="col-sm-6">
			            						<div class="h4">Элементы</div>
			            						<ol class="listElemsTab">
			            							<li><span data-id="1">Рама с лестницей</span></li>
			            							<li><span data-id="2">Рама без лестницы</span></li>
			            							<li><span data-id="3">Горизонталь</span></li>
			            							<li><span data-id="4">Диагональ</span></li>
			            							<li><span data-id="5">Ригель</span></li>
			            							<li><span data-id="6">Настил деревянный</span></li>
			            							<li><span data-id="7">Подпятник</span></li>
			            							<li><span data-id="8">Полурама</span></li>
			            						</ol>
			            						<div class="h4">Дополнительные элементы к рамным лесам, не указанные на изображении:</div>
			            						<ul>
			            							<li>Анкерный кронштейн</li>
			            							<li>Выносная консоль</li>
			            							<li>Домкрат</li>
			            							<li>Кронштейн</li>
			            							<li>Настил металлический</li>
			            							<li>Отбортовочный деревянный элемент</li>
			            							<li>Отбортовочный металлический элемент</li>
			            							<li>Планка под кронштейн</li>
			            							<li>Полустойка</li>
			            							<li>Рама торцевая</li>
			            							<li>Ригель усиленный</li>
			            							<li>Стабилизирующая опора</li>
			            							<li>Фасадная сетка</li>
			            							<li>Хомуты кованые оцинкованные</li>
			            							<li>Хомутовая стяжка</li>
			            						</ul>
			            					</div>
			            					<div class="col-sm-6">
			            						<div class="imageElemsTab">
			            							<img src="/img/tableram.png" alt="">	
			            							<div class="pointsTab">
			            								<div data-id="1" class="point active">1</div>
			            								<div data-id="2" class="point">2</div>
			            								<div data-id="3" class="point">3</div>
			            								<div data-id="4" class="point">4</div>
			            								<div data-id="5" class="point">5</div>
			            								<div data-id="6" class="point">6</div>
			            								<div data-id="7" class="point">7</div>
			            								<div data-id="8" class="point">8</div>
			            							</div>
			            						</div>
			            					</div>
			            					<div class="col-sm-12">
			            	<div class="h4">
			            		<p>Среди всех аналогов рамные строительные леса заслуженно считаются самыми выгодными в финансовом плане, а также одними из самых простых сборно-разборных подмостей в плане монтажа. Представленная модель, абсолютно удобная и безопасная для интенсивного эксплуатирования, собирается на высоту до 100 м. В ее основе лежат маршевые рамы – несущие стальные элементы, устанавливающиеся в вертикальном положении для достижения нужной высоты подмостей. Они представляют собой сварные прямоугольные каркасы, внутри которых могут находиться прочные перекладины (для образования лестницы, и, соответственно, перемещения строителей между ярусами).</p>
			            		<p>Конструкция всех моделей фасадных средств подмащивания включает в себя следующие элементы:</p>
			            		
			            		<ol>
			            			<li>Башмаки – стальные изделия из опорной пластины и приваренной посередине вертикальной трубки для стыковки с несущими рамами. Их назначение состоит в распределении нагрузки под подмостями. Также встречается название «подпятники».</li>
			            			<li>Горизонтальные связи – трубчатые детали, связывающие противоположно установленные рамы, и факультативно выполняющие роль ограждений.</li>
			            			<li>Диагонали – Х-образные элементы из двух скрепленных посередине труб, которые соединяют две рамы и защищают каркас лесов от кручения. Именно благодаря диагоналям подмости бывают жесткими и, соответственно, безопасными для интенсивного эксплуатирования. При этом данные элементы, как и горизонтали, дополнительно выступают в роли ограждений.</li>
			            			<li>Ригели – металлические элементы, укладывающиеся между двумя противоположными рамами для последующей установки на них строительных настилов.</li>
			            			<li>Усиленный ригель – ригель, предназначенный для работ с повышенным уровнем нагрузки. Так, если обычно допустимая нагрузка не превышает 200 кг/м2, то с усиленными ригелями ее можно увеличить до 500 кг/м2. Также встречается название «ферма».</li>
			            			<li>Настилы – элементы, образующие рабочую поверхность. Без них строители не смогли бы выполнять свои рабочие функции, в связи с чем к данным деталям предъявляются достаточно жесткие требования. Могут производиться из древесины (более дешевый и быстрый в исполнении, но вполне эффективный вариант) или металла (обладают перфорированной поверхностью, максимальной долговечностью и безопасностью).</li>
			            			<li>Кронштейны – стальные изделия, необходимые для крепления каркаса рамочных средств подмащивания к стене во избежание опрокидывания подмостей.</li>
			            		</ol>

			            		<p>Следовательно, можно смело утверждать, что фасадные леса заслуженно считаются современным оборудованием для безопасного и результативного осуществления широкого перечня работ (например, кладки, отделки, реставрации, монтажа и т.д.). К тому же они характеризуются выгодной ценой, что однозначно говорит в их пользу. Профессионалы в разных сферах предпочитают заказывать именно этот вид вспомогательных подмостей, причем, популярностью пользуется не только приобретение металлоконструкций, но и их аренда (если позволяет срок проведения строительных работ).</p>
			            		<p>Наша компания предлагает рамные леса серии ЛР, которые производятся в полном соответствии с ТУ 5225-004-18171908-2017 «Леса строительные рамные. Технические условия».</p>
			            	</div>
			            					</div>
			            				</div>
			            				<div class="tab-pane fade text-center" id="document_T7">
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на рамные леса</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_lesa_ramnye_mdn.pdf" target="_blank">Прайс на элементы лесов</a></div>
			            					<div class="col-lg-4"><a class="linkPrice" href="documentViewer_pk_mdnprom/prices/stroitelnye_nastily_mdn.pdf" target="_blank">Прайс на настилы</a></div>
			            					<div class="col-lg-6"><a class="linkPasport" href="documentViewer_pk_mdnprom/pasport/ramnye-lesa.pdf" target="_blank">Скачать паспорт</a></div>
			            					<div class="col-lg-6"><a class="linkCertificate" href="documentViewer_pk_mdnprom/pasport/sertifikat.jpg " target="_blank">Сертификат</a></div>
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


</template>

<script>
export default {
  head: {
    title: 'Рамные леса от производителя  ООО "ПК МДН-Пром"',
    meta: [
      { charset: "utf-8" },
      { name: "viewport", content: "width=device-width, initial-scale=1" },
      {
        hid: "description",
        name: "description",
        content: 'Заказать рамные строительные леса в компании ООО "ПК МДН-Пром", которые отличаются высокой прочностью, простотой в эксплуатации, и, при этом, их стоимость намного ниже по сравнению с другими видами строительных лесов.'
      }
    ]
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
.line-lesa .lesa-block .nuxt-link-active .overlay{
 top: 0;
 background: rgba(0,0,0,0.3);
}
</style>
