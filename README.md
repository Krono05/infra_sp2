# YaMDB
## _The Best music social network_
## Помогаем найти друзей по интересам

## Возможности

- Вы можете осталять свои отзывы и комментарии к ним
- Выставлять рейтинг произведениям
- Писать похвальные оды или ругать автора

## Установка

#### 1. Установка docker и docker-compose

Если у вас уже установлены docker и docker-compose, этот шаг можно пропустить, иначе можно воспользоваться официальной [инструкцией](https://docs.docker.com/engine/install/).

#### 2. Запуск контейнера
```bash
docker-compose up
```
### 3. Выключение контейнера
```bash
docker-compose down
```


## Использование
#### Создание суперпользователя Django
```bash
docker-compose run web python manage.py createsuperuser
```

#### Пример инициализации стартовых данных:
```bash
docker-compose run web python manage.py loaddata fixtures.json
```

## Основные использованные технологии
* python 3.8
* [django](https://www.djangoproject.com/)
* [drf](https://www.django-rest-framework.org/)
* [posgresql](https://www.postgresql.org/)
* [docker](https://www.docker.com/)
* ✨Magic ✨

## Автор

* **Tamir Boldanov** - *Initial work* - (https://github.com/krono05)

## Лицензия

MIT License.

## Благодарности

Яндекс.Практикум