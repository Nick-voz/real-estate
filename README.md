# Сайт по продаже недвижимости

> Для получения доступа к полному описанию и задачам писать в [Telegram]( https://t.me/SergeyFilichkin)

Приложение создано для тренировки на реальных задачах и получения коммерческого опыта. Выполнение задач помогает достигнуть __реального уровня middle python разработчика__.

Типы задач:
- **технического плана** (продумать архитектуру, прикрутить новый микросервис, настроить взаимодействие между сервисами, переехать на другую БД, написать юнит-тесты, настроить форматтер и тд.);
- **фичи** (добавить сущность, написать к ней API в соотвествии с бизнес-требованиями, добавить админку для менеджера и тд.).

Стек:
- Python 3.10;
- Django/DRF;
- FastAPI;
- Kafka;
- Celery;
- Redis;
- Docker/docker-compose.

__

## Запуск проекта

1. Делаем форк репозитория к себе в аккаунт:
Справа вверху жмем кнопку `fork` -> `Create fork`

2. Клонируем репозиторий из аккаунта себе локально на компьютер
- Жмем зеленую кнопку `<> Code`. Выбираем метод через `HTTPS`.
- Локально переходим в папку, в которую будем копировать (через терминал).
- В терминале пишем команду
```shell
git clone сюда_что_скопировали_ранее
```

### Используя виртуальное окружение

1. Установить базу данных Postgres:
[Ссылка](https://www.postgresql.org/download/)

2. Создать виртуальное окружение в папке с проектом
```shell
  python3 -m venv venv 
  pip3 install -r requirements.txt
```

3. Запустить
```shell
  python manage.py runserver
```

4. Проверить работоспособность:
[Перейти на страницу](http://www.localhost:8000)

# Создание мердж-реквестов
Т.к. ранее вы уже сделали форк, то работаем в этом репозитории.
- создаем ветку;
- коммитим в нее изменения;
- пушим в репозиторий;
- заходим в мой репозиторий (где вы это читаете);
- сверху `Pull requests`;
- справа `New pull request`.