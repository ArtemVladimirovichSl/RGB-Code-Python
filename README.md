**Входные данные**

Программе поступают последовательно три числа: значения оттенка красного, потом зеленого и затем синего цветов. Данные числа варьируются от 0 до 255 включительно

**Выходные данные**

Ваша задача закодировать оттенки цветов согласно RGB модели.
Не забывайте, что на каждый цвет всегда должно отводиться два разряда. Символы букв в шестнадцатеричной системе необходимо записывать в верхнем регистре.
Примечание: для перевода в 16-ую систему вы можете воспользоваться функцией hex, она возвращает строку перевода в 16ую систему, впереди которой находятся два служебных знака 0x

**Описание решения**

1. Просим пользователя ввести данные оттенков цветов Red, Green и Blue.
2. Создаём для каждого цвета отдельную переменную.
3. Считываем данные, введённое с консоли, в виде строки.
4. Преобразовываем их в целочисленное значение.
5. Переводим в шестнадцатиричную систему.
6. Срезом отсекаем служебные символы "0" и "х", стоящие вначале.
7. Если есть буквы, переводим их в верхний регистр.
8. Делаем длину строки не меньше двух символов. Если строка меньше двух символов, спереди дополняем её нулями.

**(пункты с 3 по 8 для каждой переменной)**

9. Выводим результат.
