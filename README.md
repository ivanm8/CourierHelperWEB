# Описание
**CourierHelper** – программное обеспечение, которое состоит из **web-приложения для менеджера курьеров** и **Anadroid-приложения для курьеров**.

### Как работает web-приложение
   1. менеджер импортирует доставки (из exel-файла или sql)
   2. CourierHelper для каждой доставки определяет
      * административный округ
      * район
      * две ближайшие станции метро и расстояния до них
   3. CourierHelper максимально удобно сортирует доставки внутри каждого административного округа сначала по районам, а затем по времени доставки
   4. менеджер назначает курьеров отсортированным доставкам
   5. CourierHelper отправляет эти доставки курьерам на Android-устройства

Как выглядят сортированные доставки (3-ий пункт):
![отсортированные доставки](https://courierhelper.ru/img/sorteddeliveries.png)

### Возможности мобильного приложения для Android
   * звонок клиенту в один клик
   * sms клиенту в один клик
   * sms сразу всем клиентам в один клик
   * два шаблона sms, редактируемые в настройках
   * все доставки на одной карте
   * кошелёк для упрощения сдачи кассы
   * ведение статистики каждого курьера

# Для продолжения пройдите в нашу [wiki](https://github.com/ivan8m8/CourierHelperWEB/wiki)
