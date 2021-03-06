## Используемые наборы данных

Для данной лабораторной работы я решил выбрать два табличных датасета на задачу бинарной классификации. Один датасет взят с популярного соревнования -- анонимизированные данные пользователей для задачи прогнозирования кредитов банковских клиентов. Другим набором данных послужили харакетристики грибов на ядовитость.

## Визуализация

Используемые библиотеки: matplotlib, seaborn.
Для датасета задачи кредитного риска были построены pairplot, так как в силу того, что признаки анонимизированы, достаточно сложно понять их смысл. Благодаря данной визуализации можно выяснить природу данных и при особой сноровке даже вычленить суть.

## Работа с данными

В ходе работы были разрешены проблемы пропуска в данных, работы с категориальными признаками.

В одном датасете пришлось разобраться с проблемой пропусков в данных. В каждой из задач релевантные категориальные признаки были преобразованы с помощью OneHotEncoding, а численные были нормализованы, так как это необходимая составляющая для линейной модели. От некоторых признаков, смысл которых не очень ясен, я решил и вовсе избавиться. Также были сгенирированы новые признаки для одной из задач.

При выполнении визуализаций одного датасета я научился работать с категориальными признаками (смотреть как категории влияют на целевую переменную), а при работе с другим датасетом -- с числовыми признаками. Эти действия помогут нагенерировать новые признаки, если мы захотим добиться лучшего качества наших моделей, но для учебных целей это не является необходимым.
