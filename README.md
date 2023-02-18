# IncomePredictionRBGroup1
Проект по прогнозу дохода. Группа 1

----------------------------------------------------------------
Прогноз дохода

Задача состоит в том, чтобы по различным характеристикам людей спрогнозировать целевую переменную - уровень дохода людей (два варианта дохода: больше 50 тысяч или меньше).

Описание признаков клиентов:
- Целевая переменная - зарплата больше или меньше 50К income: >50K, <=50K
- age: количество полных лет.
- workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked. 
- fnlwgt: continuous. 
- education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool. 
- education-num: continuous. 
- marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse. 
- occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces. 
- relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried. 
- race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. 
- gender: Female, Male. 
- capital-gain: continuous. 
- capital-loss: continuous. 
- hours-per-week: continuous. 
- native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. 

Для некоторых числовых (continuous) характеристик в датасете нет полного описания.
----------------------------------------------------------------

Дедлайны:
* 21 февраля 10:00 - необходимо сделать разведочный анализ и обучить логистическую регрессию для решения вашей задачи (по материалам занятия 4)
* 25 февраля - улучшить решение: закодировать категориальные признаки при помощи OneHot encoding, обучить бустинг (по материалам занятия 5)
* 28 февраля - собрать докер-образ проекта 
* 2 марта - подготовить презентации к защите проектов
