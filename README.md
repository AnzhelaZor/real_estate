# Оценка стоимости недвижмости

## Суть данной работы в сравнении методов отбора признаков, а именно, фильтры (корреляция) и встроенный метод (случайный лес). Так же спрогнозированы стоимости для жилой недвижимости.

Анализ работы проведен в фале "анализ.docx"
Используется отбор корреляцией и линейная регрессия в файле (correlation_linearregression) и случайный лес в фале (randomforest).

В данных содержится 22 признака и 23699 строк.
Признаки: 
•	airports_nearest — расстояние до ближайшего аэропорта (м) 
•	balcony — количество балконов 
•	ceiling_height — высота потолков (м) 
•	cityCenters_nearest — расстояние до центра города (м) 
•	days_exposition — сколько дней было размещено объявление
•	first_day_exposition — дата публикации 
•	floor — этаж 
•	floors_total — количество этажей в доме 
•	is_apartment — апартаменты (True, False) 
•	kitchen_area — площадь кухни (м²) 
•	last_price — цена 
•	living_area — жилая площадь (м²) 
•	locality_name — название населённого пункта 
•	open_plan — свободная планировка (True, False) 
•	parks_around3000 — количество парков в радиусе 3 км 
•	parks_nearest — расстояние до ближайшего парка (м) 
•	ponds_around3000 — количество водоёмов в радиусе 3 км 
•	ponds_nearest — расстояние до ближайшего водоёма (м) 
•	rooms — число комнат 
•	studio — квартира-студия (True, False) 
•	total_area — площадь квартиры (м²) 
•	total_images — количество фотографий квартиры в объявлении
