Задача проекта научиться проводить разведывательный анализ данных.
Я проверил данные на качество, отсеял незаполненные строки.
Числовые столбцы исследовал на наличие выбросов и потом провел корреляционный анализ.
Оставил для модели все столбцы, т.к. они были слабо скоррелированы.
Построил бокс плоты для номинативных переменных, но они показали только что все переменные влияют на скор.
Тогда при помощи теста стьюдента нашел переменную, которая влияет на скор и добавил ее в модель.
Качество данных оставляет желать лучшего, но я считаю, что все равно с этими данными имеет смысл работать.