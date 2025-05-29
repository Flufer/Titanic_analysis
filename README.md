# 🚢 Titanic Survival Prediction Project

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/600px-RMS_Titanic_3.jpg)

Анализ выживаемости пассажиров Титаника с использованием машинного обучения.

## 🔍 **Описание проекта**
- **Датасет**: [Titanic from Kaggle](https://www.kaggle.com/c/titanic/data)
- **Задача**: Бинарная классификация (выжил/погиб)
- **Методы**:
  - Предобработка данных (заполнение пропусков, кодирование категорий)
  - Логистическая регрессия
  - Случайный лес
  - Оценка через ROC-AUC и матрицу ошибок

## 📊 **Результаты**
| Модель               | Accuracy | ROC-AUC |
|----------------------|----------|---------|
| Логистическая регрессия | 0.81     | 0.88    |
| Случайный лес        | 0.82     | 0.89    |

## 🛠 **Требования**
- Python 3.9+
- Библиотеки: `numpy`,`pandas`, `scikit-learn`, `matplotlib`, `seaborn`

## ▶ **Как запустить**
1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/Flufer/Titanic_analysis.git