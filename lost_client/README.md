# Прогнозирование оттока клиентов

## Описание
Оператор связи «ТелеДом» хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи, для этого нужно разработать модель, которая будет предсказывать, разорвёт ли абонент договор. 
## Используемые библиоткеи
* pandas
* numpy
* lightgbm
* phik
* seaborn
* sqlalchemy.create_engine
* sqlalchemy.text
* matplotlib.pyplot
* scipy.stats.boxcox
* scipy.stats.kruskal
* sklearn.preprocessing.PowerTransformer
* sklearn.model_selection.train_test_split 
* sklearn.model_selection.RandomizedSearchCV
* sklearn.model_selection.GridSearchCV
* sklearn.model_selection.KFold
* sklearn.pipeline.Pipeline
* sklearn.utils.class_weight.compute_class_weight
* sklearn.preprocessing.StandardScaler
* sklearn.preprocessing.OneHotEncoder
* sklearn.preprocessing.OrdinalEncoder
* sklearn.impute.SimpleImputer
* sklearn.compose.ColumnTransformer
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier
* sklearn.ensemble.VotingClassifier
* sklearn.tree.DecisionTreeClassifier
* sklearn.metrics.f1_score
* sklearn.metrics.roc_auc_score
* sklearn.metrics.accuracy_score
* sklearn.metrics.roc_curve
* sklearn.metrics.precision_recall_curve
* sklearn.metrics.precision_score
* sklearn.metrics.recall_score
* sklearn.metrics.confusion_matrix
* tensorflow.keras

## Общий вывод
Была разработана модель для опредления оттока клиентов, проведен исследовательский и статистический анализ, проверены гипотезы. Также была проведена проверка выбранной модели на тестовой выборке и проанализированы признаки влияющие больше всего
