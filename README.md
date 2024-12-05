# Recognizing_lie
В этом проекте реализована система распознавания эмоций с использованием данных о чертах лица и нейронных сетей. Она включает в себя сценарии для обучения модели нейронной сети, обработки данных и выполнения логического вывода для прогнозирования эмоций по изображениям лиц. В будущем, проект будет распознавать, лжет ли человек или нет по эмоции, которую он показал. 

Ориентация по проекту (выполнять следующие файлы по порядку, чтобы модель могла обучиться):
Recognizing_lie/src/collect_from_picture.py - файл, загружающий координаты точек лица с показанной эмоцией на картинке в отдельный файл (в файле хранятся данные для обучения модели распознавать эмоции) - подготовка dataset
Recognizing_lie/src/train_model.py - файл, благодаря которому программа обучается распознавать эмоцию (можно заметить, что в результате программа выдает, с какой точностью была определена та или инная эмоция, и с каждым разом эта точность растет (модель обучается)) - обучение модели
Recognizing_lie/src/use_model.py - файл, который используется для распознавания эмоций (так как модель уже обучена, она может распознавать, на какой картинке какая эмоция) - оценка рисунка