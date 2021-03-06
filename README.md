# Probability-theory-and-Math-statistics

Стек: python, jupyter notebook, scipy, matplotlib, seaborn

### Имеется датасет с средними ценами на авокадо и объемами продаж на нескольких рынках США.
Данный датасет взят с Kaggle.com (https://www.kaggle.com/neuromusic/avocado-prices).  
__Описание датасета:__ 
В датасете представлены еженедельные данные сканирования розничной торговли за 2018 год. Данные сканирования розничной торговли поступают непосредственно с кассовый аппаратов розничных продавцов, основанных на фактических розничных продажах авокадо Hass. Данные были выгружены с сайта Hass Avocado Board в мае 2018 года.

__Описание некоторых столбцов в наборе данных__  
Date - дата наблюдения  
AveragePrice - средняя цена одного авокадо  
type - тип: обычные (conventional) или органические (organic)   
year - год  
Region - город или регион наблюдения  
Total Volume - общее количество проданных авокадо  
4046 - общее количество проданных авокадо с кодом PLU 4046  
4225 - общее количество проданных авокадо с кодом PLU 4225  
4770 - общее количество проданных авокадо с кодом PLU 4770  

### Предполагаю, что средние цены на авокадо типов conventional и organic представляют собой две разные генеральных совокупности.
__Нулевая гипотеза:__ средние стоимости авокадо из групп conventional и organic принадлежат одной генеральной совокупности.   
__Альтернативная гипотиза:__ средние стоимости авокадо из групп conventional и organic принадлежат разным генеральным совокупностям.  
__Критерий:__ t-критерий  
__Уровень значимости:__ alpha=0.05  
__Критическая область:__ двухсторонняя
