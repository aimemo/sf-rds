# Проект 5. Ford vs Ferrari 

## Цели и задачи проекта
### Цели проекта
В заданном наборе картинок с изображением авто классифицировать на 10 классов по цветам.

### Задачи проекта
* Улучшить базовую метрику на kaggle.
* Использовать продвинутые библиотеки аугментации изображений.
* Подобрать параметры, обеспечивающие лучший результат.
* Использовать различные функции callback в Keras.
* Попробовать разные арзитектуры.

---

## Выводы по результатам работы над проектом

- Использована библиотека Albumentation для аугментации изображений.
- Протестированы различные комбинации значений переменных. Из всех опробованных вариантов текущие значения дают наилучшую метрику.
- Протестировано увеличение размера изображения, подаваемого на вход - к улучшению метрики не привело.
- Опробована сеть EfficientNetB4 - метрика была хуже, чем на Xception.
- Применена TTA. Score не значительно, но хуже, чем без него.

---
**Самое большое достижение** - проект сдаю своевременно и удалось получить **score выше, чем в baseline** :) Довольна как удав! ))))
