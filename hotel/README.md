# Данные
Описание данных
В таблицах hotel_train и hotel_test содержатся одинаковые столбцы:<br>
id — номер записи;<br>
adults — количество взрослых постояльцев;<br>
arrival_date_year — год заезда;<br>
arrival_date_month — месяц заезда;<br>
arrival_date_week_number — неделя заезда;<br>
arrival_date_day_of_month — день заезда;<br>
babies — количество младенцев;<br>
booking_changes — количество изменений параметров заказа;<br>
children — количество детей от 3 до 14 лет;<br>
country — гражданство постояльца;<br>
customer_type — тип заказчика:<br>
    1. Contract — договор с юридическим лицом;<br>
    2. Group — групповой заезд;<br>
    3. Transient — не связано с договором или групповым заездом;<br>
  Transient-party — не связано с договором или групповым заездом, но связано с бронированием типа Transient.<br>
days_in_waiting_list — сколько дней заказ ожидал подтверждения;<br>
distribution_channel — канал дистрибуции заказа;<br>
is_canceled — отмена заказа;<br>
is_repeated_guest — признак того, что гость бронирует номер второй раз;<br>
lead_time — количество дней между датой бронирования и датой прибытия;<br>
meal — опции заказа:<br>
    1. SC — нет дополнительных опций;<br>
    2. BB — включён завтрак;<br>
    3. HB — включён завтрак и обед;<br>
    4. FB — включён завтрак, обед и ужин.<br>
previous_bookings_not_canceled — количество подтверждённых заказов у клиента;<br>
previous_cancellations — количество отменённых заказов у клиента;<br>
required_car_parking_spaces — необходимость места для автомобиля;<br>
reserved_room_type — тип забронированной комнаты;<br>
stays_in_weekend_nights — количество ночей в выходные дни;<br>
stays_in_week_nights — количество ночей в будние дни;<br>
total_nights — общее количество ночей;<br>
total_of_special_requests — количество специальных отметок.<br>


## Задачи
1. Выполнить предобработку данных
2. Провести исследовательский анализ данных
3. Вычислить бизнес-метрику
4. Разработка модели ML
5. cпрогнозировать кто из клиентов откажется от брони

## Используемые библиотеки
*pandas, matplotlib, numpy, scipy, statsmodel, seaborn, sklearn, imblearn*
