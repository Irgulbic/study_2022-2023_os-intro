---
## Front matter
title: "Отчёт по лабораторной работе №8"
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

Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.


# Выполнение лабораторной работы


1. Создал каталог с именем ~/work/os/lab06.

![создание каталога](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab08/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Вызвал vi и создал файл hello.sh

![Вызов редактора и создание файла](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab08/report/image/2.png){ #fig:001 width=70%, height=70% }

3. Нажал клавишу i и ввел следующий текст:

![Ввод текста в редактор](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab08/report/image/6.png){ #fig:001 width=70%, height=70% }

4. сохранил изменения в файле и сделал его исполняемым

![работа с файлом](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab08/report/image/4.png){ #fig:001 width=70%, height=70% }

5. Провел с текстом в файле редактирование при помощи специальных символов

![работа с текстом файла](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab08/report/image/5.png){ #fig:001 width=70%, height=70% }

# Вывод
  
  Познакомился с операционной системой Linux. Получил практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.
  
