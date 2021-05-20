# Cat_Dog_Classifier
Свёрточная нейронная сеть, распознающая кошек и собак на изображении без специализированных для этого библиотек машинного обучения. Естественно, данный классификатор будет уступать существующим альтернативам, поскольку он работает на CPU, поэтому для экономии времени были выставлены достаточно "щадящие" условия для обучения сети.

## Скрипты

`Neural_network.py`- скрипт, в котором происходит обучение сети. Обученные веса csv формата хранятся в папке "weights".

>(Постскриптум, веса уже готовы, ничего обучать не надо. Но если хочется, то нужно скачать датасет по ссылке: https://www.kaggle.com/c/dogs-vs-cats/data
>, распаковать архив "train.zip" в папку "dataset/train", запустить `Neural_network.py` и подождать некоторое время)

`main.py` - обученная сеть с интерфейсом.
