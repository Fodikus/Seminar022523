# Seminar022523
Домашняя работа №9 к семинару "Знакомство с языками программирования"

Задача 66: Задайте значения M и N. Напишите программу, которая найдёт сумму натуральных элементов в промежутке от M до N.
```
int sum(int m, int n)
{ 
    if (m == n)
        return m;
    return sum(m, n - 1) + n;
}

Console.Clear();
Console.Write("Введите число M: ");
int m = Convert.ToInt32(Console.ReadLine());
Console.Write("Введите число N: ");
int n = Convert.ToInt32(Console.ReadLine());
while (m > n)
{
    Console.Write("Вы ошиблись!\nВведите число N больше числа M: ");
    n = Convert.ToInt32(Console.ReadLine());
}

Console.WriteLine($"M = {m}; N = {n} -> {sum(m, n)}");
```

Задача 68: Напишите программу вычисления функции Аккермана с помощью рекурсии. Даны два неотрицательных числа m и n.
```

}
```
