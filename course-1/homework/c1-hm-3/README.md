1) Условие: запросить температуру в градусах Цельсия, перевести в Фаренгейты по формуле
F = C * 9 / 5 + 32 и вывести результат.

Код:
string q = Console.ReadLine();
double C = double.Parse(q);
double F = C * 9 / 5 + 32;
Console.WriteLine(F);

Пример:

Ввод:25
Вывод:77

2)Условие: запросить три числа, найти среднее арифметическое, вывести результат с пояснением.

Код:
double a = double.Parse(Console.ReadLine());
double b = double.Parse(Console.ReadLine());
double c = double.Parse(Console.ReadLine());

double arithmetic = (a + b + c) / 3;
Console.WriteLine($"Среднее арифметическое чисел {a}, {b}, {c} равно {arithmetic}");

Пример:

Ввод:  3
Ввод:  6
Ввод:  9
Вывод: Среднее арифметическое чисел 3, 6, 9 равно 6

3)Условие: запросить два числа, вывести сумму, разность, произведение и частное.

Код:
double a = double.Parse(Console.ReadLine());
double b = double.Parse(Console.ReadLine());

double sum = a + b;
double sub = a - b;
double mul = a * b;
double div = a / b;

Console.WriteLine($"Сумма:{sum};Разность:{sub};Умножение:{mul};Деление:{div}");

Пример:

Ввод:  10
Ввод:  4
Вывод: Сумма:14;Разность:6;Умножение:40;Деление:2,5