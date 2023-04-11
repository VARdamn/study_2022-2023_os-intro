---
## Front matter
title: "Лабораторная Работа №10"
subtitle: "Программирование в командном процессоре ОС UNIX. Командные файлы"
author: "Барсегян Вардан Левонович"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

# Выполнение лабораторной работы

1. Создаю папку backup для резервного копирования, создаю файла для первого скрипта и открываю его (рис. @fig:001).

![Создание папки, файла для скрипта](image/pic1.png){#fig:001 width=70%}

2. С помощью команды man изучаю опции и использование архиватора tar (рис. @fig:002).

![man tar](image/pic2.png){#fig:002 width=70%}

3. Код первого скрипта (рис. @fig:003).

![Код первого скрипта](image/pic3.png){#fig:003 width=70%}

4. Запускаю скрипт и проверяю его работу - в папке backup создался архив с файлом этого скрипта. (рис. @fig:004).

![Проверка работы скрипта](image/pic4.png){#fig:004 width=70%}

5. Создаю файл для второго скрипта, делаю файл исполняемым, запускаю в редакторе (рис. @fig:005).

![Создание файла, изменение прав доступа, открытие в редакторе](image/pic5.png){#fig:005 width=70%}

6. Код второго скрипта (рис. @fig:006).

![Код второго скрипта](image/pic6.png){#fig:006 width=70%}

7. Проверка работы второго скрипта (рис. @fig:007).

![Проверка работы скрипта](image/pic7.png){#fig:007 width=70%}

8. Создаю файл для третьего скрипта, делаю файл исполняемым, запускаю в редакторе (рис. @fig:008).

![Создание файла, изменение прав доступа, открытие в редакторе](image/pic8.png){#fig:008 width=70%}

9. Код третьего скрипта (рис. @fig:009).

![Код третьего скрипта](image/pic9.png){#fig:009 width=70%}

10. Проверка работы третьего скрипта (рис. @fig:010).

![Проверка работы скрипта](image/pic10.png){#fig:010 width=70%}

11. Создаю файл для четвертого скрипта, делаю файл исполняемым, запускаю в редакторе (рис. @fig:011).

![Создание файла, изменение прав доступа, открытие в редакторе](image/pic11.png){#fig:011 width=70%}

12. Код четвертого скрипта (рис. @fig:012).

![Код четвертого скрипта](image/pic12.png){#fig:012 width=70%}

13. Проверка работы четвертого скрипта (рис. @fig:013).

![Проверка работы скрипта](image/pic13.png){#fig:013 width=70%}

# Выводы

Я изучил основы программирования в оболочке ОС UNIX/Linux, узнал множество различных команд, узнал про циклы, ветвления и прочие конструкции. Написал 4 скрипта (командные файлы)

