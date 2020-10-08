# Обучаем и тестируем в Yandex Datalens ML-модель бинарной классификацию изображений. 
Демо видео тут: https://youtu.be/N-Ho8uIOx9E
Мы будем относить каждой изображенеи к одной из двух категорий. В нашем случае это - легковой автомобиль и все остальное. Одним из основных сценариев обучения передаче данных является использование сети, предварительно обученной на большом наборе данных (изображений). В примере используется подход Convolutional Neural Network (CNN) под названием ResNet50, предварительно обученный на наборе данных ImageNet, который содержит 1,2 миллиона изображений, которые разнесены по 1000 категорий. Сначала вы удалите последний сетевой слой, чтобы создать визуальные элементы изображений. Затем вы будете использовать эти функции для обучения boosted decision tree для классификации изображений как pass (автомобиль) или неудачных (в нашем наборе автобусы). Вы будете использовать в Keras с CNTK-toolkit в качестве CNN и LightGBM для бинарной классификации
