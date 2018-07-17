# Задание 3 - Временные интервалы

Написать программу, которая умеет работать с интервалами времени. Интервал времени - это целое число в определенных единицах
измерения времени (секунды, минуты и т.д.).

В базовом интерфейсе `TimeUnit` описаны методы, которые должен реализовать каждый конкретный тип интервала.
Примеры реализации можно посмотреть в классах `Milliseconds` и `Seconds`

Класс `TimeUnitUtils` содержит утилитные методы для перевода интервалов из одних единиц измерения в другие.

В процессе работы над этой задачей надо также проанализировать работу реализованных классов и сделать модификации, если это необходимо.

Этапы выполнения задания:
* Реализовать класс `Minutes`, который определяет интервал в часах
* Добавить методы по переводу интервалов из одних единиц в другие в классе `TimeUnitUtils`
* Добавить новый метод в интерфейс `TimeUnit` - `long getHours()`, возвращающий количество часов в интервале. Реализовать новый метод для существующих классов интервалов и добавить новый класс `Hours`.