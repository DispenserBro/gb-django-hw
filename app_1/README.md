# Домашнее задание по 1 семинару

[Общие сведения](../)

## Задания

- [Задание № 7](#задание-7-с-семинара)

### Задание 7 с семинара

- Создайте пару представлений в вашем первом приложении:
главная и о себе.
- Внутри каждого представления должна быть переменная
html - многострочный текст с HTML вёрсткой и данными о
вашем первом Django сайте и о вас.
- *Сохраняйте в логи данные о посещении страниц

#### Описание решения

Для генерации случайных данных использовалась библиотека [Faker](https://pypi.org/project/Faker/).

При каждом обновлении страницы генерируются новые слычйные заголовки, описания и даты новостей.

Вместо представленной функции генерации можно указать любую другую с аналогичным форматом вывода.

В функции-представлении происходит генерация строки, содержащей HTML страницу.