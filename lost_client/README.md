# Прогнозирование цены квартиры

## Описание
Сервис по продаже квартир закала разработку модели по прогнозированию стоимости квартиры 
## Используемые библиоткеи
pandas as pd
numpy as np
sqlalchemy.create_engine
sqlalchemy.text
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import boxcox, kruskal
import phik
from sklearn.preprocessing import PowerTransformer
from sklearn.model_selection import train_test_split, RandomizedSearchCV, GridSearchCV, KFold
from sklearn.pipeline import Pipeline
from sklearn.utils.class_weight import compute_class_weight
from sklearn.preprocessing import StandardScaler, OneHotEncoder, OrdinalEncoder
from sklearn.impute import SimpleImputer
from sklearn.compose import ColumnTransformer
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier, VotingClassifier
from sklearn.tree import DecisionTreeClassifier
import lightgbm as lgbm
from sklearn.metrics import f1_score, roc_auc_score, accuracy_score, roc_curve
from sklearn.metrics import precision_recall_curve, precision_score, recall_score, confusion_matrix
from tensorflow import keras

## Общий вывод
Была разработана модель линейной регрессии для опредления медианной стоимости квартиры с использованием
pyspark, также была проведена проверка выбранной модели на тестовой выборке
