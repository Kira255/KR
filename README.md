# Итоговая проверочная работа

## Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив задан на старте выполнения алгоритма.

## Алгоритм решения:
Создаем массив из строк Array1, заполненный 5 строками ("print", "num", "256", "class", "128"), и массив из строк Array2 имеющий длину идентичную длине массива Array1. 

Создаем функцию SecondArray, которая принимает массив array1 и массив array2, и ничего не возвращает. Внутри функции создаем переменную count равную 0, далее цикл for, который пробегает по длине массива array1. Внутри цикла for условие if, которое проверяет длина элемента с индексом i из массива array1 меньше или равна 3, если да, то в элемент массива array2 с индексом count записывается элемент массива array1 с индексом i, к count прибавляем 1. 

Создаем функцию PrintArray, которая принимает массив array, и ничего не возвращает. Создаем цикл for, который пробегает по длине массива array, и печатает поочередно элементы массива array в терминал. 

Далее вызываем функцию SecondArray для массивов Array1 и Array2, и функцию PrintArray для массива Array2.

*В папке KR хранится решение Задачи (папка Example), блок-схема, файл README.*