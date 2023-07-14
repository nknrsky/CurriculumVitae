# Nikita Kravtsov

![Profile Picture](https://i.imgur.com/iIUL2ER.png)

***

## PERSONAL INFO

* Date of birth: 26.08.04
* Address: Belarus, Mogilev

***

## CONTACT INFO

* [Telegram](https://t.me/nikanorsky)
* [VK](https://vk.com/nikanorsky)
* Phone: +375 (29) XXX-82-08
* Email: <kravvvvvtsov@gmail.com>

***

## ABOUT ME

My name is Nikita Kravtsov. I'm a second-year student at the Belarusian-Russian University. My specialization is software engineering. At this moment I'm looking for a job opportunities and I'm open to any offers and projects. My main goal is to take part in many interesting projects, meet new people with the same interests and learn new things about IT-sphere. My best character traits are responsibility and patience, determination and creativity, which in my point of view are the most important in IT.

***

## SKILLS

* Programming languages:
  * C#
  * SQL
  * JavaScript
* Databases
  * MS Access
  * MS SQL Server
* Other
  * HTML
  * CSS


***

## CODE EXAMPLE

```C#
namespace Fibonacci
{
    class Program
    {
        static long[] numbers;
 
        static long Fib(int n)
        {
            if (0 == numbers[n])
            {
                numbers[n] = Fib(n - 1) + Fib(n - 2);
            }
            return numbers[n];
        }
 
 
        static void Main()
        {
            Console.Write("n = ");
            int n = int.Parse(Console.ReadLine());
            numbers = new long[n + 2];
            numbers[1] = 1;
            numbers[2] = 1;
            long result = Fib(n);
            Console.WriteLine("fib({0}) = {1}", n, result);
            Console.ReadKey();
        }
    }
}
```

***

## EXPERIENCE

* As part of the course project to the discipline "Databases" was developed a program to record information about foreign students studying at the university
* As part of the course project to the discipline "Computer Graphics" was developed game application in the genre of Endless Runner
* As part of the course project to the discipline "Programming" was developed program for ticket sales accounting

***