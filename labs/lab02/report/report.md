---
## Front matter
title: "Отчёт по лабораторной работе №2"
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


    1)Изучить идеологию и применение средств контроля версий.
    2)Освоить умения по работе с git.


# Выполнение лабораторной работы


1. Зададим имя и email владельца репозитория

![имя и почта](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Настроим utf-8 в выводе сообщений git

![настройка вывода сообщений](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/2.png){ #fig:002 width=70%, height=70% }

3. Зададим имя начальной ветки и параметры

![настройка параметров](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/3.png){ #fig:003 width=70%, height=70% }

4. Регистрация на гитхаб 

![регистрация](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/4.png){ #fig:004 width=70%, height=70% }

5. Создание SSh ключа

![ключ](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/5.png){ #fig:005 width=70%, height=70% }

6. копирование ключа 

![ключ для гитхаб](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/6.png){ #fig:006 width=70%, height=70% }

7. Регистрация ключа на гитхаб 

![вставка ключа](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/7.png){ #fig:007 width=70%, height=70% }

8. Создание директорий 

![Создание директорий](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/8.png){ #fig:008 width=70%, height=70% }

9. Клонирование репозитория 

![Репозиторий](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/9.png){ #fig:009 width=70%, height=70% }

10. Удаление лишних файлов и создание каталогов 

![работа с файлами](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/10.png){ #fig:010 width=70%, height=70% }

11. Выгрузка файлов на гит

![выгрузка](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab03/report/image/11.png){ #fig:011 width=70%, height=70% }

# Вывод
Изучил идеологию и применение средств контроля версий, освоить умения по работе с git.
