1)
string q = Console.ReadLine();
double C = double.Parse(q);
double F = C * 9 / 5 + 32;
Console.WriteLine(F);

2)
double a = double.Parse(Console.ReadLine());
double b = double.Parse(Console.ReadLine());
double c = double.Parse(Console.ReadLine());

double arithmetic = (a + b + c) / 3;
Console.WriteLine($"Среднее арифметическое чисел {a}, {b}, {c} равно {arithmetic}");

3)
double a = double.Parse(Console.ReadLine());
double b = double.Parse(Console.ReadLine());

double sum = a + b;
double sub = a - b;
double mul = a * b;
double div = a / b;

Console.WriteLine($"Сумма:{sum};Разность:{sub};Умножение:{mul};Деление:{div}");