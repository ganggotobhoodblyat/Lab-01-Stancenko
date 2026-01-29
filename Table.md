| Вызывающий метод | Метод            | Вызываемый модуль  | Метод                        | Данные                                |
|------------------|------------------|--------------------|------------------------------|---------------------------------------|
| Program.Main     | -                | InputModule        | ReadInt("Введите число: ")   | string prompt → int n                 |
| Program.Main     | -                | ValidationModule   | IsValidNumber(n, 1, 20)      | int n, int min=1, int max=20 → bool   |
| Program.Main     | if(bool)         | ProcessingModule   | PrintSquare(n)  | int n      | int n                                 |
| InputModule      | ReadInt(promt)   | Console            | ReadLine | string → int n    | string → int n                        |
| ProcessingModule | PrintSquare(n)   | Console            | WriteLine()                  | -                                     |

