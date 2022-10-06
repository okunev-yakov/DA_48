# Яндекс.Практикум<br>
## Специализация: Аналитик данных.<br>
### Курс: Основы машинного обучения.<br>
### Проект № 03-02.<br>
### Название: Подготовка плана действий по удержанию клиентов фитнес-центра.<br>

**ЦЕЛЬ ИССЛЕДОВАНИЯ** — на основе таблицы данных по клиентам необходимо:<br>
А) Спрогнозировать вероятность оттока для каждого клиента,<br>
Б) Сформировать типичные портреты клиентов и основные признаки, наиболее сильно влияющие на отток,<br>
В) Разработать рекомендации по повышению качества работы с клиентами:<br>
1) выделить целевые группы клиентов<br>
2) предложить меры по снижению оттока<br>

**ФОРМИРУЕМЫЕ НАВЫКИ**:<br>
1) Проведение исследовательского анализа данных (exploratory data analysis, EDA).<br>
2) Построение моделей прогнозирования, оценка и сравнение метрик моделей.<br>
3) Кластеризация клиентов.<br> 

**ПРИМЕНЯЕМЫЕ БИБЛИОТЕКИ PYTHON**:<br>
import itertools<br>
from sklearn.cluster import KMeans<br>
from sklearn.preprocessing import StandardScaler<br>
from sklearn.model_selection import train_test_split<br>
from sklearn.linear_model import Lasso, Ridge, LogisticRegression<br>
from sklearn.ensemble import RandomForestRegressor, GradientBoostingRegressor, RandomForestClassifier<br>
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score, roc_auc_score, mean_absolute_error, mean_squared_error, r2_score<br>
from scipy.cluster.hierarchy import dendrogram, linkage<br>

**НЕКОТОРЫЕ ПРИМЕНЯЕМЫЕ КОМАНДЫ, ФУНКЦИИ**:<br>
scaler.fit_transform(X_train)<br> 
LogisticRegression(solver = 'liblinear', random_state = 0)<br>
RandomForestClassifier(n_estimators = 100, random_state = 0)<br>