# Описание
Строится модель прогнозирования отказа от брони клиента. В качестве метрики используется величина выручки, которая получится после внедрения модели машинного обучения.

## Используемые инструменты
pandas
matplotlib
numpy
seaborn
cipy.stats
statsmodels.api
sklearn.model_selection.train_test_split
sklearn.preprocessing.OneHotEncoder
sklearn.utils.shuffle
sklearn.tree.DecisionTreeClassifier
sklearn.metrics.accuracy_score
sklearn.metrics.f1_score
sklearn.metrics.precision_score
sklearn.metrics.recall_score
sklearn.metrics.accuracy_score
sklearn.metrics.roc_curve
sklearn.metrics.roc_auc_score
sklearn.metrics.recall_score
sklearn.ensemble.RandomForestClassifier
sklearn.linear_model.LogisticRegression
sklearn.model_selection.cross_val_score
sklearn.preprocessing.StandardScaler
sklearn.pipeline.Pipeline
sklearn.pipeline.make_pipeline
sklearn.model_selection.GridSearchCV
sklearn.model_selection.RandomizedSearchCV
imblearn.over_sampling.SMOTE
imblearn.pipeline.Pipeline
imblearn.pipeline.make_pipeline
sklearn.preprocessing. OrdinalEncoder

## Общий вывод
Была построена модель для прогнозирования отказа клиента от брони, выявлен портрет "идеального" клиента, состоятельнойсть
модели была проверена импользуя величину выручки после внедрения модели
