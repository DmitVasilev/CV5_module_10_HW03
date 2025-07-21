# CV 5. Модуль 10 (HW-03)

## Содержание
[1. Постановка задачи](https://github.com/Tio147/DS_1/tree/main/project_0/README.md#Project-description)   
[2. Результаты](https://github.com/Tio147/DS_1/tree/main/project_0/README.md#What-case-are-we-solving?)   
[3. Выводы](https://github.com/Tio147/DS_1/tree/main/project_0/README.md#Brief-information-about-the-data)   


### 1. Постановка задачи

В данной работе необходимо:
* провести обучение модели семейства YOLOv5 с использованием предобученных весов;
* провести сравнение с моделью faster rcnn;
* добиться значения метрики mAP_50 на валидационной выборке более 85%;
* визуализировать прогноз модели валидационной выборке.

:arrow_up:[in table of contents](https://github.com/Tio147/DS_1/tree/main/project_0/README.md#Table-of-contents)

### 2. Результаты

* Ноутбук с решением на GitHub: [m10_u4_homework.ipynb]().
* Обеспечить воспроизводимость кода поможет файл requirements.txt: [requirements.txt]().

:arrow_up:[in table of contents]()


### 3. Выводы
При обучении моделей использовались предобученные веса. Проведено сравнение моделей семейства YOLOv5 и fasterrrcnn_resnet50_fpn. Модели семейства YOLOv5 показали более высокую скорость обучения. Значения метрик mAP_50 и mAP_50_95 для старшей модели семейства YOLOv5 также оказались выше, чем для модели fasterrrcnn_resnet50_fpn. Модель YOLOv5m превосходит fasterrrcnn_resnet50_fpn по метрике mAP_50_95, однако уступает по метрике mAP_50. Значение метрики mAP_50 для YOLO v5x6 + TTA на валидационной выборке составила 86.2 %. Проведена визуализация прогнозов моделей для изображения из валидационной выборки.

:arrow_up:[к содержанию]()

