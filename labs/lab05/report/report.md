---
## Front matter
title: "Отчёт по лабораторной работе №5"
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


  Ознакомиться с файловой системой линукс, её структурой, именами и содержанием каталогов. Приобрести практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами, по проверке использования диска и обслуживание файловой системы.


# Выполнение лабораторной работы


1. Выполнил примеры, приведенные в первой части описания лабораторной работы.

![Копирование файлов и каталогов](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/2.png){ #fig:001 width=70%, height=70% }

![Перемещение и переименование файлов и каталогов](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/8.png){ #fig:002 width=70%, height=70% }

![Права доступа](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/9.png){ #fig:003 width=70%, height=70% }

2. Выполнил действия связанные с копированием и созданием файлов.

![Копирование и создание файлов](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/10.png){ #fig:004 width=70%, height=70% }

3. Определил опции команды chmod, необходимых для выполнения поставленных в описании лабораторной работы задач.

![команды chmod](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/11.png){ #fig:005 width=70%, height=70% }

4. Проделал специальные упражнения описанные  в описании лабораторной работы.

![упражнения](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/12.png){ #fig:006 width=70%, height=70% }

![использование команды man](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab05/report/image/12.png){ #fig:006 width=70%, height=70% }

# Вывод
     Ознакомился с файловой системой линукс, её структурой, именами и содержанием каталогов. Приобрел практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами, по проверке использования диска и обслуживание файловой системы.

