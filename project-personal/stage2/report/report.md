---
## Front matter
title: "Отчет об индивидуальном проекте"
subtitle: "Этап 2"
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

Научиться добавлять на сайт различные данные: данные о себе, посты, картинки.

# Выполнение лабораторной работы

1. Копирую в папку ~/work/blog/public/authors/admin новую аватарку. (рис. @fig:001).

![Копирование новой аватарки](image/pic1.png){#fig:001 width=70%}

2. Редактирую информацию о себе: краткое описание, информация об интересах и об образовании (рис. @fig:002).

![Редактирование информации о себе](image/pic2.png){#fig:002 width=70%}

3. Запускаю сайт на локальной машине командой ~/bin/hugo server и проверяю результат (рис. @fig:003).

![Проверка изменений](image/pic3.png){#fig:003 width=70%}

4. Создаю новый пост о прошедшей неделе командой ~/bin/hugo new post/last_week (рис. @fig:004).

![Пост о прошедшей неделе](image/pic4.png){#fig:004 width=70%}

5. Редактирую md-файл для этого поста (рис. @fig:005).

![Редактирование поста](image/pic5.png){#fig:005 width=70%}

6. Запускаю сайт и проверяю созданный пост (рис. @fig:006).

![Проверка поста](image/pic6.png){#fig:006 width=70%}

7. Создаю еще один пост о системе контроля версий Git (рис. @fig:007).

![Пост о Git VCS](image/pic7.png){#fig:007 width=70%}

8. Редактирую содержимое поста: добавляю информацию, также добавляю картинку для поста (рис. @fig:008).

![Редактирование поста](image/pic8.png){#fig:008 width=70%}

9. Проверяю созданный пост о системе контроля версий (рис. @fig:009).

![Проверка нового поста на сайте](image/pic9.png){#fig:009 width=70%}

# Выводы

Я научился редактировать информацию о себе, узнал как создавать и редактировать посты, картинки к ним

