# ML-_in_business_project-
Итоговый проект по курсу "Машинное обучение в бизнесе"

Стек: sklearn, numpy, pandas, xgboost, API: flask

Данные: https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction

Задача:  Бинарная классификация: предсказать удовлетворенность пассажира сервисом авиакомпании по данным опроса.

Преобразование признаков: QuantileTransformer, One Hot Encoding

Для запуска:

Запусть Flask-приложение: run_server.py
Использовать функцию get_prediction из get_predictions.py для получения предсказанных значений

Функция get_prediction: принимает на вход pandas-dataframe.Возвращает json-объект со списком предсказанных значений,следующего типа 'str': 'satisfied'/'neutral or dissatisfied'.

Поддирректории:

'datasets/' - содержит данные в формате .csv (train и test)
'models/' - содержит предобученную модель в формате .dill
'notebooks/' - содержит блокноты Jupyter Noutbook с этапами создания модели классификации