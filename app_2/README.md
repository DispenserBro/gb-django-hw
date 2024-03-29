# Домашнее задание по 1 семинару

[Общие сведения](../)

## Задания

- [Задание № 8](#задание-8-с-семинара), [модели](./models.py), [команды](./management/commands/)

### Задание 8 с семинара

- Создайте три модели Django: клиент, товар и заказ. Клиент может иметь несколько заказов. Заказ может содержать несколько товаров. Товар может входить в несколько заказов.
- Поля модели "Клиент":
    - имя клиента
    - электронная почта клиента
    - номер телефона клиента
    - адрес клиента
    - дата регистрации клиента
- Поля модели "Товар":
    - название товара
    - описание товара
    - цена товара
    - количество товара
    - дата добавления товара
- Поля модели «Заказ»:
    - связь с моделью «Клиент», указывает на клиента, сделавшего заказ
    - связь с моделью «Товар», указывает на товары, входящие в заказ
    - общая сумма заказа
    - дата оформления заказа
- Допишите несколько функций CRUD для работы с моделями по желанию

#### Описание решения

Все модели содержат поля из задания.
Во всех моделях переопределён метод `__str__`.
В командах добавил CRUD-операции для работы с моделями:
- Create: add_client, add_product, add_order
- Read: get_clients, get_products, get_orders
- Delete: delete_client
