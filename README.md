# P02D13

***== Quest received. Develop an src/game_of_life.c program in C – a visualization of The Game of Life. To display the graphics, only use ASCII characters (with output to the terminal). You need to implement interactive version of the Game of life. Also create the option for adjusting the speed of the "game". ==***

* ***Graphics***

Treat the playing field - a rectangle of 80 by 25 cells – as a matrix of the state of the "game". 
It is assumed that the field is "closed to itself", for example, in the lower right square, the neighbor on the right is the lower left square, and the neighbor on the bottom is the upper right.
Provide for original initialization of the "game" state via stdin. Prepare at least 5 files with initial states for quick launch and initialization through input redirection. 

## Important notes:

* The game must be written in C, have a structured style, and run from the terminal; 
  
* Your source code will be tested by the static analyzer `cppcheck`, as well as the style linter `cpplint`. 
  
* Do not use cumbersome functions, limit them up to 40 lines (excluding `main`).

* Check your program for memory leaks!

> When developing the game, follow the principles of structured programming of E. Dijkstra.


One from s21 pool

This game is an imitation of life. This is a cellular automaton invented by the English mathematician John Conway in 1970. This is a copy made by me and 2 students of school 21 pool.



***== Получен Quest. На языке программирования Си разработать программу src/game_of_life.c, представляющую из себя визуализацию "The Game of Life". Для отображения графики использовать только символьную (ASCII) графику (с выводом в терминал). Необходимо реализовать в игре Game of life интерактивный режим, c настройкой скорости игры. ==***

Поле — прямоугольник 80 на 25 клеток.
Подразумевается, что поле "замкнуто само на себя", к примеру у нижнего правого квадратика соседом справа является нижний левый квадратик, а соседом снизу - верхний правый.

Предусмотреть начальную инициализацию состояния "игры" через stdin. Подготовить как минимум 5 файлов с начальным состоянием для быстрого запуска и инициализации через перенаправление ввода.

## Важные замечания

* Игра должна быть разработана на языке Си, в структурном стиле и работать из терминала;
  
* Ваш исходный код будет тестироваться статическим анализатором ```cppcheck```, а также стилевым линтером 
```cpplint```.

* Инструкция о том, как запустить эти тесты у себя на компьютере, лежит в папке `materials`.

* Не используйте громоздкие функции, ограничивайтесь 40 строками (`main` не в счет).

* Проверяйте вашу программу на утечки памяти!

> При разработке игры в полной мере руководствоваться принципами структурного программирования Э. Дейкстры. 
