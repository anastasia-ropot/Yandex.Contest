# Yandex.Contest
Яндекс.Контест — это сервис для онлайн-проверки заданий по математике и программированию. Он предназначен для проведения состязаний любого уровня — от школьных олимпиад до соревнований международного класса. Его можно использовать также для подготовки к турнирам и приёма экзаменов.

# 1) A. Камни и украшения

Условие | Данные 
------- | ------
Ограничение времени | 1 секунда
Ограничение памяти | 64Mb
Ввод | стандартный ввод или input.txt
Вывод | стандартный вывод или output.txt

## Условие
Даны две строки строчных латинских символов: строка J и строка S. Символы, входящие в строку J, — «драгоценности», входящие в строку S — «камни». Нужно определить, какое количество символов из S одновременно являются «драгоценностями». Проще говоря, нужно проверить, какое количество символов из S входит в J.
Это разминочная задача, к которой мы размещаем готовые решения. Она очень простая и нужна для того, чтобы вы могли познакомиться с нашей автоматической системой проверки решений. Ввод и вывод осуществляется через файлы, либо через стандартные потоки ввода-вывода, как вам удобнее.

## Формат ввода
На двух первых строках входного файла содержатся две строки строчных латинских символов: строка J и строка S. Длина каждой не превосходит 100 символов.

## Формат вывода
Выходной файл должен содержать единственное число — количество камней, являющихся драгоценностями.

## Пример

Ввод | Вывод
---- | -----
ab   | 4
aabbccd 

## Решение

JS - https://github.com/nastya-ropot/Yandex.Contest/blob/master/jewels.js
Node.js - https://github.com/nastya-ropot/Yandex.Contest/blob/master/jewelsNode.js
