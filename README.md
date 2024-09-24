# lesson26

### Попов Георгий 

### параграф 26 

1)

Компьюютерная арифмеетика, техническая дисциплина, предметом исследования которой являются представление чисел в ЭВМ, алгоритмы вычисления элементарных функций

2)

В компьютерах вещественные числа хранятся в регистрах и ячейках памяти с ограниченным количеством разрядов. 

3)

При сложении может возникнуть ситуация, когда старшие разряды результата операции не помещаются в отведенной для него области памяти. 

4)

Дробная часть числа ограничена, поэтому любое число, имеющее более трёх цифр после запятой

5)

Антипереполнение — это ситуация, когда результат операции становится настолько близким к нулю, что порядок числа выходит за пределы разрядной сетки. 

6)

Антипереполнение может сделать дальнейшие вычисления невозможными, если полученный результат нужно разделить на него.

7)

Знаковый разряд несёт один бит информации, поскольку он имеет два допустимых значения: 0 и 1

8)

Примеры величин, которые по своему смыслу могут иметь только целые значения: Год рождения, Номер квартиры.

9)

Разделение в компьютере целых и вещественных (дробей) чисел даёт следующие преимущества: Экономичное использование компьютерной памяти. Целые числа занимают меньше места в памяти, чем вещественные. Например, целые числа в интервале от 0 до 255 в языке Паскаль можно хранить в переменных типа byte которые занимают всего один байт. Ускорение операций. Операции с целыми числами, как правило, выполняются значительно быстрее, чем с вещественными. В ядре современных процессоров реализованы только целочисленные арифметические действия, а для вещественной арифметики используется специализированный встроенный блок. Удобство в определённых задачах. Только для целых чисел определены операции деления нацело и нахождения остатка. В некоторых задачах они удобнее, чем простое деление с получением дробного (к тому же не совсем точного) результата

10)

Во-первых, непрерывность бывает разной: в точке, справа и слева от этой точки f(c+0), f(c),f(c-0) на промежутке (открытом или закрытом), на бесконечности или в ООФ Во-вторых, справедливо другое: если функция непрерывна и ограничена, то такая функция необходимо стремится к пределу.

11)

Да, можно увеличить разрядность обрабатываемых чисел по сравнению с аппаратной разрядностью компьютера. 

### Задачи.

1) 255, 999 

2) 2^16 – 1 = 65 535, 2^32 – 1 = 4 294 967 295 

3) 2^-16 = 0,0000152587890625; 1,234567 1,234568 

4) ‐32767 5- Например, факториал числа 9, т.е. 1⋅2⋅3⋅…⋅9 = 362880 > 2^16
