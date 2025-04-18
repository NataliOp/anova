## A/B-тест маркетинговых кампаний для ресторана быстрого питания

### 📝 **Контекст проекта**

Сеть ресторанов быстрого питания проводит эксперимент для выбора лучшей маркетинговой кампании для нового продукта. В рамках A/B-теста три разные маркетинговые акции были протестированы в различных магазинах, где каждая акция использовалась в разных точках.

### 🎯 **Цель**

Оценить результаты A/B-тестирования для трех разных маркетинговых кампаний и определить, какая из них оказывает наибольшее влияние на объем продаж нового продукта.

## 🧩 **Описание данных**
Датасет содержит информацию о продажах нового продукта, полученную в ходе тестирования различных маркетинговых акций в разных точках на протяжении четырех недель.

| Название столбца | Описание |
|------------------|----------|
| MarketID         | Уникальный идентификатор магазина |
| MarketSize       | Размер рыночной площади по объемам продаж |
| LocationID       | Уникальный идентификатор местоположения магазина |
| AgeOfStore       | Возраст магазина в годах |
| Promotion        | Одна из трех протестированных акций |
| week             | Одна из четырех недель, когда проводились акции |
| SalesInThousands | Объем продаж для определенного LocationID, Promotion, week |

## 🔍 **Ход исследования**

1. Загрузка датасета

2. Разведочный анализ данных (EDA)

 * Анализ структуры данных
 * Визуализация
 * Работа с выбросами

3. Дисперсионный анализ (ANOVA)

4. Выводы

## 📦 **Технологический стек**

* Python: pandas, scipy, pingouin, matplotlib, seaborn
* Jupyter Notebook

## 🔗 **Источник данных**

Данные для анализа были взяты с платформы Kaggle:

[Fast Food Marketing Campaign A\B Test](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test)

*Данные использованы исключительно в образовательных и аналитических целях*
