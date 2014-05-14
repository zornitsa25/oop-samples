﻿Примери за обектно-ориентирано програмиране на C++
===================================

Проектът съдържа примери, които демонстрират различни особености на
обектно-ориентираното програмиране на C++.

Примерите са групирани в различни директории, според
темата, към която се отнасят (напр. динамичен масив).

Списък на примерите
--------------------

### Command Line
1. **List Command Line Arguments** - Извежда на екрана всички аргументи подадени от командния ред.

### Dynamic Array (динамичен масив)
1. **Dynamic Array With Structures** - Проста реализация на динамичен масив с помощта на структура и няколко функции.
2. **Dynamic Array With Classes** - Обектно-ориентирана реализация на динамичен масив.
3. **Dynamic Array Extended** - Разширение на обектно-ориентираната реализация на динамичен масив. В тази версия е добавена обработка на изключения и се демонстрира употребата на Proxy клас в реализацията на оператора [].

### Dynamic Memory
1. **Two-Dimensional Array Allocation With Exceptions** - Демонстрира динамично заделяне на двумерен масив. Примерът включва и обработка на изключенията хвърлени от new.
2. **Two-Dimensional Array Allocation With Nothrow** - Демонстрира динамично заделяне на двумерен масив. В примера new се използва с nothrow. Демонстрира се и употребата на errno и strerror

### Files
1. **File Size** - Прост пример за намиране на размер на файл.

### Exceptions
1. **Exceptions** - Пример за използване на изключения. Примерът позволява да се експериментира с хвърляне на различни типове и няколко точки, в които те се прихващат.

### Rational Number
1. **Rational Number With Structures** - Реализация на рационално число със структура. Включена е и нормализираща функция, която коригира знаците на числителя и знаменателя и ги съкращава на техния НОД.
2. **Rational Number With Classes** - Обектно-ориентирана реализация на рационално число. В примера е включена възможност за автоматична нормализация на числото след всяка операция, която го променя.

### Static
1. **Static Inside a Function** - Демонстрира функция, която брои колко пъти е била извикана при изпълнението на програмата.
2. **Static Inside a Class** - Демонстрира клас, който брои колко негови обекти са били създадени при изпълнението на програмата.