---
## Front matter
title: "Отчёт по лабораторной работе №11"
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

Изучить основы программирования в оболочке ОС UNIX. Научится писать болеесложные командные файлы с использованием логических управляющих конструкцийи циклов

# Ход лабораторной работы
## Задание 1
Используя командыgetopts grep,написать командный файл,который анализируеткомандную строку с ключами (рис. [-@fig:001]) - (рис. [-@fig:004])

![Скрипт](image/1.png){ #fig:001 width=70% }

![Работа программы](image/2.png){ #fig:002 width=70% }

![Работа программы](image/3.png){ #fig:003 width=70% }

![Работа программы](image/4.png){ #fig:004 width=70% }

## Задание 2
Написать на языке Си программу (рис. [-@fig:005]) - (рис. [-@fig:008])

![Создаём файлы](image/5.png){ #fig:005 width=70% }

![Скрипт кода Си](image/6.png){ #fig:006 width=70% }

![Скрипт кода](image/7.png){ #fig:007 width=70% }

![Работа программы](image/8.png){ #fig:008 width=70% }

## Задание 3
Написать командный файл,создающий указанное число файлов,пронумерованных последовательно от 1 до N (рис. [-@fig:009]) - (рис. [-@fig:011])

![Скрипт кода](image/9.png){ #fig:009 width=70% }

![Запуск файла](image/10.png){ #fig:010 width=70% }

![Запуск файла](image/11.png){ #fig:011 width=70% }

## Задание 4
Написать командный файл,который с помощью команды tar запаковывает в архив все файлы в указанной директории (рис. [-@fig:012]) - (рис. [-@fig:013])

![Скрипт кода](image/12.png){ #fig:012 width=70% }

![Архив](image/13.png){ #fig:013 width=70% }

# Вывод
Изучила основы программирования в оболочке ОС UNIX. Научилась писать болеесложные командные файлы с использованием логических управляющих конструкцийи циклов
