# CV 5. Модуль 10 (HW-03)

## Содержание
[1. Постановка задачи](https://github.com/DmitVasilev/CV5_module_10_HW03?tab=readme-ov-file#1-%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8)   
[2. Результаты](https://github.com/DmitVasilev/CV5_module_10_HW03?tab=readme-ov-file#2-%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B)   
[3. Выводы](https://github.com/DmitVasilev/CV5_module_10_HW03?tab=readme-ov-file#3-%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D1%8B)   


### 1. Постановка задачи

В данной работе необходимо:
* провести обучение модели семейства YOLOv5 с использованием предобученных весов;
* провести сравнение с моделью faster rcnn;
* добиться значения метрики mAP_50 на валидационной выборке более 85%;
* визуализировать прогноз модели валидационной выборке.

:arrow_up:[ к содержанию](https://github.com/DmitVasilev/CV5_module_10_HW03#%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B0%D0%BD%D0%B8%D0%B5)

### 2. Результаты

* Ноутбук с решением на GitHub: [m10_u4_homework.ipynb](https://github.com/DmitVasilev/CV5_module_10_HW03/blob/904a4cd215f009d6a826795ffcfc6d33f8808a90/m10_u4_homework.ipynb).
* Обеспечить воспроизводимость кода поможет файл requirements.txt: [requirements.txt](https://github.com/DmitVasilev/CV5_module_10_HW03/blob/904a4cd215f009d6a826795ffcfc6d33f8808a90/requirements.txt).

:arrow_up:[ к содержанию](https://github.com/DmitVasilev/CV5_module_10_HW03#%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B0%D0%BD%D0%B8%D0%B5)


### 3. Выводы
 - При обучении моделей использовались предобученные веса.
 - Проведено сравнение моделей семейства YOLOv5 и fasterrrcnn_resnet50_fpn. Модели семейства YOLOv5 показали более высокую скорость обучения. Значения метрик mAP_50 и mAP_50_95 для старшей модели семейства YOLOv5 также оказались выше, чем для модели fasterrrcnn_resnet50_fpn. Модель YOLOv5m превосходит fasterrrcnn_resnet50_fpn по метрике mAP_50_95, однако уступает по метрике mAP_50. 
 - Значение метрики mAP_50 для YOLO v5x6 + TTA на валидационной выборке составила 86.2 %. 
 - Проведена визуализация прогнозов моделей для изображения из валидационной выборки.

:arrow_up:[ к содержанию](https://github.com/DmitVasilev/CV5_module_10_HW03#%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B0%D0%BD%D0%B8%D0%B5)

