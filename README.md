## Алгоритм
* Выделение границ при помощи фильтра Кэнни
* Выделение трапециевидной области интереса
* Поиск линий при помощи преобразования Хафа
* Вычисление координат линий дорожной разметки
* Проверка положения камеры относительно этих линий (нужно сместиться правее или левее)
* Вывод на экран изображения с выделенными линиями дорожной разметки и рекомендациями о том стоит сметиться правее или левее

## Результат работы программы
![Вывод программы, если машина двигается по середине полосы]( images/ok.jpg)
![Вывод программы, если машина должна сместиться правее]( images/keep_right.jpg)
![Вывод программы, если машина должна сместиться левее]( images/keep_left.jpg)