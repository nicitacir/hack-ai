# **Классификация агрокультур на основе изменения показателя вегетационных индексов во временной последовательности(всероссийский чемпионат г. Иннополис - цифровой прорыв 2022г.** 

**Цель:** 
* Классификация агрокультур. Метрика - Recall



**Стек:** 
* pandas 
* numpy 
* CatBoost
* seaborn
* LogisticRegression

**Результат:** 
 Для классификация агрокультур 
 
1 - Отобрали/отсортировали основные признаки, которые должны влиять на классификацию агрокультур. 

2 - Обучили модели и раасмотрели несколько вариантов улучшения(нормализация данных, усреднение пропусков на данных соседних столбцов, модель с меньшим количеством признаков(отсекли менее важные)

3 - На основании лучшей(случайный лес/Catboost с полным набором признаком с учетом сортировки по дате) построили предсказания на основании признаково тестового датасета
