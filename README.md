# Домашнее задание к занятию "`Базы данных`" - `Степанов Владислав`

### Задание 1

Сотрудники (
id - первичный ключ,serial
Имя - char(70)
id должности - внешний ключ таблицы должность
Дата найма - date
Оклад - numeric

)

Должность (
id - первичный ключ,serial
Название должности - char(50)
)

Подразделение (
id - первичный ключ,serial
Тип - char(20)
Название подразделения - char(100)
)

Проект (
id - первичный ключ,serial
Название проекта - char(150)
)

Филиал (
id - первичный ключ,serial
id города - внешний ключ таблицы город
Адрес - char(50)
)

Город (
id - первичный ключ,serial
Город - char(15)
)

Сотрудник - проект (
id сотрудника - внешний ключ таблицы сотрудник
id проекта - внешний ключ таблицы проект
)
