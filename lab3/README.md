# Лабораторная работа #3
Задание:
1) Попробовать несколько разлчных [техник нормализации](http://yeephycho.github.io/2016/08/03/normalizations_in_neural_networks/) изображения ([дополнительная информация](https://medium.com/@dibyadas/visualizing-different-normalization-techniques-84ea5cc8c378)). (2 балла)

    a) без нормализации

    b) Local Contrast Normalization

    c) Local Responce Normalization
2) Попробовать применить [аугментацию](https://pytorch.org/vision/stable/auto_examples/transforms/plot_transforms_illustrations.html#sphx-glr-auto-examples-transforms-plot-transforms-illustrations-py) (как минимум 3 варианта). Как она влияет на процесс обучения? (2 балла)

    a) Horizontal flip

    b) Color augmentation

    c) Affine (любой)

    d) [MixUp](https://towardsdatascience.com/yolov7-a-deep-dive-into-the-current-state-of-the-art-for-object-detection-ce3ffedeeaeb)

    e) Mosaic
3) Возьмите любую модель, с которой вы хотите провести эти эксперименты, и постарайтесь набрать как можно больше очков. (3 балла)
4) Напишите свою собственную модель и обучите ее. Отправьте submission (результаты в таблице лидеров для hand-made моделей будут сравниваться отдельно). (3 балла)
5) (опционально) Попробуйте проанализировать ошибки модели, чтобы узнать, как повысить метрики. (3 балла)

P.S.:
* Метрика для оценивания — [mAP](https://jonathan-hui.medium.com/map-mean-average-precision-for-object-detection-45c121a31173).