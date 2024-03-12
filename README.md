# weather_forecast_cities_ana analysis
Прогноз погоды через парсинг данных Яндекс погоды на неделю вперёд + анализ данных для городов, находящихся на одной широте

Предварительно подготовили необходимые данные для анализа:

* в excel создали список городов, которые будем рассматривать в анном анализе, с данными по широте и долготе





* загрузили данный список в наш анализ
![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/8b5e0f72-20db-4004-a361-6a0ac04127a2)



Создали список названий дней недели, используемых на сайте яндекс.погоды

![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/0dea25b9-9a56-46cf-a83e-b69f2f71503d)


Вытащили данные с сайтя Яндекс.погоды
![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/d3bed30c-02d6-46c1-892f-933c83ffcf86)

Выгрузили данные по погоде по интересующим нас городам
![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/56e5d7a8-9b56-4d0c-9dad-fda604114f5f)

Посмотрели динамику изменения данных по дневной температуре для городов мира, находящихся примерно на одной широте.
* Для этого визуализировали карту при помощи библиотеки folium (построили карту для отображения нашей выборки городов, привязав к их координатам)
![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/73b7c8c2-00d7-4869-9dfe-843e23452030)

* и посмотрели интересующие нас погодные показатели
![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/81316bfd-5d2e-4657-bc3f-561fe4f0490a)
![image](https://github.com/PaslenAmari/weather_forecast_cities_and_analysis/assets/106679149/ab3c39f5-7740-41cd-869c-3cccbb8861a5)

Выводы:

После визуализации наших данных, наглядно видно, что для городов, находящихся примерно на одной широте, разброс как дневных температур, так и ночных, достаточно высок.


Более стабильный разброс прогнозируемых дневных температур для ближайшей недели, судя по графику, характерен для центральных районов (Измир, Палермо, Лиссабон) исследуемой широты.

Более плавное изменение прогнозируемых ночных температур характерно для Ашхабада.
