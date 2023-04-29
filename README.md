# **Baikal Electronics**
![микропроцессор байкал](/Images/1.jpg)
## **Как появилась Baikal Electronics?**
***Изначально*** —в 2002 году появилась компания под названием ««Т-Платформа» — фирма специализировалась на высокопроизводительных вычислениях и в свое время добилась успехов. Основным направлением стала разработка суперкомпьютеров.
В 2004 был создан «СКИФ К-1000» на базе процессоров AMD Opteron, который занял 98 место в списке ТОП-100 самых мощных суперкомпьютеров. В 2007 и 2008 годах были **созданы еще пара суперкомпьютеров линейки «СКИФ»** с пиковой производительностью в 12 и 60 Тфлопс соответственно.
***Идея создания процессоров*** «Байкал» появилась не как ответ AMD или Intel, а просто как необходимость на фоне санкций. Уже тогда перспектива ограничений на западные технологии витала в воздухе, поэтому чтобы не откатиться обратно к перфокартам, было решено заняться собственными разработками. Так на базе «Т-Платформы» в январе 2012 года была основана Baikal Electronics (ВЕ), а уже через год анонсировали разработку первого процессора.

## **Линейка процессоров «Байкал»**
Инженеры из Baikal Electronics решили не изобретать велосипед, и пошли по более простому пути — лицензировали уже готовую технологию. Однако сделка с ARM не получилась из-за введенных санкций, поэтому за основу взяли ядро `MIPS Warrior P-Class P5600` от британской фирмы Imagination Technologies. Последняя обычным пользователям известна по графике PowerVR, которую часто можно встретить в смартфонах

![блок-схемабайкал](/Images/2.jpg)

*Разработка была ориентирована на всевозможные встроенные системы* — включая `станки`, `роутеры` и `банкоматы`. Несмотря на использование фактически иностранной технологии, разработчики из ВЕ уверяли, что уровень контроля *исключает любые потенциальные шпионские «закладки»*.

**Линейка процессоров Байкал в 2021г:**
 - Байкал-М/2
 - Байкал-М/2+
 - Байкал-S
 
*На сегодняшний день Байкал приостановил производство*

В 2015 появились первые инженерные образцы `Baikal Т1` — двухъядерный чип по техпроцессу `28 нм` с поддержкой до *8 ГБ DDR3*. С учетом позиционирования T1 стал весьма привлекательным решением для встраиваемых систем. В 2016 году началось массовое производство — первая партия включала *100 тысяч процессоров*, а число заказчиков согласно представителям Baikal Electronics доходило до 100 фирм.

![байкал т1](/Images/3.jpg)

В 2018 году в магазинах можно было найти в свободной покупке сам процессор. Купить `BE-T1000` (*он же «Байкал-Т1»*) можно было за ***3990 рублей***.

В конце 2013 года санкции были сняты, поэтому разработчикам наконец-то удалось лицензировать использование технологий компании **Arm Limited**. Так была поставлена новая цель — создать процессоры уже для ПК и микросерверов на архитектуре ARM. С 2016 по 2018 велась разработка процессора `Baikal-M1`, *а уже с 2019 начался выпуск на мощностях TSMC*.

![байкал м1](/Images/4.jpg)

К октябрю 2021 было достоверно известно о получении **партии из 5000 процессоро**в, а позже еще 3000, хотя был сделан заказ как минимум на *130 тысяч изделий.* С учетом дефицита полупроводников планировалось получать по 10–15 тысяч процессоров ежемесячно, начиная с 2022 года.

**В Baikal Electronics** также активно занимались выходом на рынок серверов и систем хранения данных. Так в конце 2021 года были представлены первые инженерные образцы уже серверной модели Baikal-S на ядрах `ARM Cortex-A75`.

![байкал c1](/Images/5.jpg)

Таким образом, фактически **Baikal Electronics** разработали **`три основных чипа`**, нацеленных на разные сферы применения — от встраиваемых систем до высокопроизводительных серверов. В планах компании также были **`Baikal-M lite`** (упрощенная и более дешевая версия), **`Baikal-L`** (для ноутбуков) и модели следующих поколений **`M2, S2`**. *Однако все эти чипы пока остаются только на бумаге.*

## **Производительность процессоров «Байкал»**
Когда пошла речь о первых отечественных процессорах, пусть и на лицензируемой архитектуре, сразу же начались *вопросы относительно производительности*. Однако в случае с `Baikal T1` стоит отметить, что **процессор предназначен для встраиваемых систем**. Это означает, что производительность здесь далеко не в приоритете, `намного важнее стабильность работы и доступность ПО`.
В 2018 году к энтузиастам из ServerNews попала отладочная плата  `BFK 3.1 с процессором Baikal T1`. Были выполнены тесты в *`CoreMark`*, *`Dhrystone 2`*, *`Phoronix Test Suite`* и других программах. В целом *процессор опережает Intel Atom*, но почти вчетверо *проигрывает Intel Core 2 Duo*. Сами же инженеры  Baikal Electronics представили свои результаты, которые позже свели в **`таблицу**`:

![таблица ](/Images/6.jpg)

Для сферы коммуникаций Baikal T1 выглядит *вполне достойным решением* — об этом говорит и наличие различных устройств, о которых мы поговорим далее. Однако к 2019 году у процессора было много проблем с софтом и мало технической документации. Проще говоря, продукт нуждался в доработке уже со стороны программистов для создания полноценной экосистемы.

