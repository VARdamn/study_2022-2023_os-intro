---
## Front matter
title: "Отчет об индивидуальном проекте"
subtitle: "Операционные Системы"
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

Создание шаблона сайта и выгрузка шаблона на Github, работа с шаблоном Hugo. 

# Выполнение лабораторной работы

1. Создаю репозиторий на Github, перехожу в папку work и клонирую созданный репозиторий рис. @fig:001).

![Клонирование репозитория](image/pic1.png){#fig:001 width=70%}

2. Перехожу в папку клонированного репозитория, проверяю наличие файлов (рис. @fig:002).

![Проверка файлов](image/pic2.png){#fig:002 width=70%}

3. Выполняю команду ~/bin/hugo (рис. @fig:003).

![Выполнение команды](image/pic3.png){#fig:003 width=70%}

4. Выполняю команду ~/bin/hugo/server, запуская на локальной машине шаблон сайта (рис. @fig:004).

![Выполнение команды для локального запуска шаблона](image/pic4.png){#fig:004 width=70%}

5. Открываю созданный шаблон, запущенный на локальном сервере (рис. @fig:005).

![Шаблон сайта](image/pic5.png){#fig:005 width=70%}

6. Создаю репозиторий VARdamn.github.io, клонирую его (рис. @fig:006).

![Создание и клонирование нового шаблона](image/pic6.png){#fig:006 width=70%} 

7. Сoздаю и переключаюсь на ветку main (рис. @fig:007).

![Переключение на ветку](image/pic7.png){#fig:007 width=70%}

8. Создаю файл README.md, загружаю его в последний созданный репозиторий (рис. @fig:008).

![Создание файла и его выгрузка на репозиторий](image/pic8.png){#fig:008 width=70%}

9. Ввожу команду git submodule (рис. @fig:009).

![Ввод команды](image/pic9.png){#fig:009 width=70%}

10. Прописываю команду ~/bin/hugo, генерируя файлы сайта (рис. @fig:010).

![Команда ~/bin/hugo](image/pic10.png){#fig:010 width=70%}

11. Перехожу в папку public, коммичу созданные файлы в репозиторий (рис. @fig:011).

![Коммит созданных файлов в репозиторий](image/pic11.png){#fig:011 width=70%}

12. Проверяю сделанный коммит - все файлы выгружены в репозиторий. (рис. @fig:012).

![Проверка коммита](image/pic12.png){#fig:012 width=70%}



# Выводы

Я узнал про шаблон для создания сайтов Hugo, создал два репозитория для создания собственного сайта по данному шаблону, выгрузил шаблон на Github.

