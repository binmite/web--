# Tomashov Artem

## Contacts:
- Phone number: **+375293517158**
- E-mail: <tomasovartem039@gmail.com>
- Telegram: [@natashalava](https://t.me/natashalava)
- Instagram: [n.shalava](https://www.instagram.com/n.shalava?igsh=MXIxZGk3NGF6NTQ3ZA==)

---

Student majoring in <mark>computer science and computer engineering</mark>. I'm looking for an opportunity to *expand my knowledge* and gain any experience.

---

## Skills:
- Git (basic)
- C#
- Python
- HTML, CSS

---

## Code examples:

### Solving the unit circle problem:
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

### Solving the problem of finding Armstrong numbers:
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

## Completed projects:
- CV

---

## Courses and trainings:
- Phyton course from LetPy
- ~~JS course from Rolling Scopes~~
- ~~React course from KTS~~

---

## English level:
B2 (test from Epam)

---

## My photo

![Упс, не загрузилась](./photo_2025-02-12_15-25-41.jpg)