Согласно тестам были сделаны выводы, что **процессор опережает** **`Intel Atom E3940`** и немного не дотягивает до  **`Core i3-7300Т`**. В рамках офисных систем Baikal-M вполне может удовлетворить основные потребности, но многое зависит от вариантов готовой продукции.

![сравнение байкала S ](/Images/7.jpg)

Серверный **`Baikal-S`** является самым *высокопроизводительным в линейке*, однако в распоряжении разработчиков имеются только инженерные образцы. Соответственно, к сторонним тестировщикам процессор никогда не попадал, и все данные предоставлены исключительно Baikal Electronics. Исходя из представленных результатов, за счёт большего количества ARM-ядер Baikal S успешно **конкурирует с ** `Xeon Gold 6148` и `AMD EPYC 7351`. Применение ARM-процессоров в качестве серверных становится все более актуальной тенденцией. Такие модели не только обходятся дешевле, они обычно имеют меньшее тепловыделение и большее число ядер. *Учитывая эти моменты, Baikal S действительно мог бы стать достойной отечественной заменой.*

### *Что же сейчас имеется на Байкалах и в какой доступности?*
Первой разработкой на Baikal-Т1 стала система числового программного управления `(СЧПУ) «Ресурс-30»` многокоординатного фрезерного станка, представленная в 2016 году. Через год обещали продажи для массового пользователя. Там же анонсировали терминал `Таволга TP-T22BT`. Последний даже сумели *продать тиражом 9348 устройств* в МВД — терминалы использовались для сдачи теоретического экзамена на права. Однако позже к «Т-Платформы» был предъявлен иск, что терминалы не соответствуют необходимым требованиям.

![картинка с компами ](/Images/8.jpg)

Была разработана также рабочая станция `2ВТ1`, однако о *каких-либо массовых поставках информации нет*, хотя схожий терминал под кодовым названием `ED506` можно купить в компании «Эдельвейс».
Также представлены процессорные платы `CPC313` и `CPC516` от компании *Fastwel*. Обе платы можно заказать на официальном сайте, но стоимость не указана.

![картинка с платами ](/Images/9.jpg)

 - Таким образом, различные платы на базе Baikal-T1 были произведены в достаточных объемах, и некоторые из них можно даже приобрести. 

Однако более серьезная продукция, в частности терминалы и маршрутизаторы, если и выпускались, то сугубо для госсектора и в небольших количествах.
*Дела с Baikal-M обстоят еще хуже*. В своей презентации разработчики анонсировали, что уже разработано больше *10 материнских плат и 50+ устройств на базе Baikal-M.* Однако ключевое слово здесь — «разработано». Проблема с выпуском готовых продуктов осталась, ведь в Россию по итогу было завезено всего лишь 8000 чипов.
Те же продукты, которые добрались до пользователей или тестировщиков, были выпущены очень малыми партиями. Если материнские платы на базе Байкала еще встретить в продаже можно, то ассортимент готовых сборок еще не столь велик. *`В продаже имеются моноблок ES607 и системный блок ED507`*.

## **Что ждет процессоры «Байкал»?**
**Процессоры «Байкал»** — это именно отечественная разработка, *пусть и на базе иностранных технологий*, но никак не выпуск. 
- Все актуальные модели производились на мощностях TSMC.

 - Однако в связи с недавними событиями тайваньская компания не просто разорвала контракт, но и не поставит в страну уже выпущенные процессоры. Это значит, что в распоряжении имеются лишь те небольшие партии, которые успели прийти в страну до наложения санкций.
 - Дополнительно ARM Limited отозвала лицензию на использование своих технологий.

Сами же разработчики заявляют, что имеющихся данных вполне достаточно для того, чтобы и дальше заниматься созданием версий **`M2 и S2`**, на которые *«Минпромторг» уже выделил средства*. Однако выпускать без производственных лицензий процессоры *не получится*. По крайне мере, без нарушения авторских прав.
Некоторые предлагают перейти на другую архитектуру, в частности, вернуться к MIPS или даже VLIW. Однако есть ли смысл возвращаться к MIPS и тем более переделывать все под VLIW, учитывая наличие «Эльбруса» — это интересные вопросы.

*Известно, что Baikal Electronics планирует выполнять корпусирование процессоров на мощностях холдинга GS* Group в Калининградской области. Однако кто будет заниматься именно производством — все еще не понятно.
Процессоры Baikal действительно могли стать массовым продуктом — разработчики уже подготавливали обширную экосистему, а первые образцы материнских плат и клиентских устройств даже были выпущены в небольших партиях. Однако в большей мере это заслуга именно ARM, поскольку российские инженеры уже использовали готовые ядра в своих процессорах. И если продолжать разработку новых моделей «Байкал» еще можно, даже, несмотря на отзыв лицензий, то с производством большие проблемы. 

- Однако разработка готового продукта пусть и на чужих технологиях — это бесценный опыт.

## **Используемые источники:**
 - Внутри российского процессора Байкал (https://habr.com/ru/articles/584868/)
 - Baikal - S (https://www.tadviser.ru/index.php/Продукт:Baikal-S)
 - Знакомство с российским ARM-процессором Байкал-М (https://www.ixbt.com/platform/baikal-m-pc-review.html)

