---
## Front matter
title: " Отчёт по третьему этапу проекта"
author: "Паращенко Антонина Дмитриевна"

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

Добавить к сайту достижения.


# Выполнение лабораторной работы

1) Добавить информацию о навыках (Skills). (рис. [-@fig:001])

![Навыки](image/2.JPG){ #fig:001 width=70% }

2) Добавить информацию об опыте (Experience). (рис. [-@fig:002])

![Навыки](image/4.JPG){ #fig:002 width=70% }

3) Добавить информацию о достижениях (Accomplishments). (рис. [-@fig:003]) 

![Достижения](image/6.JPG){ #fig:003 width=70% }

4) Сделать пост по прошедшей неделе. (рис. [-@fig:004])
	
![Пост о прошедшей неделе](image/7.JPG){ #fig:004 width=70% }

5) Добавить пост на тему по выбору: язык разметки Markdown. (рис. [-@fig:005])

![Пост markdown](image/8.JPG){ #fig:005 width=70% }

# Выводы

Добавила на сайт свои достижения и тренировала навыки работы в markdown.
