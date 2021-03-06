# Анализ рынка недвижимости Санкт-Петербурга

## Задача

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

## Что было выполнено:

- Проведен исследовательский анализ и предобработка данных для датасета с объявлениями о продаже квартир в Санкт-Петербурге 
- Выявлены, влияние площади, потолков, количества комнат, даты объявления на цены квартир всех представленных населённых пунктов и центра Санкт-Петербурга для построения автоматизированной системы определения цен во избежание мошенничества и аномалий
- На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра 
- Проведена предобработка данных. Добавлены новые данные
- Построены гистограммы, боксплоты, диаграммы рассеивания

## Библиотеки

*pandas*

## Выводы

Выявлены следующие зависимости:
- С ростом площади квартиры ее стоимость увеличивается
- Стоимость квартир на первых и последних этажах гораздо ниже, чем в промежуточных
- Инфляция оказывает свое влияние на рост квартир: год от года они стоят дороже. Причем, если в целом по городу можно отметить некий застой цен в послекризисные годы, то в центральной зоне жилье продолжиро расти в цене

За пределами Санкт-Петербурга жилье стоит дешевле. Стоимость квартир в туристическом городе Пушкино гораздо выше, чем в более близких к Санкт-Петербургу населенных пунктах, представленных типовыми многоэтажками.

В центральной зоне здания гораздо ниже, чем в среднем по городу: чем ближе к центру, тем меньше объявлений о продаже можно обнаружить. Тем не менее, их стоимость гораздо выше, причем этаж уже не имеет существенного значения. Историческая застройка накладывает отепчаток на кол-во комнат: однушки и квартиры с 4 или большим числом комнат почти отсутствуют.
