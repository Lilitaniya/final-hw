# Задача: 
>Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


![итог](https://github.com/Lilitaniya/final-hw/assets/141516288/e8bb750e-332a-4aad-89bd-8203ae2c9b28)

Для того, чтобы написать эту программу, надо:

1. Объявить и инициализировать массивы строк, в нашем случае через переменные `sourceArray` и `newArray`.

2. Определить функцию, которая принимает массив строк и возвращает количество элементов в массиве, у которых длина строки не превышает 3. В нашем случае это функция `DeterminingSizeNewArray`.

3. Определить функцию, которая принимает размер и массив строк, и возвращает новый массив с элементами, у которых длина строки не превышает 3. В нашем случае это функция `FormingNewArray`

4. Определеить функцию, которая принимает массив строк и выводит его содержимое на консоль. В коде эта функция названа `PrintArray`.

5. После определения всех функция объявляем переменную и инициализируем ее значением равным 0. Т.е., `int lenght = 0`

6. Запускается цикл, в котором происходит проверка длины строк в массиве `sourceArray`, и если она не превышает 3, то увеличивается счетчик `length`. Т.е., `for (int i = 0; i < array.Length; i++) if (array[i].Length <= 3) length++;`

7. Возвращаем значения переменной `length`.

8. Теперь объявляем переменную `threeArr` и инициализзируем новым массивом строк размера `size`.

9. Снова запускаем цикл с перебором по подобию прошлого, только если длина строки не превышает 3, то она добавляется в новый массив `threeArr`. 

10. Опять же делаем возврат. 

11. После того как все циклы прокрутятся, надо сделать их вывод. В коде они обозначены выводами на консоль через функцию `PrintArray`. Выводится сначала старый массив `sourceArray` и потом содержимое нового массива через `newArray`.

12. Готово, вы восхитительны! 
