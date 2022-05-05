---
## Front matter
title: "Отчёт по лабораторной работе №5"
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

Ознакомиться с файловой системой Linux, её структурой, именами и содержанием
каталогов, приобрести практические навыки по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

# Ход лабораторной работы
## Выполнение примеров из текста лабораторной работы

1) Копируем файл в текущем каталоге (рис. [-@fig:001])

![Копируем файл ~/abc1 в файл april и в файл may](image/1.jpg){ #fig:001 width=70% }

2) Копируем несколько файлов в каталог (рис. [-@fig:002])
	
![Копируем файлы april и may в каталог monthly](image/1.jpg){ #fig:002 width=70% }
	
3) Копируем файлы в произвольном каталоге (рис. [-@fig:003])
	
![Скопируем файл monthly/may в файл с именем june](image/1.jpg){ #fig:003 width=70% }
	
4) Копируем каталоги в текущем каталоге (рис. [-@fig:004])
	
![Скопируем каталог monthly в каталог monthly.00 ](image/4.jpg){ #fig:004 width=70% }
	
5) Копируем каталоги в произвольном каталоге (рис. [-@fig:005])
	
![Скопируем каталог monthly.00 в каталог /tmp](image/4.jpg){ #fig:005 width=70% }
	
6) Переименовываем файлы в текущем каталоге (рис. [-@fig:006])
	
![Изменяем название файла april на july в домашнем каталоге](image/6.jpg){ #fig:006 width=70% }
	
7) Перемещаем файлов в другой каталог (рис. [-@fig:007])
	
![Перемещаем файл july в каталог monthly.00](image/7.jpg){ #fig:007 width=70% }
	
8) Переименовываем каталоги в текущем каталоге (рис. [-@fig:008])

![Переименовать каталог monthly.00 в monthly.01](image/8.jpg){ #fig:008 width=70% }

9) Перемещаем каталог в другой каталог (рис. [-@fig:009])

![Переместить каталог monthly.01 в каталог reports](image/9.jpg){ #fig:009 width=70% }
 
10) Переименовываем каталог, не являющийся текущим (рис. [-@fig:010])

![Переименовать каталог reports/monthly.01 в reports/monthly](image/10.jpg){ #fig:010 width=70% }
 
11) Создаём файл ~/may с правом выполнения для владельца (рис. [-@fig:011])

![Права доступа файла may](image/11.jpg){ #fig:011 width=70% }

12) Лишаем владельца файла may права выполнение (рис. [-@fig:012])

![Права доступа файла may](image/12.jpg){ #fig:012 width=70% }

13) Создаём каталог monthly с запретом на чтение для членов группы и всех
остальных пользователей (рис. [-@fig:013])

![Права доступа каталога monthly](image/13.jpg){ #fig:013 width=70% }

14) Создаём файл ~/abc1 с правом записи для членов группы. (рис. [-@fig:014])

![Права доступа файла abc1](image/14.jpg){ #fig:014 width=70% }

15) Скопируем файл /usr/include/sys/io.h в домашний каталог и назовём его equipment (рис. [-@fig:015])

![Копирование файла](image/15.jpg){ #fig:015 width=70% }

16) В домашнем каталоге создаём директорию ~/ski.plases. Перемещаем файл equipment в каталог ~/ski.plases и переименовываем файл ~/ski.plases/equipment в ~/ski.plases/equiplist (рис. [-@fig:016]) 

![Создание директории, перемещение и переименование файла](image/16.jpg){ #fig:016 width=70% }

17) Создаём в домашнем каталоге файл abc1 и копируем его в каталог ~/ski.plases, называем его equiplist2. (рис. [-@fig:017])

![Создание файла, его копирование и переименование](image/17.jpg){ #fig:017 width=70% }

18) Создаём каталог с именем equipment в каталоге ~/ski.plases. Перемещаем файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment (рис. [-@fig:018])

![Создание каталога, перемещение файлов](image/18.1.jpg){ #fig:018 width=70% }

19) Создаём и перемещаем каталог ~/newdir в каталог ~/ski.plases и называем его plans. (рис. [-@fig:019])

![Создание каталога, его перемещение и переименование](image/19.jpg){ #fig:019 width=70% }

20) Определяем опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа. (рис. [-@fig:020]) - (рис. [-@fig:023])

![Переопределение прав доступа](image/19.1.jpg){ #fig:020 width=70% }

![Переопределение прав доступа](image/19.2.jpg){ #fig:021 width=70% }

![Переопределение прав доступа](image/19.3.jpg){ #fig:022 width=70% }

![Переопределение прав доступа](image/19.4.jpg){ #fig:023 width=70% }

21) Просматриваем содержимое файла /etc/password. (рис. [-@fig:014])

![Файл password](image/20.jpg){ #fig:024 width=70% }

22) Скопируем файл ~/feathers в файл ~/file.old. Перемещаем файл ~/file.old в каталог ~/play. Скопируем каталог ~/play в каталог ~/fun. Перемещаем каталог ~/fun в каталог ~/play и называем его games (рис. [-@fig:025])

![Копирование и перемещение](image/22.jpg){ #fig:025 width=70% }

23) Лишаем владельца файла ~/feathers права на чтение и видим, что мы не имеем доступ, чтобы прочитать файл (рис. [-@fig:026])

![Права доступа файла feathers](image/23.jpg){ #fig:026 width=70% }

24) Лишаем владельца каталога ~/play права на выполнение и видим, что права доступа к каталогу изменились. (рис. [-@fig:027])

![Файл password](image/24.jpg){ #fig:027 width=70% }

25) Прочитаем man по командам mount, fsck, mkfs, kill. (рис. [-@fig:028]) - (рис. [-@fig:032]

![Вызов команды man](image/25.jpg){ #fig:028 width=70% }

![mount](image/mount.jpg){ #fig:029 width=70% }

![fsck](image/fsck.jpg){ #fig:030 width=70% }

![mkfs](image/mkfs.jpg){ #fig:031 width=70% }

![kill](image/kill.jpg){ #fig:032 width=70% }

# Вывод

Ознакомилась с файловой системой Linux, её структурой, именами и содержанием каталогов, приобрела практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.
