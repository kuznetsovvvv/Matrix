# Matrix

Определить класс **CMatrix** для работы с квадратной матрицей, содержащей
элементы из поля вычетов Zp, p - простое число, которое задается с помощью
оператора #define целых чисел. Внутри класса матрица должна быть реализована с
помощью указателя (int **). Размер матрицы задается в конструкторе класса.

**В классе должны быть определены**
* необходимые конструкторы (в том числе
конструктор копирования и перемещения)

* деструктор
  
* операторы присваивания(копированием и перемещением)
  
* << (вставка в поток вывода)
  
* инкремент и декремент ++ и -- (справа и слева), увеличивающие и уменьшающие размер
матрицы

* сложения матриц. Сложение выполняется поэлементно. При сложении
размер результата - это минимум из размеров исходных матриц, лишние строки
матрицы большего размера игнорируются.

**Каждый класс должен быть описан в 2-х файлах** (заголовочном и
реализации): cmatrix.h и cmatrix.cpp

**В отдельном файле должен быть написан тест на данный класс
(функция main).**

**Coverage by tests:** 
[![Coverage Status](https://coveralls.io/repos/github/kuznetsovvvv/Matrix/badge.svg?branch=main)](https://coveralls.io/github/kuznetsovvvv/Matrix?branch=main)
