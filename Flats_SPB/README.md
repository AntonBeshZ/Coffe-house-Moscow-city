# Исследование объявлений о продаже квартир

**Цель исследования:**<br>
Определить рыночную стоимость объектов недвижимости. А также какие параметры в объявлении, влияют на цену объектов.<br>

Входные данные - данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. 
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных.<br>

**Выводы:**<br>
Установил параметры, влияющие на цену объектов. На стоимость больше всего влияют: 
общая и жилая площади, чем они больше, тем дороже квартира соответственно. Также влияют такие параметры как: 
тип этажа - квартиры не на первом и не на последнем этажах дороже, год размещения объявления - в 2014 году была самая дорогая недвижимость.
Выяснил, что по длительности продажа квартир обычно происходит в диапазоне 40 - 100 дней. Сделки менее 40 дней можно считать быстрой продажей, 
а более 600 дней, т.е. почти 2 года, уже необычно долгой продажей.

Дополнительно выяснил, что самая дорогая цена квадратного метра в Санкт-Петербурге, а самая дешевая - в Выборге.
Также узнал среднюю стоимость квартир при удалении от центра: в целом наблюдается снижение стоимости при удалении от центра, за исключением 
нескольких всплесков в районе 4-5 км, 20 км и 27 км. Вероятно, в этих районах располагаются элитные районы и населенные пункты.

Исследование позволяет построить автоматизированную систему, которая отследит аномалии и мошенническую деятельность.
