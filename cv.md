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
