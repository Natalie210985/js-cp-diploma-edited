# Дипломное задание по курсу «JavaScript-программирование для начинающих»

## Создание «информационной системы для предварительного бронирования билетов».

### Студенту предоставляются следующие компоненты системы:

- [Верстка](./sources/layout.zip)
- [Backend](./md/backend.md)

## Задача

-   Разработать сайт бронирования билетов онлайн

## Сущности

_Кинозал_  Помещение, в котором демонстрируются фильмы. Режим работы определяется расписанием на день. Зал — прямоугольный, состоит из N*M различных зрительских мест.

_Зрительское место_  Место в кинозале. Зрительские места могут быть VIP и обычные.

_Фильм_  Информация о фильме заполняется администратором. Фильм связан с сеансом в кинозале.

_Сеанс_  Сеанс — это временной промежуток, в котором в кинозале будет показываться фильм. На сеанс могут быть забронированы билеты.

_Билет_  QR-код c уникальным кодом бронирования, в котором обязательно указаны место, ряд, сеанс. Билет действителен строго на свой сеанс. Для генерации QR-кода можно использовать [QRCreator.js](https://github.com/slesareva-gala/QR-Code)

## Роли пользователей системы

-   Гость — неавторизованный посетитель сайта

### Возможности гостя

-   просмотр расписания
-   просмотр информации о фильмах
-   выбор места в кинозале
-   бронирование билета

## **Стек технологий**

![logo](./img/logo.png)


## **Реализация проекта**

- Адаптирована исходная верстка под планшетные и мобильные устройства.
- Разработана API для взаимодействия с Backend.
- Запрограммирована гостевая часть сайта

## **[Демо](https://Natalie210985.github.io/js-cp-diploma-edited/)**
![Демо](./img/demo.gif)
