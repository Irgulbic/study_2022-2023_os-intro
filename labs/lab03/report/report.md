---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина: Операционные ситемы."
author: "Матюхин Павел Андреевич НММбд-02-22"

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


   Научиться делать отчеты при помощи компиляции файлов из формата md


# Выполнение лабораторной работы


1. Сделал скриншоты выполнения лабораторной работы №2

![скриншоты](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Изменил шаблон формат md

![шаблон](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/2.png){ #fig:002 width=70%, height=70% }

3. Скомпилировал шаблон при помощи команды make

![Компиляция](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/3.png){ #fig:003 width=70%, height=70% }


# Вывод
   Научился делать отчеты при помощи компиляции файлов из формата md

