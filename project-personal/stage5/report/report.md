---
## Front matter
title: "Отчет об индивидуальном проекте"
subtitle: "Этап 5"
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

Сделать записи для персональных проектов, сделать пост о прошедшей неделе, сделать пост на тему по выбору (научные языки программирования).

# Выполнение лабораторной работы

1. Создаю новый пост по прошедшей неделе командой ~bin/hugo/server new post/week01.05 (рис. @fig:001).

![Создание нового поста](image/pic1.png){#fig:001 width=70%}

2. Пишу пост и проверяю результат (рис. @fig:002).

![Написанный пост и результат](image/pic2.png){#fig:002 width=70%}

3. Редактирую первый проект: меняю тег, ссылки, описание, добавляю ссылку на репозиторий. (рис. @fig:003).

![Редактирование первого проекта](image/pic3.png){#fig:003 width=70%}

4. Меняю slides для первого проекта - пишу туда инструкцию для использования бота (рис. @fig:004).

![Папка slides первого проекта](image/pic4.png){#fig:004 width=70%}

5. Аналогично редактирую второй проект, получаю следующий результат (рис. @fig:005).

![Отредактированные проекты](image/pic5.png){#fig:005 width=70%}

6. Создаю новый пост на тему "Научные языки программирования" командой ~/bin/hugo new post/scientificProgLangs (рис. @fig:006).

![Создание шаблона нового поста](image/pic6.png){#fig:006 width=70%}

7. Пишу пост, проверяю результат (рис. @fig:007).

![Написание нового поста и проверка](image/pic7.png){#fig:007 width=70%}

# Выводы

Я сделал записи для персональных проектов, написал пост по прошедшей неделе, также я написал пост о научных языках программирования.

