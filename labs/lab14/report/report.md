---
## Front matter
title: "Отчёт по лабораторной работе №14"
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

Приобретение практических навыков работы с именованными каналами.

# Ход лабораторной работы
1) В домашнем каталоге создаём файлы common.h server.c client.c makefile (рис. [-@fig:001])

![Создание файлов](image/1.png){ #fig:001 width=70% }

2) Пишем скрипт файла common.h (рис. [-@fig:002])
 
![Скрипт](image/2.png){ #fig:002 width=70% }

3) Пишем скрипт файла server.c (рис. [-@fig:003])

![Скрипт](image/3.png){ #fig:003 width=70% }

4) Пишем скрипт файла client.c (рис. [-@fig:004])

![Скрипт](image/4.png){ #fig:004 width=70% }

5) Пишем скрипт файла makefile (рис. [-@fig:005]) 

![Скрипт](image/5.png){ #fig:005 width=70% }

6) Скомпилируем файлы с помощью команды make all (рис. [-@fig:006])

![Компиляция](image/6.png){ #fig:006 width=70% }

7) Проверяем работу написанной программы. Открываем 3 консоли и в запускаем ./server.c, а в других двух ./client.c и видим результат работы. (рис. [-@fig:007]) 

![Скрипт кода](image/7.png){ #fig:007 width=70% }

8) Если сервер завершит свою работу, не закрыв канал, то, когда мы будем запускать этот сервер снова, появится ошибка "Невозможно создать FIFO", так как у нас уже есть один канал.

# Вывод
Приобрела практические навыки работы с именованными каналами.
