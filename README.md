# interactive-web-map

### Cостав команды:
* Ильясов Яшар 
* Недосекина Алёна
* Сушко Анастасия
* Шаталин Юрий

### Ссылка на карту:
https://printscreensys.github.io/interactive-web-map/

Кратко о городе: город Уфа
Основан в 1574 году
Население: 1 144 809 (2021)
Плотность: 1617,12 чел./км²

### Информация
Уфа — столица Республики Башкортостан, административный центр Уфимского района, в состав которого не входит.  Расположена на Уфимском полуострове, в водоразделе рек Белой и Уфы.

В рамках административно-территориального устройства, город Уфа состоит из 7 городских районов.

История Уфы начинается с 1574) года со строительства Уфимского кремля. Основателем крепости является воевода Иван Нагой, первым городским воеводой является Михаил Нагой. С конца XVI века Уфа использовалась как место политической ссылки. Уфа выдержала много набегов и осад в XVII—XVIII веках, но ни разу не была взята; в том числе, она выдержала четырехмесячную блокаду и штурмы во время Крестьянской войны 1773—1775 годов. При эвакуации в Великую Отечественную войну, в Уфу эвакуировали промышленные предприятия, научные и образовательные учреждения, и людей.

Уфа является точкой роста экономики Башкортостана, и вносит значительный вклад в экономику России — в городе производится ряд важнейших видов продукции страны — бензин, дизельное топливо и полимеры пропилена, а также клеёной фанеры, нефти и топочного мазута. Основу обрабатывающей промышленности Уфы составляет производства нефтепродуктов и нефтехимии, машиностроение и химическая промышленность.

### Используемые данные и источники:
* Административные границы
* ОКН - объекты капитального строительства (полигоны зданий)
* ОКН - точки
* Парки, монументы и могилы

### Основные используемые методы:
* folium.Plugins - LayerControl, Mouse Position, Fullscreen
* Кластеры из точек, агрегирование по ячейкам

### Возникшие сложности в работе:
* Применить кастомные цвета к Choropleth
* Кастомные маркеры
* Очистка данных от несуществующих адресов и утраченных ОКН, дополнительная отрисовка зданий, добавление координат для братских могил, памятников на кладбищах

### Чем мы гордимся:
* (тем, что мы смогли это сделать)
* Иконки для точек

### Что не получилось сделать:
* (сдать вовремя)
* Некоторые опциональные пункты задания 
* Зум-уровни - через Python - не нашел в документации, можно ли так делать. Через JavaScript не получилось сделать
* Добавить Search - не отображался на карте почему-то
