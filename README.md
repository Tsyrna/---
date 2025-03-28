# Декоративно-прикладное искусство в музеях пяти крупнейших городов России
Датафрейм содержит информацию о предметах декоративно-прикладного искусства в музеях в пяти крупнейших городах России
## Тема проекта
Анализ представленности декоративно-прикладного искусства (фарфор, куклы, посуда, статуэтки) в музеях России на основе данных Госкаталога Минкультуры РФ
## Цель исследования
Изучить распределение предметов декоративно-прикладного искусства (фарфор, куклы, посуда, статуэтки) по музеям России, выявить регионы и музеи с наибольшим количеством таких экспонатов, а также проанализировать их временные периоды создания.
## Процесс работы по этапам
### 1. Получение данных
Я получала данные через API Минкультуры РФ, это источник со свободной лицензией (https://opendata.mkrf.ru/opendata)
После получения данных я сохранила их в **единый датафрейм** и в формат **CSV**.
### 2. Разведочный анализ
С помощью сводных таблиц и различных функций, я смогла сделать следующие выводы:  
**Количество предметов по городам:** больше всего предметов декоративно-прикладного искусства содержится в Санкт-Петербурге, меньше всего - в Казани  
**Количество предметов по типу предмета:** наиболее популярной категорией предметов декоративно-прикладного искусства является фарфор, наименее популярной - посуда  
**Количество предметов по городам и типам:** С помощью этой сводной таблицы я смогла посмотреть как распределись предметы декоративно-прикладного искусства по этим пяти городам  
**Анализ временных периодов (для предметов с датами)**: Предметов с указанием даты: 3318, Самая ранняя дата: 0001-01-01T12:00:00.000Z, Самая поздняя дата: 2022-01-01T12:00:00.000Z  
**Анализ возраста предметов** (среднее, медианное, минимальное и максимальное значение для каждого типа): статуэтки и фарфор оказались "старше" посуды и кукл, средний возраст предметов, связанных с фарфором - примено 134 года  
**Анализ распределения предметов по векам/эпохам**: больше всего экспонатов декоративно-прикладного искусства относятся в 20 веку, менее всего - к 18
### Визуализация данных
1. Бар-чарт: Топ-5 городов по количеству музейных предметов  
2. Круговая диаграмма: Распределение предметов по городам  
3. Бар-чарт: Распределение музейных предметов по типам  
4. Бар-плот: Топ-10 музеев по количеству предметов  
5. Линейный график: Анализ по годам регистрации экспонатов  

## Общий вывод и результаты
### 1. Основные результаты анализа
**Распределение предметов по городам**
  **Санкт-Петербург** лидирует по количеству экспонатов (**2885** предметов), что может быть связано с исторической ролью города как культурной          столицы России.  
  **Москва** занимает второе место (1591 предмет), что отражает её статус главного музейного центра страны.  
  **Новосибирск, Екатеринбург и Казань** имеют значительно меньше предметов (680, 270 и 19 соответственно), что может указывать на неравномерное           распределение культурного наследия по регионам.  
  
**Распределение по типам предметов**  
  **Фарфор** (**1970** предметов) — самый распространённый вид декоративно-прикладного искусства, что объясняется его исторической ценностью и           долговечностью.  
  **Куклы** (**1658** предметов) и статуэтки (1229 предметов) также широко представлены, что может быть связано с их популярностью в дворцовых и         частных коллекциях.  
  **Посуда** (**588** предметов) встречается реже, возможно, из-за её утилитарного назначения и меньшей сохранности.  
  
**Возраст предметов**  
  **Фарфор** — самый «старый» (средний возраст ~134 года), что подтверждает его долгую историю производства в России.  
  **Статуэтки** (~99 лет) и посуда (~117 лет) также относятся к XIX – началу XX века.  
  **Куклы** (~63 года) — самые «молодые», что может быть связано с их активным коллекционированием в советский период.  
  
**Распределение по векам**  
  **XX век** — большинство экспонатов, что объясняется лучшей сохранностью предметов этого периода.  
  **XIX век** — значительное количество, особенно фарфора и статуэток.  
  **XVIII век** — наименьшее количество, вероятно, из-за естественного износа и исторических потрясений.  
  
### 2. Выводы
**Культурное неравенство регионов:**  
Санкт-Петербург и Москва значительно опережают другие города по количеству экспонатов, что отражает их историческую роль в сохранении искусства.  
Региональные музеи (Казань, Новосибирск, Екатеринбург) нуждаются в дополнительном изучении и, возможно, поддержке для пополнения коллекций.  
  
**Популярность фарфора:**  
Фарфор доминирует в коллекциях, что подтверждает его культурную и историческую значимость для России.  
  
**Сохранность предметов**  
Чем старше предмет, тем реже он встречается в коллекциях (особенно XVIII век). Это может быть связано с войнами, революциями и естественным разрушением.  
  
Этот проект демонстрирует, как открытые данные (Госкаталог Минкультуры) могут быть использованы для анализа культурного наследия. Результаты могут быть полезны музеям, историкам и культурологам.
