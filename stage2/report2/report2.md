---
## Front matter
title: "Прохождение внешнего курса"
subtitle: Этап №2"
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

Я перешла на второй этап курса

![Начало второго этапа](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-38-11.png){#fig:001 width=70%}

1. Удаленный сервер - это компьютер, находящийся в дата-центре, к которому можно получить удаленный доступ через сеть Интернет. Удаленный сервер обычно используется для размещения веб-сайтов, приложений, баз данных и других сервисов, которые необходимы для функционирования сайта или бизнес процессов компании. Пользователи могут получить доступ к удаленному серверу с помощью протоколов удаленного доступа, таких как RDP, VNC или SSH.

![Задание 1](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-38-41.png){#fig:002 width=70%}

2. Только id_rsa.pub подходит, так какк он открытый

![Задание 2](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-39-11.png){#fig:003 width=70%}

3. -r = Recursively copy entire directories. Note that scp follows symbolic links encountered in the tree traversal.

![Задание 3](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-39-40.png){#fig:004 width=70%}

4. Сначала проверяем интерент соединение а потом сервер на существование такой программы

![Задание 4](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-40-05.png){#fig:005 width=70%}

5. FileZilla — свободный многоязычный проект, посвящённый приложениям для FTP. Включает в себя отдельное приложение «FileZilla Client» (являющееся FTP-клиентом), и «FileZilla Server». Приложения публикуются с открытым исходным кодом для Windows, macOS и Linux. Клиент поддерживает FTP, SFTP, и FTPS (FTP через SSL/TLS) и имеет настраиваемый интерфейс с поддержкой смены тем оформления.

![Задание 5](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-40-55.png){#fig:006 width=70%}

6. Сначала проверяем версии этой программы зпьни настраиваем сервер, чтобы он выводил информацию непосредственно на экран

![Задание 6](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-41-25.png){#fig:007 width=70%}

7. Стандартные справочные команды - help и man

![Задание 7](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-42-03.png){#fig:008 width=70%}

8. FastQC supports files in the following formats 
FastQ (all quality encoding variants) Casava FastQ files* Colorspace FastQ GZip compressed FastQ SAM BAM SAM/BAM Mapped only (normally used for colorspace data)

![Задание 8](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-42-33.png){#fig:009 width=70%}

9. Комбинация Ctrl+С - завершает процесс. Комбинация Ctrl+Z - приостанавливает процесс.

![Задание 9](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-43-43.png){#fig:010 width=70%}

![Задание 10](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-44-42.png){#fig:011 width=70%}

11. Если сигнал не перехватывается процессом, процесс уничтожается. Следовательно, это используется для изящного завершения процесса. Команда «kill -9» отправляет сигнал уничтожения для немедленного завершения любого процесса, если он присоединен к PID или имени процесса . Это принудительный способ убить/завершить набор процессов

![Задание 11](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-45-04.png){#fig:012 width=70%}

12. Команда kill шлёт сигнал о завершении процесса. Но программа обрабатывает сигналы только когда она исполняется, пока она остановлена она не может обработать сигнал и приступит к его обработке только после продолжения работы.

![Задание 12](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-45-30.png){#fig:013 width=70%}

13. Запущенная программа потребляет ресурсы CPU, а остановленная нет.

![Задание 13](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-45-56.png){#fig:014 width=70%}

14. Приостановленное приложение не выполняет новых действий, поэтому не занимает вычислительные ресурсы компьютера (CPU 0%). При этом, в оперативной памяти оно сохранится, поэтому оно будет занимать столько же оперативной памяти, сколько до постановки на паузу.

![Задание 14](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-46-23.png){#fig:015 width=70%}

15. Принудительно завершать отдельный поток нельзя — это может сломать программу. Потоки должны завершаться корректно, например, по флагу или сигналу.

![Задание 15](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-46-52.png){#fig:016 width=70%}

![Задание 16](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-48-00.png){#fig:017 width=70%}

![Задание 17](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-48-56.png){#fig:018 width=70%}

18. Для завершения работы tmux нужна команда exit

![Задание 18](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-49-23.png){#fig:019 width=70%}

19. Так как мы заходили на сервер с терминала который закрыли, tmux продолжит свою работу на сервере 

![Задание 19](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-50-06.png){#fig:020 width=70%}

20. Ещё будет предупреждение о том, что работа завершится. Запущенный процесс во вкладке, конечно же, при её закрытии, пропадёт.

![Задание 20](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-51-26.png){#fig:021 width=70%}

21. Ctrl+b c - создать новое окно;
Ctrl+b w - выбрать окно из списка;
Ctrl+b 0-9 - открыть окно по его номеру;
Ctrl+b , - переименовать текущее окно;
Ctrl+b % - разделить текущую панель по горизонтали;
Ctrl+b ” - разделить текущую панель по вертикали;
Ctrl+b стрелка - перейти на панель, находящуюся в стороне, куда указывает стрелка
Ctrl+b Ctrl+стрелка - изменить размер текущей панели;
Ctrl+b o - перейти на следующую панель;
Ctrl+b ; - переключаться между текущей и предыдущей панелью;
Ctrl+b x - закрыть текущую панель;
Ctrl+b ( - войти в режим копирования) - вставить из внутреннего буфера обмена tmux;
Ctrl+b d - отключится от текущей сессии;
Ctrl+b : - открыть командную строку.

![Задание 21](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-51-54.png){#fig:022 width=70%}

22. Можно закрыть одно из делений вкладки выполнив команды Ctrl+B и Х. По половинам “разделенной” вкладки можно перемещаться при помощи Ctrl+B и стрелок - как описано в задании выше.
Делить экран можно только в текущей вкладке tmux, а не во всех вкладках одновременно

![Задание 22](/home/eeprozorova/work/course/outsidecourse/stage2/report2/image/2025-05-31_16-52-38.png){#fig:023 width=70%}

# Вывод

Я закончила второй этап внешнего курса и перехожу к третему.

:::
