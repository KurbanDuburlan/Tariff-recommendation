# Рекомендация тарифов
## Описание: 
У меня есть данные о поведении клиентов, которые уже перешли на эти тарифы. Моя задача заключается в построении модели для задачи классификации, которая будет определять подходящий тариф. Предобработку данных мне делать не потребуется, так как она уже выполнена.
## Стэк: 
python, pandas, numpy, sklearn
## Цель: 
Построение модели классификации для определения подходящего тарифа на основе данных о поведении клиентов оператора связи.
## Вывод: 
Проект включал решение задачи классификации клиентов мобильного оператора на тарифы "Смарт" и "Ультра". В ходе работы был проведен анализ данных, заполнены пропущенные значения и выполнена предобработка. Далее данные были разделены на обучающую, валидационную и тестовую выборки.

Были построены и исследованы три модели: дерево решений, случайный лес и логистическая регрессия. Наилучший результат достигнут с использованием моделей случайного леса и дерева решений, с метрикой accuracy на тестовой выборке в 79,1 %, превышая необходимую точность в 75%.

Проверка модели на адекватность подтвердила, что она превосходит случайное угадывание.

Итак, модель случайного леса и дерева решений является оптимальной для данной задачи, позволяя классифицировать новых клиентов на тарифы "Смарт" и "Ультра" с высокой точностью.
