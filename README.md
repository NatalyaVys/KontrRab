Итоговая Проверочная работа. 
Задача. Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры или задать на старте выполнения алгоритма. 
пример: ["hello", "2", "world", ";-)"] -> [ "2", ";-)" ]


Алгоритм решения: 
*вводим значение и проводим перебор значений введенного массива. 
*проверяем каждый размер массива на соответствие условию задачи, т.е длина строки меньше или равно трем. 
*если строка соответствует условию переносим значение в новый массив, повторяем предыдущие два действия до тех пор, 
 пока не достигнем конца введенного массива. Выводим новый (удовлетворяющий условию) массив на экран.
*Если условие не выполняется то сразу выходим на экран пустой массив - [ ].
