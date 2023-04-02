---
## Front matter
title: "Отчет об индивидуальном проекте"
subtitle: "Этап 3"
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

Оформить список достижений на сайте (информация о навыках, опыте, достижениях), сделать пост о прошедшей неделе, сделать пост на тему по выбору.

# Выполнение лабораторной работы

1. Редактирую список достижений на сайте - информацию о навыках в файле ~/work/blog/content/index.md. Получаю следующий результат (рис. @fig:001).

![Редактирование информации о навыках](image/pic1.png){#fig:001 width=70%}

2. Редактирую список достижений на сайте - информацию об опыте в файле ~/work/blog/content/index.md. Получаю следующий результат (рис. @fig:002).

![Редактирование информации об опыте](image/pic2.png){#fig:002 width=70%}

3. Редактирую список достижений на сайте - информацию о достижениях в файле ~/work/blog/content/index.md. Получаю следующий результат (рис. @fig:003).

![Редактирование информации о достижениях](image/pic3.png){#fig:003 width=70%}

4. Создаю новый пост по прошедшей неделе командой ~/bin/hugo new post/week27.03 (рис. @fig:004).

![Создание шаблона нового поста](image/pic4.png){#fig:004 width=70%}

5. Пишу пост, запускаю сайт на локальной машине, получаю следующий результат (рис. @fig:005).

![Пост по прошедшей неделе](image/pic5.png){#fig:005 width=70%}

6. Создаю новый пост на тему "Язык разметки LaTeX" командой ~/bin/hugo new post/LaTeXMarkup (рис. @fig:006).

![Создание шаблона нового поста](image/pic6.png){#fig:006 width=70%}

7. Редактирую шаблон поста (рис. @fig:007).

![Редактирование нового поста](image/pic7.png){#fig:007 width=70%}

8. Перезапускаю сайт, открываю полученный пост (рис. @fig:008).

![Пост о языке разметки LaTeX](image/pic8.png){#fig:008 width=70%}

# Выводы

Я отредактировал список достижений (информация о навыках, опыте, достижениях), написал пост по прошедшей неделе, также я написал пост о языке разметки LaTeX.

