# OfficePricingArticle

В данном репозитории представлены файлы, с помощью которых проводилось обучение и оценка моделей стоимости аренды офисов, рассмотренных в статье.

Файл
- ModelWObjsV1_6.ipynb 
содержат обучение общих моделей (Catboost, линейная) для всех классов.
Файлы
- ModelWObjsV1_6_ClassA.ipynb
- ModelWObjsV1_6_ClassB.ipynb
- ModelWObjsV1_6_ClassC.ipynb
содержат обучение моделей (Catboost, линейная) для отдельных классов. 
Из этих моделей всегда удалялся признак класса офиса, в остальном - набор признаков совпадает

Файлы
- MakeShapEstimationGeneral.ipynb
- MakeShapEstimationClassA.ipynb
- MakeShapEstimationClassB.ipynb
- MakeShapEstimationClassC.ipynb
содержат построение SHAP value и соответствующих графиков для модели Catboost.

Файл с собранным датасетом можно найти по ссылке
https://disk.yandex.ru/d/e4ISRNTb7u4GHw

По всем вопросам писать Дмитрию Демину на почту
dmitriy.demin.98@mail.ru
