# MlSexDetector
Detect user's sex by name
Нейронная сеть, определяющая пол человека по ФИО.

## Требования
Python 3, TensorFlow, Keras, NLTK

## QuickStart
> python predict.py

Далее следует вводить различные имена в режиме диалога, сеть будет определять пол:
> Input name: Владимир Путин
> Sex:  М
> [[  4.24729733e-05   9.96808589e-01   3.14901001e-03]]
> Input name: Любовь Петрова
> Sex:  Ж
> [[  3.94746803e-06   7.50368787e-03   9.92492378e-01]]
> Input name: Полад Бюльбюль оглы
> Sex:  М
> [[ 0.00102036  0.97395748  0.0250222 ]]
> Input name: Кто Где
> Sex:  unknown
> [[  9.99970675e-01   2.07114244e-05   8.59489865e-06]]

## Retrain
> python train.py

При этом будет использован малый датасет.
