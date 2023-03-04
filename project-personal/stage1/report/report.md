---
## Front matter
title: "Отчёт по первой стадии индивидуального проекта"
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


   Научиться работать с сайтами


# Выполнение лабораторной работы


1. Установил до ПО HUgo 

![ПО](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Скопировал данные из взаимствованного репозитория 

![Копирование](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/2.png){ #fig:002 width=70%, height=70% }

3. Создал сайт при помощи HUGO server

![терминал](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image//4.png){ #fig:003 width=70%, height=70% }

![сайт](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/3.png){ #fig:004 width=70%, height=70% }

4. Создал новый репозиторий на гитхаб и связал его с моим пк

![репозиторий](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/6.png){ #fig:005 width=70%, height=70% }

5. Переключился на ветку main, создал фай и залил на гит

![работа с новым репозиторием](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/7.png){ #fig:006 width=70%, height=70% }

6. Поменял параметры игнорирования файла паблик

![Изменение параметров](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/8.png){ #fig:007 width=70%, height=70% }

7. Совершил новое клолнирование при помощи submodule 

![клонирование](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/9.png){ #fig:008 width=70%, height=70% }

8. Изменил параметры сайта при помощи hugo

![изменение парметров](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/10.png){ #fig:009 width=70%, height=70% }

9. Проверил связь с гитом 

![связь](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/11.png){ #fig:010 width=70%, height=70% }

11. Залил изменения на гит

12. Теперь сайт работает через гит сервера

# Вывод
   Научился копировать сайт и изменять его параметры

