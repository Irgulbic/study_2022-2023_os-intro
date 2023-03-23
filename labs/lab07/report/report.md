---
## Front matter
title: "Отчёт по лабораторной работе №7"
subtitle: "Дисциплина: Операционные сиcтемы."
author: "Матюхин Павел Андреевич НПИбд-02-22"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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


Освоить основные возможности командной оболочки Midnight Commander. Приобрести навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.


# Выполнение лабораторной работы


1. Изучил информацию о mc, вызвав в командной строке man mc.

![информация об mc](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Запустил из командной строки mc, изучил его структуру и меню.

![структура и меню mc](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/2.png){ #fig:002 width=70%, height=70% }

3. Выполнил несколько операций в mc, используя управляющие клавиши (операции
с панелями; выделение/отмена выделения файлов, копирование/перемещение фай-
лов, получение информации о размере и правах доступа на файлы и/или каталоги
и т.п.)

![операции в mc](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/3.png){ #fig:003 width=70%, height=70% }

4. Выполнил основные команды меню левой (или правой) панели. Оцените степень
подробности вывода информации о файлах.

![вывод информации](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/4.png){ #fig:004 width=70%, height=70% }

5. Испоьзуя возможности подменю "Файл" выполнил различные операции

![копирование файлов в созданный каталог](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/5.png){ #fig:005 width=70%, height=70% }

6. С помощью соответствующих средств подменю "Команда" осуществил выполнение различных операций

![поиск в файловой системе файла с заданными условиями](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/6.png){ #fig:006 width=70%, height=70% }

![выбор и повторение одной из предыдущих команд](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/7.png){ #fig:007 width=70%, height=70% }

![Анализ файла расширений](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/8.png){ #fig:008 width=70%, height=70% }

7. Вызвал подменю "Настройки" . Освоил операции, определяющие структуру экрана mc

![Параметр конфигурации](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/9.png){ #fig:009 width=70%, height=70% }

8. Выполнил специальные задания с текстом в редакторе midnight commander

![работа с редактором mc](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab07/report/image/10.png){ #fig:010 width=70%, height=70% }

# Вывод
  
  Освоил основные возможности командной оболочки Midnight Commander. Приобрел навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.
