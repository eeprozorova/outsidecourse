---
title: Прохождение внешнего курса
subtitle: Третий этап
author:
  - Прозорова Е. Е.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 15 апреля 2025 

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Прозорова Елизавета Евгеньевна
  * студент факультета ФМиЕН
  * группа НММбд-03-24
  * Российский университет дружбы народов
  * [1132246767@pfur.ru](mailto:1132246767@pfur.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

# Вводная часть

## Цели и задачи

- прохождение внешнего курса "Введение в Linux"

# Выполнение лабораторной работы

Я начала третий и заключительный этап курса

![Начало третьего этапа](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_16-55-13.png){#fig:001 width=70%}

##

1. • ZQ - выйти без сохранения
• :q! - выйти без сохранения
• ZZ - записать файл и выйти (если файл не изменяли, то записываться он не будет)
• :wq - записать файл и выйти
• :x - записать файл и выйти
• :w - записать файл
• :sav filename - “сохранить как”
• :w filename - “сохранить как”
• :w! - записать файл

![Задание 1](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_16-56-15.png){#fig:002 width=70%}

##

2. Strange_ TEXT is_here. 2=2 YES!
Точка считается “маленьким словом”, так что всего их 9: Strange_, is_here, ., 2, =, 2, ! и два лишних пробела. И если посчитать нажатия на w и на W, то действительно после 10 штук попадем в одно место. 10 нажатий на W, это то же самое, что и 10 нажатий на w

![Задание 2](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-32-33.png){#fig:003 width=70%}

##

3. • $ — в конец текущей строки;
• w — на слово вправо;
• b — на слово влево;
• i — начать ввод перед курсором;
• p — вставка содержимого неименнованного буфера под курсором;
• P — вставка содержимого неименованного буфера перед курсором;
• yy (также Y) — копирование текущей строки в неименованный буфер;
• yy — копирование числа строк начиная с текущей в неименованный буфер

![Задание 3](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-33-16.png){#fig:004 width=70%}

##

4. Команда $ — в конец текущей строки, W - до пробела вправо - то есть, перемещение.
Нажать Esc достаточно один раз, но да ладно.
Надпись visual - горит.
d — используется совместно с командами перемещения. Удаляет символы с текущего положения курсора до положения после ввода команды перемещения.
yy (также Y) — копирование текущей строки в буфер;

![Задание 4](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-34-31.png){#fig:005 width=70%}

##

5. Только из набора С, так как у каждой оболочки свой буфер который при выходе будет записываться в файл истории

![Задание 5](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-35-02.png){#fig:006 width=70%}

##

6. Эта директория, потому что в этой мы создаем новый файл и только после этого переходим в другую папку.

![Задание 6](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-35-36.png){#fig:007 width=70%}

##

7. мя не может начинаться с цифры и содержать специальные символы или пробелы (только буквы и цифры)

![Задание 7](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-37-08.png){#fig:008 width=70%}

##

8. $ echo опции строка Эта команда печатает строки, которые передаются в качестве аргументов в стандартный вывод и обычно используется в сценариях оболочки для отображения сообщения или вывода результатов других команд.
var1=$1 - обозначение переменных
var2=$2
echo "Arguments are: \$1=$var1 \$2=$var2" - строка печати.

![Задание 8](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-38-38.png){#fig:009 width=70%}

##

9. 3 не больше 5, 3 не меньше 3, 3 не равно 4.
5 не больше 5, 5 не меньше 3, 5 не равно 4.
Оба раза выведет four

![Задание 9](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-40-45.png){#fig:010 width=70%}

##

10. • (Start)
• a > c нет (Finish)
• (Start)
• , > c нет (Finish)
• (Start)
• b > c нет (Finish)
• (Start)
• , > c нет (Finish)
• (Start)
• c_d > c да

![Задание 10](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-41-21.png){#fig:011 width=70%}

##

11. • a = $a
• a += b это то же самое, что и a = a + b, но с символами “+=” != “=+"
• 3. если выражение не в скобках, но с пробелами - работать не будет. (let a=a+b - сработает; let a = a + b - нет)

![Задание 11](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-43-20.png){#fig:012 width=70%}

##

12. Выведет путь до директории в которую мы перешли так как pwd - команда.

![Задание 12](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-45-49.png){#fig:013 width=70%}

##

13. Программа выполняет стандартный вывод в терминал нам просто нужно настроить вывод в файл.

![Задание 13](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-46-20.png){#fig:014 width=70%}

##

14. -iname ищет без учета регистар а -name в так как в запросе. Звезда после слова - после слова может быть сколько угодно символов

![Задание 14](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-47-40.png){#fig:015 width=70%}

##

15. find [path] [expression]
path - это путь к директории, в которой нужно выполнить поиск файлов (по умолчанию, поиск производится в текущей директории и всех ее поддиректориях);
expression - это выражение, которое определяет критерии поиска файлов.
-name: поиск файлов по имени. Например: find /home/user -name myfile.txt

![Задание 15](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-48-20.png){#fig:016 width=70%}

##

16. Текущий каталог - это depth=1, а остальное считается просто:
/home/bi -> depth=1
/home/bi/dir1 -> depth=2
/home/bi/dir1/dir2 -> depth=3

![Задание 16](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-49-11.png){#fig:017 width=70%}

##

17. Описания man: Print NUM lines of trailing context after/before matching lines “matching lines” - множественное число, строки в которых нашлось совпадение

![Задание 17](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-49-53.png){#fig:018 width=70%}

##

![Задание 18](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-51-10.png){#fig:019 width=70%}

##

![Задание 19](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-52-21.png){#fig:020 width=70%}



![Задание 20](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_18-53-36.png){#fig:021 width=70%}

##

![Задание 21](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-18-32.png){#fig:022 width=70%}

##

22. Cначала идет команда установки подписей, а потом в скобках: подпись - пробел - переменная с координатой - запятая
Повторяется это количество раз соответствующее числу переменных, и без запятой (в случае с последней переменной)
А подпись в свою очередь получается конкатенацией текста из задания и переменной с координатой

![Задание 22](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-19-45.png){#fig:023 width=70%}

##

23. • r - чтение;
• w - запись;
• x - выполнение;
• s - выполнение от имени суперпользователя (дополнительный);
• u - владелец файла;
• g - группа файла;
• o - все остальные пользователи;
• 0 - никаких прав;
• 1 - только выполнение;
• 2 - только запись;
• 3 - выполнение и запись;
• 4 - только чтение;
• 5 - чтение и выполнение;
• 6 - чтение и запись;
• 7 - чтение запись и выполнение.

![Задание 23](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-21-11.png){#fig:024 width=70%}

##
24. • wc -l вывести количество строк
• wc -c вывести количество байт
• wc -m вывести количество символов
• wc -L вывести длину самой длинной строки
• wc -w вывести количество слов

![Задание 24](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-26-20.png){#fig:025 width=70%}

##

25. h, –human-readable print sizes in human readable format (e.g., 1K 234M 2G)
-s, –summarize display only a total for each argument

![Задание 25](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-26-47.png){#fig:026 width=70%}

##

26. Данная команда создает сразу 3 директории от dir1 до dir3

![Задание 26](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-27-27.png){#fig:027 width=70%}

# Сертификат

![Полученный сертификат](/home/eeprozorova/work/course/outsidecourse/stage3/report3/image/2025-05-31_19-29-06.png){#fig:028 width=70%}

# Вывод

Я полностью прошла внешний курс и изучила Linux и работу с ним.

:::

