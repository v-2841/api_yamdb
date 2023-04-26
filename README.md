### YaMDb (групповой проект)
### Описание
Проект YaMDb собирает отзывы (Review) пользователей на произведения (Title).
Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм или послушать музыку
Произведения делятся на категории: «Книги», «Фильмы», «Музыка».
Список категорий (Category) может быть расширен (например, можно добавить категорию «Изобразительное искусство» или «Ювелирка»).

Произведению может быть присвоен жанр из списка предустановленных (например, «Сказка», «Рок» или «Артхаус»).

Добавлять произведения, категории и жанры может только администратор.

Благодарные или возмущённые пользователи оставляют к произведениям текстовые отзывы и ставят произведению оценку в диапазоне от одного до десяти (целое число); из пользовательских оценок формируется усреднённая оценка произведения — рейтинг (целое число). На одно произведение пользователь может оставить только один отзыв.

Добавлять отзывы, комментарии и ставить оценки могут только аутентифицированные пользователи.

Полная документация к API находится по эндпоинту /redoc

### Стек технологий использованный в проекте:
-   Python
-   Django
-   Django REST Framework
-   REST API
-   SQLite
-   Аутентификация по JWT-токену

## Запуск проекта
1. Клонирование репозитория
```
git clone https://github.com/v-2841/api_yamdb.git
```
Откройте в своем редакторе кода локальный проекта из репозитория GitHub, клонированного ранее

2. Развертывание в репозитории виртуального окружения для MacOS или Linux
```
python3 -m venv venv
```
Развертывание в репозитории виртуального окружения для Windows
```
python -m venv venv
```

3. Запуск виртуального окружения для MacOS или Linux
```
source venv/bin/activate
```
Запуск виртуального окружения для Windows
```
source venv/Scripts/activate
```

4. Установка зависимостей в виртуальном окружении
```
pip install -r requirements.txt
```

5. Перейти в папку api_yambd
```
cd api_yambd/
```

6. Выполнение миграций для MacOS или Linux
```
python3 manage.py migrate
```
Выполнение миграций для Windows
```
python manage.py migrate
```

7. Запуск проекта для MacOS или Linux
```
python3 manage.py runserver
```
Запуск проекта для Windows
```
python manage.py runserver
```

## Документация
Документация будет доступна после запуска проекта по адресу `/redoc/`.

## Авторы
- :white_check_mark: [Vitaliy Pavlov (Python-разработчик - тимлид)](https://github.com/v-2841)
- :white_check_mark: [Aleksei Kashtanov (Python-разработчик)](https://github.com/frensiss2001)
- :white_check_mark: [Vadim Demin (Python-разработчик)](https://github.com/Jaguar0505)