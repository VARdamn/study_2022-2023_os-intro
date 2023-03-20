---
## Front matter
title: "Лабораторная Работа №7"
subtitle: "Командная оболочка Midnight Commander"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций
с ними.

# Выполнение лабораторной работы

## Задание по mc

1. Читаю справку по команде mc (рис. @fig:001).

![man mc](image/pic1.png){#fig:001 width=70%}

2. Запускаю оболочку mc, изучаю его структуру и меню (рис. @fig:002).

![Запуск mc](image/pic2.png){#fig:002 width=70%}

3. Выполняю несколько операций в mc: выделение и отмена выделения файла (рис. @fig:003), копирование файла (рис. @fig:004), перемещение файла (рис. @fig:005), информация (рис. @fig:006), информация о правах доступа файла, его владельце (рис. @fig:007)

![Выделение файла](image/pic3.png){#fig:003 width=70%}

![Копирование файла](image/pic4.png){#fig:004 width=70%}

![Перемещение файла](image/pic5.png){#fig:005 width=70%}

![Информация](image/pic6.png){#fig:006 width=70%}

![Информация о правах доступа файла](image/pic7.png){#fig:007 width=70%}

4. Открываю меню левой панели (рис. @fig:008)

![Меню левой панели](image/pic8.png){#fig:008 width=70%}

5. Просматриваю в данном меню дерево каталогов (рис. @fig:009), информацию о каталоге (рис. @fig:010)

![Дерево каталогов](image/pic9.png){#fig:009 width=70%}

![Информация о каталоге](image/pic10.png){#fig:010 width=70%}

6. Просматриваю содержимое текстового файла, используя клавишу F3 (рис. @fig:011)

![Просмотр содержимого файла](image/pic11.png){#fig:011 width=70%}

7. Открываю файл для редактирования, используя клавишу F4 (рис. @fig:012)

![Редактирование файла](image/pic12.png){#fig:012 width=70%}

8. Создаю новый каталог, используя клавишу F7 (рис. @fig:013)

![Создание каталога](image/pic13.png){#fig:013 width=70%}

9. Копирую файл в данный каталог, используя клавишу F5 (рис. @fig:014)

![Копирование файла в каталог](image/pic14.png){#fig:014 width=70%}

10. В подменю Команда произвожу поиск файла с заданными условиями (рис. @fig:015)

![Поиск файла](image/pic15.png){#fig:015 width=70%}

11. История предыдущей команды (рис. @fig:016)

![История предыдущей команды](image/pic16.png){#fig:016 width=70%}

12. С помощью дерева каталогов перехожу в домашнюю папку (рис. @fig:017)

![Переход в домашнюю папку](image/pic17.png){#fig:017 width=70%}

13. Открываю анализ файла меню (рис. @fig:018)

![Анализ файла меню](image/pic18.png){#fig:018 width=70%}

14. Открываю анализ файла расширений (рис. @fig:019)

![Анализ файла расширений](image/pic19.png){#fig:019 width=70%}

15. В подменю настройки открываю изменение внешнего вида редактора (рис. @fig:020)

![Настройки конфигурации](image/pic20.png){#fig:020 width=70%}

## Задание по встроенному редактору mc

1. Создаю файл text.txt (рис. @fig:021)

![Создание файла](image/pic21.png){#fig:021 width=70%}

2. Открываю этот файл с помощью встроенного в mc редактора (рис. @fig:022)

![Открытие файла](image/pic22.png){#fig:022 width=70%}

3. Вставляю в этот файл текст (рис. @fig:023)

![Вставка текста](image/pic23.png){#fig:023 width=70%}

4. Удаляю строку текста, используя Сtrl+y (рис. @fig:024)

![Удаление строки](image/pic24.png){#fig:024 width=70%}

5. Выделяю фрагмент текста и копирую его, используя F3, F5 (рис. @fig:025)

![Выделение фрагмента и его копирование](image/pic25.png){#fig:025 width=70%}

6. Выделяю фрагмент текста и пермещаю его, используя F3, F6 (рис. @fig:026)

![Выделение фрагмента и его перемещение](image/pic26.png){#fig:026 width=70%}

7. Сохраняю файл, используя F2 (рис. @fig:027)

![Сохранение изменений](image/pic27.png){#fig:027 width=70%}

8. Отменяю последнее действие, используя Ctrl+U (рис. @fig:028)

![Отмена последнего действия](image/pic28.png){#fig:028 width=70%}

9. Перехожу сначала в конец файла (сочетание Ctrl+End), пишу текст, далее перехожу в начало файла (сочетание Ctrl+Home), пишу текст (рис. @fig:029)

![Ввод текста в начале и конце файла](image/pic29.png){#fig:029 width=70%} 

10. В файле с настройкой подсветки синтаксиса редактора mc нахожу include unknown.syntax, меняю на unclude sh.syntax (рис. @fig:030)

![Настройка подсветки синтаксиса](image/pic30.png){#fig:030 width=70%}

11. Открываю С файл в mc, теперь подсветка синтаксиса работает (рис. @fig:031)

![Подсветка синтаксиса включена](image/pic31.png){#fig:031 width=70%}

# Выводы

Я научился углубленно работать с мс, освоил множество горячих клавиш данного редактора, изучил меню различных настроек и конфигураций, приобрел практические навыки по работе, просмотру, редактированию файлов и каталогов через midnight commander, включил подсветку синтаксиса.

