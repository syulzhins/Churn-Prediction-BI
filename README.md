# Анализ оттока клиентов (Churn Prediction)

**BI-проект:** Исследование причин оттока, когортный анализ, LTV, предсказательная модель и рекомендации по удержанию клиентов.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 🎯 Цель проекта

Выявить основные причины оттока клиентов, построить модель предсказания оттока, рассчитать ключевые метрики (Retention, LTV) и разработать рекомендации по удержанию клиентов.

## 📋 Бизнес-задача

- Почему клиенты уходят?
- Какие сегменты наиболее подвержены оттоку?
- Какой потенциальный финансовый ущерб от оттока?
- Как можно снизить отток?

## 🛠 Технологии

- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Анализ**: EDA, когортный анализ, LTV, A/B-тестирование
- **Моделирование**: Logistic Regression

## 📊 Ключевые метрики

- Доля оттока
- Retention Rate
- LTV (Lifetime Value)
- Accuracy модели предсказания оттока

## 📁 Структура проекта

```
Churn-Prediction/
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Churn_Analysis.ipynb
├── README.md


## 🚀 Как запустить

```bash
git clone https://github.com/syulzhins/Churn-Prediction.git
cd Churn-Prediction
jupyter notebook Churn_Analysis.ipynb
```

## 💡 Основные insights

- Самый высокий отток у клиентов с помесячной оплатой
- Клиенты с Fiber optic уходят чаще
- Пенсионеры (SeniorCitizen) имеют повышенный риск оттока
- Модель предсказания оттока показывает хорошую точность

## 📌 Бизнес-рекомендации

- Стимулировать переход на годовые контракты (скидки, бонусы)
- Улучшить качество и поддержку Fiber optic
- Разработать специальные программы удержания для пенсионеров
- Внедрить систему раннего предупреждения оттока

---

