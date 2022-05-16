---
## Front matter
title: "Отчёт по лабораторной работе №9"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Ход лабораторной работы
1) Открываем emacs (рис. [-@fig:001]) 

![emacs](image/1.png){ #fig:001 width=70% }

2) Создаём файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f. (рис. [-@fig:002]) 

![emacs](image/2.png){ #fig:002 width=70% }

3) Набираем данный текст (рис. [-@fig:003]) 

![emacs](image/3.png){ #fig:003 width=70% }

4) Сохраняем файл с помощью комбинации Ctrl-x Ctrl-s 

5) Проделать с текстом стандартные процедуры редактирования (рис. [-@fig:004]) - (рис. [-@fig:010]) 

![Вырезать одной командой целую строку (С-k)](image/4.png){ #fig:004 width=70% }

![Вставить эту строку в конец файла (C-y)](image/5.png){ #fig:005 width=70% }

![Выделить область текста (C-space)](image/6.png){ #fig:006 width=70% }

![Скопировать область в буфер обмена (M-w)](image/7.png){ #fig:007 width=70% }

![Вставить область в конец файла.](image/7.png){ #fig:008 width=70% }

![Вновь выделить эту область и на этот раз вырезать её (C-w)](image/8.png){ #fig:009 width=70% }

![Отмените последнее действие (C-/)](image/10.png){ #fig:010 width=70% }

6) Выполняем команды по перемещению курсора (рис. [-@fig:011]) - (рис. [-@fig:012]) 

![Переместите курсор в начало строки (C-a))](image/11.png){ #fig:011 width=70% }

![Переместите курсор в конец строки (C-e)](image/12.png){ #fig:012 width=70% }

7) Совершаем управление буферами (рис. [-@fig:013]) - (рис. [-@fig:016])

![Вывести список активных буферов на экран (C-x C-b)](image/13.png){ #fig:013 width=70% }

![Переместитесь во вновь открытое окно (C-x) o со списком открытых буферов и переключитесь на другой буфер](image/14.png){ #fig:014 width=70% }

![Закройте это окно (C-x 0)](image/15.png){ #fig:015 width=70% }

![Переключайтесь между буферами, но уже без вывода их списка на экран (C-x b)](image/16.png){ #fig:016 width=70% }

8) Управление окнами (рис. [-@fig:017]) - (рис. [-@fig:018])

![разделите фрейм на два окна по вертикали (C-x 3), на две части по горизонтали (C-x 2)](image/17.png){ #fig:017 width=70% }

![введите несколько строк текста](image/18.png){ #fig:018 width=70% }

9) Режим поиска (рис. [-@fig:019]) - (рис. [-@fig:021])

![Переключитесь в режим поиска (C-s) и найдите несколько слов, присутствующих в тексте](image/19.png){ #fig:019 width=70% }

![Переключайтесь между результатами поиска, нажимая C-s](image/20.png){ #fig:020 width=70% }

![Выйдите из режима поиска, нажав C-g](image/21.png){ #fig:021 width=70% }



# Вывод

Познакомилась с операционной системой Linux. Получила практические навыки работы с редактором Emacs.