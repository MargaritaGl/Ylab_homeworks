1. Магазин принимает накопительные скидочные карты и при своем расчете учитывает количество баллов, по которому начисляет процент скидки:
От 0 до 100 баллов - скидка 1% От 101 до 500 баллов - скидка 3 % От 500 до 2000 баллов - скидка 5% От 2001 баллов - скидка 10%
Задание: Составить такой набор тестовых данных для магазина (в формате количество баллов - ожидаемая скидка),
при котором мы будем знать, что в соответствии со своими накопленными баллами покупатель получит верную скидку.

            Необходимо уточнить возможно ли сохранение на карте отрицательного числа (подразумевает ли хранение отрицательных чисел формат данных, используемый для хранения баллов). 
            Если да, то проверить отрицательное количество баллов (которое возможно можно получить в реальной работе при ошибке системы расчета баллов). Ожидаемый результат при этом - запись на карту 0 баллов и скидка 1 % 
            0 баллов - скидка 1%
            1 балл - скидка 1% 
            99 баллов - скидка 1%
            100 баллов - скидка 1%
            101 балл - скидка 3%
            102 балла - скидка 3%
            499 баллов - скидка 3%
            500 баллов - скидка 3%
            501 балл - скидка 5% (необходимо уточнение требований, в какой промежуток входит 500. По предыдущим данным и логике до точного выяснения требований отнесем 500 в предыдущий интервал и примем нижнию границу скидки в 5%  501 балл)
            502 балла - скидка 5%
            1999 баллов - скидка 5%
            2000 баллов - скидка 5%
            2001 балл - скидка 10%
            2002 балла - скидка 10%
            Далее необходима проверка при максимальном возможном значении баллов и меньше него на 1.
            Так же неообходима проверка максимального количества баллов + 1, при которой должна подразумеваться корректная обработка,
            например выставление значения максимального возможного количества баллов вместо ошибочного и скидка в 10%. Необходимо уточнить максимальное количество баллов.

3. Наш сайт представлен на двух языках: русский (RU) и английский (EN).
Из требований следует, что сайт будет открываться в браузерах Opera и Firefox на операционных системах Windows 10 и Ubuntu 20.04,
а также на устройствах с операционной системой Android 10 в браузере Chrome.
Задание: Укажите минимальный набор конфигураций (браузер, ОС, язык сайта), который вы бы использовали для тестирования данного сайта.

            Для выполнения этого задания использовался pairwise tool.
<table>
  <tr>
    <th>Браузер</th>
    <th>ОС</th>
    <th>Язык сайта</th>
  </tr>
  <tr>
    <td>Opera</td>
    <td>Windows 10</td>
    <td>русский (RU)</td>
  </tr> 
  <tr>
    <td>Opera</td>
    <td>Ubuntu 20.04</td>
    <td>английский (EN)</td>
  </tr>  
  <tr>
    <td>Firefox</td>
    <td>Ubuntu 20.04</td>
    <td>русский (RU)</td>
  </tr>  
  <tr>
    <td>Firefox</td>
    <td>Windows 10</td>
    <td>английский (EN)</td>
  </tr>   
  <tr>
    <td>Chrome</td>
    <td>Android 10</td>
    <td>русский (RU)</td>
  </tr> 
  <tr>
    <td>Chrome</td>
    <td>Android 10</td>
    <td>английский (EN)</td>
  </tr> 
</table>

3. Ответьте на вопросы:
- Какой категории ui-элементов относится данный элемент? (см. доп. материалы) 

Навигационный блок для пагинации (постраничный вывод данных), включающий кнопки Назад и Вперед.

- Приведите пример - ui-элемента из категории Input Controls.

Поле ввода информации о себе, чек-бокс для выбора стран направления при бронировании билетов, выпадающий список для выбора интервалов времени, доступных при заказе звонка.

- Является ли командная строка частью GUI?

Нет, командная строка часть GUI не является.

4. Какой тип мобильного приложения не имеет доступа к внутреннему функционалу смартфона, например пушам?

Web приложения не имеют доступ к внутреннему функционалу смартфона.
