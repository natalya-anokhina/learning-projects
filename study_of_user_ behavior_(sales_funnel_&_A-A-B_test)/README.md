# Исследование поведения пользователей мобильного приложения

## Данные
В наличии данные о действиях пользователей в мобильном приложении стартапа, который продает продукты питания:

-  название события;
- уникальный идентификатор пользователя;
- время события;
- номер эксперимента: 246 и 247 — контрольные группы, 248 — экспериментальная.


## Задача
Изучить воронку продаж. 

Исследовать результаты A/A/B-эксперимента о замене шрифтов в приложении.

Проверить гипотезы:  
- О равенстве долей уникальных пользователей, совершивших определенное событие, контрольной группы 246 и контрольной группы 247;
- О равенстве долей уникальных пользователей, совершивших определенное событие, контрольной группы 246 и тестовой группы 248;
- О равенстве долей уникальных пользователей, совершивших определенное событие, контрольной группы 247 и тестовой группы 248;
- О равенстве долей уникальных пользователей, совершивших определенное событие, объединенной контрольной группы (246+247) и тестовой группы 248;

## Используемые библиотеки

pandas, numpy, scipy, datetime, math, matplotlib, seaborn, plotly