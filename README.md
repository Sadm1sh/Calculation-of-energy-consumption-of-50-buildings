# Calculation-of-energy-consumption-of-50-buildings
# Расчёт энергопотребления для 50 зданий
## Задача
Загрузить данные и посчитать модели линейной регрессии для 50 зданий по ансамблю регрессионных моделей: в первой модели весь оптимальный набор метеорологических данных, во второй - дни недели и праздники, в третьей - недели года, в четвертой - месяцы. Финальное значение показателя рассчитать как взвешенное арифметическое показателей всех моделей, взяв веса для первой и второй модели как 3/8, а для третьей и четвертой - как 1/8.

Загрузить данные решения, посчитайте значение энергопотребления для требуемых дат для тех зданий, которые посчитаны в модели, и выгрузите результат в виде CSV-файла (submission.csv).

Данные:
* [Данные по зданиям](http://video.ittensive.com/machine-learning/ashrae/building_metadata.csv.gz)
* [Обучающие данные по погоде](http://video.ittensive.com/machine-learning/ashrae/weather_train.csv.gz)
* [Обучающие данные по энергопотреблению](http://video.ittensive.com/machine-learning/ashrae/train.0.csv.gz)
* [Данные для расчётов](http://video.ittensive.com/machine-learning/ashrae/test.csv.gz)
* [Данные по погоде для расчётов](http://video.ittensive.com/machine-learning/ashrae/weather_test.csv.gz)
