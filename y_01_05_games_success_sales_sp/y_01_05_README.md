### Тема: сборный проект - 1.<br>
### Проект № 01-05 (сборный проект первого модуля).<br>
### Название: Выявление закономерностей, определяющих успешность игры.<br>

**ЦЕЛЬ ИССЛЕДОВАНИЯ** — на основе данных о продажах игр, оценках пользователей и экспертов, жанрах и платформах необходимо выявить определяющие успешность игры закономерности. Для этого требуется:<br>
1) Дать оценку всем играм по выпуску, объемам продаж, платформам, отзывам и жанрам<br>
2) Составить портрет пользователя каждого региона<br>
3) Проверить гипотезы о средних пользовательских рейтингах:<br>
3.1  о равенстве средних пользовательских рейтингов платформ Xbox One и PC для периода 2014...2016гг.<br>
3.2  о неравенстве средних пользовательских рейтингов жанров Action и Sports для периода 2014...2016гг.<br>

**ФОРМИРУЕМЫЕ НАВЫКИ**:<br>
1) Расчет матрицы корреляции.<br>
2) Построение линейных графиков, диаграмм размаха, круговых диаграмм и диаграмм размаха.<br>
3) Формулирование и проверка гипотез Н_0 и Н_1.<br>

**ПРИМЕНЯЕМЫЕ БИБЛИОТЕКИ PYTHON**:<br>
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import warnings
from scipy import stats as st

**НЕКОТОРЫЕ ПРИМЕНЯЕМЫЕ КОМАНДЫ, ФУНКЦИИ**:<br>
.corr(...)
.query('... == "..."')
fig, axes = plt.subplots(nrows=..., ncols=..., figsize=(..., ...))
np.std(..., ddof=1)