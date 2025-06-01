---
## Front matter
title: "Прохождение внешнего курса"
subtitle: Этап №1"
author: "Елизавета Евгеньевна Прозорова"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

- прохождение внешнего курса "Введение в Linux"

# Выполнение лабораторной работы

Итак я начала внешний курс

![Начало прохожденения](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_15-58-02.png){#fig:001 width=70%}

1. Курс называется "Введение в Linux"

![Задание 1](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_15-58-57.png){#fig:002 width=70%}

2. Ответы были выбраны в соответствии с описаными критериями

![Задание 2]](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_15-58-58.PNG){#fig:003 width=70%}

3. Лично я пользуюсь только Windows, но отметила также и линукс.

![Задание 3](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_15-58-59.PNG){#fig:004 width=70%}

4. VirtualBox - это программа для запуска одной ос на другой

![Задание 4](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-15-50.png){#fig:005 width=70%}

5. У меня действительно получилось установить и запустить машину

![Задание 5](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-16-12.png){#fig:006 width=70%}

6. Формат deb - это стандартный формат пакетов программного обеспечения для операционных систем семейства Debian (Debian, Ubuntu, Mint и т.д.)

![Задание 6](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-21-36.png){#fig:007 width=70%}

7. Менеджер обновлений — это программа для обновления установленного программного обеспечения в дистрибутивах ОС Linux, основанных на Debian или использующих систему управления пакетами APT. Менеджер обновлений устанавливает обновления безопасности или просто улучшающие функциональность программы.

![Задание 7](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-22-32.png){#fig:008 width=70%}

8. Здесь подходят только - Консоль и Терминал остальные варианты не имеют значения

![Задание 8](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-23-10.png){#fig:009 width=70%}

9. Интерфейс Linux - регистрозависимый поэтому только pwd

![Задание 9](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-23-52.png){#fig:010 width=70%}

10. В данном случае подходят все варианты так как Linux - регистрозависимый.

![Задание 10](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-25-10.png){#fig:011 width=70%}

11. Так как я нахожусь в другой директории то мне нужно прописать полный путь до Downloads

![Задание 11](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-26-02.png){#fig:012 width=70%}

12. rm -r - это удаление директорий и рекурентное удаление файлов находящихся в ней.

![Задание 12](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-26-48.png){#fig:013 width=70%}

13. Я проверила это просто введя в консоль

![Задание 13](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-27-38.png){#fig:014 width=70%}

14. Это комбинация для запуска программы в фоновом режиме

![Задание 14](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-27-38.png){#fig:015 width=70%}

15. По моему опыту ошибки автоматически выводятся на экран

![Задание 15](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-29-32.png){#fig:016 width=70%}

16. < file — использовать файл как источник данных для стандартного потока ввода.
file — направить стандартный поток вывода в файл. Если файл не существует, он будет создан, если существует — перезаписан сверху.
2> file — направить стандартный поток ошибок в файл. Если файл не существует, он будет создан, если существует — перезаписан сверху.
file — направить стандартный поток вывода в файл. Если файл не существует, он будет создан, если существует — данные будут дописаны к нему в конец.
2»file — направить стандартный поток ошибок в файл. Если файл не существует, он будет создан, если существует — данные будут дописаны к нему в конец.
&>file или >&file — направить стандартный поток вывода и стандартный поток ошибок в файл. Другая форма записи: >file 2>&1.

![Задание 16](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-30-06.png){#fig:017 width=70%}

17. Выполнив инструкции, в итоге всё вывелось на экран

![Задание 17](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-30-47.png){#fig:018 width=70%}

18. q –quiet Turn off Wget’s output

![Задание 18](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-31-51.png){#fig:019 width=70%}

19. При загрузке материалов из Интернета вы часто захотите ограничить поиск только определенными типами файлов. Например, если вы заинтересованы в загрузке GIF-файлов, вы не будете рады получить кучу документов PostScript, и
наоборот.
Wget предлагает две опции для решения этой проблемы. В описании каждой опции перечислены краткое имя, длинное имя и эквивалентная команда в .wgetrc.
‘-A acclist’ ‘–accept acclist’ ‘accept = acclist’ ‘–accept-regex urlregex’ ‘accept-regex =
urlregex’
Аргумент опции '--accept' представляет собой список суффиксов или шаблонов файлов. Таким образом, указав 'wget -A gif,jpg', Wget загрузит только файлы, заканчивающихся на 
A "zelazny*196[0-9]*" загрузит только файлы, начинающиеся с 'zelazny'

![Задание 19](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-32-39.png){#fig:020 width=70%}

20. gzip (сокращение от GNU Zip) — утилита сжатия и восстановления (декомпрессии) файлов, использующая алгоритм Deflate.

![Задание 20](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-33-31.png){#fig:021 width=70%}

21. 

![Задание 21](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-34-16.png){#fig:022 width=70%}

22. c - архиватор
j - указатель на тип архиватора bzip
f - потому что создаем архив в файловой системе

![Задание 22](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-34-40.png){#fig:023 width=70%}

23. ? = один символ
alexey = маленькая буква
И файл должен быть jpeg, а не jpg

![Задание 23](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-35-07.png){#fig:024 width=70%}

24. Здесь регистр - маленькая буква, слово - world, а не word

![Задание 24](/home/eeprozorova/work/course/outsidecourse/stage1/report1/image1/2025-05-31_16-35-49.png){#fig:025 width=70%}

# Вывод

Я закончила первый этап внешнего курса.

:::
