Мисуркин Павел.
 Pav2072@yandex.ru
Тестовое задание.
1.	По вашему - кто такой QA инженер?
QA инженер – это специалист, отвечающий за соответствие продукта техзаданию. Тот кто ищети анализирует ошибки, баги на всех стадиях разработки, в том числе и после выпуска.
2.	Что такое тестирование?
Тестированиеэто рабочий процесс направленный на выявление багов, ошибок и несоответствие текущего состояния продукта итоговой цели.
3.	Зачем вообще проводить проверку ПО?
Проверку ПО необходимо проводить для правильного функционирования проекта для пользователя.
Логическая задача:5 пиратов собираются разделить 100 золотых монет. Порядок пиратов определен – известно кто 1й 2й и так далее. По традиции пираты делят деньги следующим образом. 1й пират предлагает вариант деления денег. Все голосуют за или против этого варианта. Если голосов против более половины пирата убивают и следующий делит по тем же правилам. Когда дело касается денег каждый пират отлично умеют считать и поддержит предложенный вариант если он для него выгоднее чем альтернатива. Как 1му пирату получить максимально возможное количество денег и остаться в живых.
Ответ:В данной задаче первый пират зависит от решения о поддержке нижестоящех. Первый пират забирает 98 монет, второму 0, третьему 1 монету, четвертому 0, пятому 1 монету. При таком раскладе первого капитана не убьют, т.к. голосов против не будет больше половины от числа пиратов. Третий и пятый пират будут голосовать за решение первого, иначе они не получат ничего.

Задачи на тестирование:
1.	Как протестировать сломанный тостер?
Уточнить что именно сломано-что именно не должно работать при данной поломке.
Что именно он должен делать? Разогревать тосты? Соответственно он должен нагреваться до определенной температуры. Если сломан нагревательный элемент-соответственно нагрева тоста не происходит, либо происходит не достаточно быстро, либо с недостаточной температурой, (исходя из характеристик тостера желательно знать его рабочую температуру).
Изначально узнаем его характеристики:
Размер, Ш*В*Д, под какие размеры хлеба он подходит.
Максимальная/минимальная рабочая температура, есть ли ее регулировка.
Нагревается ли при работе тостера корпус, можно ли обжечься пользователю?
Если поломка кабеля питания-какая его длина, какая вилка? Из чего сделан провод, материал оплетки? Соттветствует ли вилка местным стандартам? (если влка для другой страны-то не будет питания тостера, соответственно о не работает.
2.	В приложении к тестовому заданию вы найдете 2 скриншота - реальное приложение (приложение №1) и макет (приложение №2). Найдите ошибки при реализации. Опционально - дайте рекомендации по улучшению.
В релизе указано понятие доставка карты и доставим карту, что указывает что процесс доставки еще происходит, значит клиенту нужно  ждать, не указано что нужно иметь при себе карту. Завершающая кнопка-закрыть.
В макете указано карта готова/карту можно забрать, что указывает что действие завершено и клиенту можно идти по адресу и забрать карту, имея при себе паспорт.
Завершающая кнопка – готово. В макете не указан город.
Рекомендации – исправить сообщение на карта готова и карту можно забрать, а также уточнить адрес, что не указано в макете (город/населенный пункт).

3.	 Вам передали на тестирование калькулятор и список проверок к нему, которые написал предыдущий QA. Требования описаны чуть ниже. Ваша задача - проверить корректность этих проверок
1)Ожидаемый результат и фактический не соответствует результатам тестовых данныйх 1+1+1, реальный и ожидаемый ответ должен быть «3 (три)»
4)Ожидаемый результат не корректен. Ответ 375 (триста семьдесят пять)
5)Кулькулятор не правильно округлил дробь, правильный ответ 0,17143
6) Согласно техзаданию- задача должна прописываться либо полностью словами, либо полностью цыфрами, правильно было бы прописать –«-1+1» или «минус один плюс один»
7) Согласно техзаданию- задача должна прописываться либо полностью словами, либо полностью цифрами, правильно было бы прописать –«триста четырнадцать минус четырнадцать» или «314-14». Фактический результат не корректен.
8) Не указаны 5 знаков после запятой
