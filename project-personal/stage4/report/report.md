---
## Front matter
title: " Отчёт по четвёртому этапу проекта"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы.


# Выполнение лабораторной работы

1) Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте: (рис. [-@fig:001]) - (рис. [-@fig:008])

![eLibrary](image/1.png){ #fig:001 width=70% }

![Google Scholar ](image/2.png){ #fig:002 width=70% }

![ORCID](image/3.png){ #fig:003 width=70% }

![Mendeley](image/4.png){ #fig:004 width=70% }

![ResearchGate](image/5.png){ #fig:005 width=70% }

![Academia.edu](image/6.png){ #fig:006 width=70% }

![arXiv](image/7.png){ #fig:007 width=70% }

![github](image/8.png){ #fig:008 width=70% }

2) Изменить иконки для ссылок на научные ресурсы (рис. [-@fig:009]) - (рис. [-@fig:010])

![md файл](image/9.png){ #fig:009 width=70% }

![На сайте](image/10.png){ #fig:010 width=70% }

5) Сделать пост по прошедшей неделе. (рис. [-@fig:008])
	
![Пост о прошедшей неделе](image/11.png){ #fig:011 width=70% }

6) Добавить пост на тему по выбору: оформление отчёта в markdown (рис. [-@fig:009])

![Пост git](image/12.png){ #fig:012 width=70% }

# Выводы

Добавить к сайту ссылки на научные и библиометрические ресурсы.
