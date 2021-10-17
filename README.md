# Обобщения, ограничения обобщений, наследование обобщенных типов или параметризированные классы.

## Оглавление

1. [Обобщения](#Обобщения)
    1. [Значения по умолчанию](#Маркированный)
    2. [Статические поля обобщенных классов](#Нумерованный)
    3. [Использование нескольких универсальных параметров](#Смешанные-списки)
    4. [Обобщенные методы](#Список-задач)


## Обобщения


```C#
using MarkdownSharp;
using MarkdownSharp.Extensions.Mal;

Markdown mark = new Markdown();

// Short link for MAL - 
// http://myanimelist.net/people/413/Kitamura_Eri => mal://Kitamura_Eri
mark.AddExtension(new Articles()); 
mark.AddExtension(new Profile());

mark.Transform(text);
```
