Дипломная работа по курсу "Python-разработчик"

Это приложение предоставляет полноценную платформу для пользователей, которым необходимо выполнять задачи по обнаружению объектов на изображениях. Используя предобученные модели глубокого обучения и удобный веб-интерфейс на Django, проект подходит для пользователей без опыта в машинном обучении.

К использованию предлагается модель <a href="https://github.com/chuanqi305/MobileNet-SSD">MobileNet SSD</a>. Она определяет следующие классы:
самолёт
велосипед
птица
лодка
бутылка
автобус
автомобиль
кот
стул
корова
стол
собака
лошадь
мотоцикл
человек
цветок
овца
диван
поезд
телевизор
В оригинале - "aeroplane", "bicycle", "bird", "boat", "bottle", "bus", "car", "cat", "chair", "cow", "diningtable", "dog", "horse", "motorbike", "person", "pottedplant", "sheep", "sofa", "train", "tvmonitor".

### Run (im work on ubuntu)
1. python -m venv venv
2. source venv/bin/activate
3. pip install -r requirements.txt
4. python manage.py runserver