---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "Дисциплина: Операционные ситемы."
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


   Приобрести практические навыки взаимодействия с системой посредством командной строки


# Выполнение лабораторной работы


1. Определил полное имя моего домашнего каталога при помощи команды pwd

![работа команды pwd](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/1.png){ #fig:001 width=70%, height=70% }

2. Перешел в каталог /tmp, при помощи различных команд ls вывел содержимое каталога

![работа команды ls](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/2.png){ #fig:002 width=70%, height=70% }

3. Определил есть ли в каталоге файл с именем cron 

![поиск файла](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/3.png){ #fig:003 width=70%, height=70% }

4. Определил кто является владельцем файлов в моем домашнем каталоге 

![работа команды ls -l](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/3.png){ #fig:004 width=70%, height=70% }

5. В домашнем каталоге создал новый каталог с именем newdir и создал в нем каталог с именем morefun

![создание каталога](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/4.png){ #fig:005 width=70%, height=70% }


6. В домашнем каталоге создал три каталога одной командой затем удалил эти каталоги одной командой

![Создание и удаление каталогов](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/5.png){ #fig:006 width=70%, height=70% }

7. Попробовал удалить каталог newdir, но каталог не был удален 

![удаление каталога newdir](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/6.png){ #fig:007 width=70%, height=70% }

8. При помощи команды rm -r удалил каталог morefun

![удаление каталога morefun](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/8.png){ #fig:008 width=70%, height=70% }

9. С помощью команды man определил какую команду нужно испоользовать для просмотра подкаталогов входящих в каталог

![работа команды ls *](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/9.png){ #fig:009 width=70%, height=70% }

10. С помощью команды man определил команду, которая позволяет 
остсортиролвать по времени последнего изменения выводимый список содержимого каталога

![Сортировка](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/10.png){ #fig:010 width=70%, height=70% }

11. Использовал команду man для просмотра описания команд

![Описание команд](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/11.png){ #fig:011 width=70%, height=70% }

12. Выполнил модификацию команд полученных из буфера команд

![модификация команд](/home/pamatyukhin/work/study/2022-2023/Операционные системы/os-intro/labs/lab04/report/image/12.png){ #fig:012 width=70%, height=70% }

# Вывод
   Приобрел практические навыки взаимодействия с системой посредством командной строки

