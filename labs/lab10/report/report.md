---
## Front matter
title: "Отчёт по лабораторной работе №10"
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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.


# Выполнение лабораторной работы


1. Создал файл script_a для работы с кодом.

![создание файла](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Написал скрипт, который при запуске будет делать резервную копию самого себя (то
есть файла, в котором содержится его исходный код) в другую директорию backup
в вашем домашнем каталоге. При этом файл должен архивироваться одним из ар-
хиваторов на выбор zip, bzip2 или tar. Способ использования команд архивации
необходимо узнать, изучив справку.

![Скрипт](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/2.png){ #fig:002 width=70%, height=70% }

![Результат работы скрипта](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/3.png){ #fig:003 width=70%, height=70% }

3. Создал файл script_b для работы с кодом и написал пример командного файла, обрабатывающего любое произвольное число
аргументов командной строки, в том числе превышающее десять. Например, скрипт
может последовательно распечатывать значения всех переданных аргументов.

![Скрипт](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/4.png){ #fig:004 width=70%, height=70% }

![Результат работы скрипта](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/5.png){ #fig:005 width=70%, height=70% }

4. Создал файл script_c для работы с кодом и написал командный файл — аналог команды ls (без использования самой этой ко-
манды и команды dir). Требуется, чтобы он выдавал информацию о нужном каталоге
и выводил информацию о возможностях доступа к файлам этого каталога.

![Скрипт](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/6.png){ #fig:006 width=70%, height=70% }

![Результат работы скрипта](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/7.png){ #fig:007 width=70%, height=70% }

5. Создал файл script_d и Написал командный файл, который получает в качестве аргумента командной строки
формат файла (.txt, .doc, .jpg, .pdf и т.д.) и вычисляет количество таких файлов
в указанной директории. Путь к директории также передаётся в виде аргумента ко-
мандной строки.

![Скрипт](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/8.png){ #fig:008 width=70%, height=70% }

![Результат работы скрипта](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab10/report/image/9.png){ #fig:009 width=70%, height=70% }

# Вывод
  
Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.
  
