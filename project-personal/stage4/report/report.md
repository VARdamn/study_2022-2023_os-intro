---
## Front matter
title: "Отчет об индивидуальном проекте"
subtitle: "Этап 4"
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

Добавить ссылки на профили в 8 различных сайтах, сделать пост о прошедшей неделе, сделать пост на тему по выбору (создание презентации).

# Выполнение лабораторной работы

1. Добавляю ссылки на профили в различных сайтах в файле ~/work/blog/content/authors/admin/index.md. (рис. @fig:001).

![Добавление ссылок на профили](image/pic1.png){#fig:001 width=70%}

2. Получаю следующий результат (рис. @fig:002).

![Ссылки на профили](image/pic2.png){#fig:002 width=70%}

3. Создаю новый пост по прошедшей неделе командой ~bin/hugo/server new post/week17.04 (рис. @fig:003).

![Создание нового поста](image/pic3.png){#fig:003 width=70%}

4. Пишу пост (рис. @fig:004).

![Написание поста](image/pic4.png){#fig:004 width=70%}

5. Запускаю сайт на локальной машине и проверяю написанный пост (рис. @fig:005).

![Пост по прошедшей неделе](image/pic5.png){#fig:005 width=70%}

6. Создаю новый пост на тему "Создание презентации" командой ~/bin/hugo new post/createPresentation (рис. @fig:006).

![Создание шаблона нового поста](image/pic6.png){#fig:006 width=70%}

7. Пишу пост, проверяю результат (рис. @fig:007).

![Написание нового поста и проверка](image/pic7.png){#fig:007 width=70%}

# Выводы

Я добавил ссылки на свои профили на различных сайтах, написал пост по прошедшей неделе, также я написал пост о создании презентаций.

