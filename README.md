# Практическая работа №2

## Варианты и задания

**Вариант 5. Среднее арифметическое.**На вход подаётся число 𝑛 ∈ N : 𝑛 ≤ 2147483647, а также 𝑛 чисел 𝑥𝑖 ∈ Z : |𝑥𝑖| ≤ 2147483647 для любого целого 𝑖 от 1 до 𝑛. Вывести значение среднего арифметического от всех 𝑥𝑖.

**Вариант 16. Разность сумм нечётных и чётных кубов.** На вход подаётся число 𝑛 ∈ N : 𝑛 ≤ 2147483647, а также 𝑛 чисел 𝑥𝑖 ∈ Z : |𝑥𝑖| ≤2147483647 для любого целого 𝑖 от 1 до 𝑛. Вывести значение ∑︁𝑛𝑖=1(−1)𝑖+1·𝑥3𝑖.

## Ход работы

1. Был написан код для каждого из задания.
2. Каждый файл с кодом был скомпилирован и запущен: 
```sh
$ gcc 05_SREDA.C -p 05_SREDA
$ ./05_SREDA
$ gcc 16_rasnosty.c -p 16_rasnosty
$ ./16_rasnosty
```
3. Файлы были загружены на репозиторий:
```sh
$ git checkout -b pr2
$ git add .
$ git commit -m "Single-pass algorithm"
$ git push -u origin pr2
```

## Результаты

Результаты представлены на скриншотах.

**Среднее арифметическое:**
  
<a href="https://imgbb.com/"><img src="https://i.ibb.co/cQwD1bq/image.png" alt="image" border="0"></a>

**Разность сумм нечётных и чётных кубов:**
  
<a href="https://imgbb.com/"><img src="https://i.ibb.co/GP2BfZq/2.png" alt="2" border="0"></a>

## Таблица

| Ресурс          | Ссылка                                                           |
| ------------    | -----------------------------------------------------------------|
| Статья markdown | https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet |
