
# Collections & Enums

In C#, collections and enums are important language features that help in organizing and manipulating data. Collections provide a way to store and manage groups of related objects, while enums allow you to define a set of named values as symbolic constants.

Collections in C#:
C# provides several built-in collection classes in the .NET Framework that you can use to store and manipulate data. Some commonly used collection classes are:

1. Arrays: Arrays are fixed-size, ordered collections of elements of the same type. They have a fixed length that is defined at the time of declaration.

```C#
int[] numbers = new int[5] { 1, 2, 3, 4, 5 };

```

2. Lists: Lists are dynamic, resizable collections of elements of the same type. They provide additional methods and flexibility compared to arrays.

```C#
 List<int> numbers = new List<int>() { 1, 2, 3, 4, 5 };

```

Enums in C#:
Enums allow you to define a set of named values that represent symbolic constants. Enumerations are often used when you have a fixed set of values that a variable can take.

```C#
enum DaysOfWeek
{
    Monday,
    Tuesday,
    Wednesday,
    Thursday,
    Friday,
    Saturday,
    Sunday
}

DaysOfWeek today = DaysOfWeek.Monday;

```

Enums can be useful when you want to improve the readability and maintainability of your code by using descriptive names for values instead of hard-coded numbers.

These are just a few examples of collections and enums in C#. Depending on your specific requirements, you may need to use different collection classes or customize enums to suit your needs.


## Things I want to know more about

to be expert in this topic