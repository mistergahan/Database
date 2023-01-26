# Database
Курс ИУ5 по Базам Данных. PostgreSQL

### Общие положения

- Программное обеспечение. Студенты могут использовать виртуальную машину с Ubuntu 20.04 по ссылке выше или компьютеры в аудиториях университета с Alt Linux

- IDE. PgAdmin на всех ПК, но предпочтительнее DataGrip на личных компьютерах

- Импорт БД MS Access на PostgreSQL. Необходимо выправлять типы, возможно через csv.

### Программное обеспечение 

- Образ виртуальной машины Linux [Ubuntu 20.04](https://github.com/iu5git/Standards/blob/main/Linux/Linux.md) для выполнения заданий курса

- [Инструкция](Docker/README.md) по установке PosgreSQL Docker


### Лабораторная 1. Основы SQL

Автор: Мащенко Елена

Создать БД. Create (типы данных, Primary, Foreign), пара таблиц. Select, CRUD. NULL, NOT NULL

[Методические указания](tutorials/lab1)

### Лабораторная 2. Запросы DDL и DCL

Автор: Мащенко Елена

DDL (alter table) + DCL (Пользователи? grant, revoke). 

Загрузка данных из csv. Полная версия бекапа и части данных.

### Лабораторная 3. Подробно SELECT

Select, where, join, order by. LEFT JOIN. Агрегированные функции, group by, having. Exists, union. 

Работа со строками и датами по вариантам. 

[Методические указания](tutorials/lab3.md)

### Лабораторная 4. Подзапросы и представления

Подзапросы (select, from, where)
View - закрепить select. Параметрировазованные View

[Методические указания](tutorials/lab2_add.md)

### Лабораторная 5. Создание приложения

Подключить к приложению, курсоры. Транзакции на примере insert (одна) + update (вторая таблица) и rollback.

* Вариант 1. C#

Автор: Даниил Карпов, Ия Ваксина

Создание оконного приложения на C# для получения данных и добавления/удаления данных

Методические указания

* Вариант 2. Tauri

Создание оконного приложения на Tauri для получения данных и добавления/удаления данных

[Методические указания](tutorials/lab5_tauri)

* Вариант 3. Qt

Создание оконного приложения на Qt для получения данных и добавления/удаления данных

[Методические указания](tutorials/qt.md)

### Лабораторная 6. Индексы и план запроса

Индексы и план запроса

[Методические указания](tutorials/lab4.md)

### Курсовая

Автор: Погосян Сос

По вариантам выполнить следующие пункты курсовой работы:

1. Из набора данных (например IMDb в формате csv) загрузить строки в таблицу-витрину.
2. Проанализировать данные - distinct. Создать таблицы под нужную предметную область, наполнить их данными из витрины.
3. Написать запросы select по нужному варианту с определенными условиями. Запросы, работают долго, потому что full scan
4. Проанализировать план запросов, добавить нужные индексы. Проверить чтобы запросы работали быстро.
5. Написать приложение для получения данных из таблицы по заданным условиям. Добавить функционал по добавлению записей и их удалению через приложение.
6. Администратор системы должен иметь доступ к редактированию дополнительных данных

#### Варианты приложения в курсовой:
1. Оконное приложение C#
2. Оконное приложение Tauri
3. Оконное приложение Qt

### Дополнительная Лабораторная 1. PL/SQL
PL/SQL, курсоры, хранимые процедуры, триггеры.

### Дополнительная Лабораторная 2. Чат бот с базой данных

Создание чат-бота на Python для получения данных и добавления/удаления данных

[Методические указания](tutorials/tgbot)

### Команда курса выражает благодарность за помощь в подготовке данного курса
1. Федюкин Данила Антонович
2. Калинников Даниил Игоревич 
3. Оразов Алексей Витальевич
4. Мащенко Елена Игоревна