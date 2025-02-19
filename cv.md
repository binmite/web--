# Томашов Артём

## Контакты:
- Телефон: **+375293517158**
- E-mail: <tomasovartem039@gmail.com>
- Telegram: [@natashalava](https://t.me/natashalava)
- Instagram: [n.shalava](https://www.instagram.com/n.shalava?igsh=MXIxZGk3NGF6NTQ3ZA==)

---

Студент по специальности <mark>информатика и вычислительная техника</mark>. Ищу возможность *расширить свои знания* и получить любой опыт.

---

## Навыки:
- Git (basic)
- C#
- Python
- HTML, CSS

---

## Примеры кода:

### Решение задачи с единичной окружностью:
```csharp
internal class Program
{
    static void Main(string[] args)
    {
        Console.Write("Введите x: ");
        double x = double.Parse(Console.ReadLine()!);

        Console.Write("Введите y: ");
        double y = double.Parse(Console.ReadLine()!);

        if (Math.Pow(x, 2) + Math.Pow(y, 2) <= 1 || ((x >= 0 && x <= 1) && (y >= 0 && y <= 1)))
        {
            Console.WriteLine("Принадлежит");
        }
        else
        {
            Console.WriteLine("Не принадлежит");
        }
    }
}
```

### Решение задачи с поиском чисел Армстронга:
```csharp
internal class Program
{
    static void Main(string[] args)
    {
        Console.Write("Введите k: ");
        int k = int.Parse(Console.ReadLine()!);

        for (int i = 1; i <= k; i++)
        {
            if (IsArmstrongNumber(i))
            {
                Console.WriteLine($"{i} - число Армстронга");
            }
    
            else
            {
                Console.WriteLine($"{i} - не число Армстронга");
            }
        }
    }

    public static bool IsArmstrongNumber(int number)
    {
        string numString = number.ToString();
        List<int> numbers = new List <int>(numString.Length);
    
        foreach (char c in numString)
        {
            int digit = c - '0';
            numbers.Add(digit);
        }
    
        int sum = 0;
        int numberOfDigits = numbers.Count;
    
        foreach (int digit in numbers)
        {
            sum += (int)Math.Pow(digit, numberOfDigits);
        }
    
        return sum == number;
    }
}
```
---

## Выполненные проекты:
- CV

---

## Курсы и тренинги:
- Курс по Phyton от LetPy
- ~~Курс по JS от Rolling Scopes~~
- ~~Курс по React от KTS~~

---

## Уровень английского:
B2 (тест от Epam)
