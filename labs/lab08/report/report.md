---
## Front matter
title: "Отчёт по восьмой лабораторной работе"  
subtitle: "По дисциплине Операционные Системы "          
author: "Пупчин Сергей Константинович"
## Generic otions
lang: ru-RU
## Pdf output format
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
## Pandoc-crossref LaTeX customizations
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
## date: "2022"
---
\
\
\
\

## Цели работы:

Получить первый опыт работы с текстовым редактором vim.
\


##  Ход работы:
\  
Эта лабораторная разбита на два небольших задания, собственно первое и второе.
Первое задание состоит в создании файла hello.sh, котрый представляет собой программу на языке shell, которая выводит в консоль строку "Hello world". Создать файл и сразу открыть его в vim можно при помощи команды vi hello.sh


![ Текст в редакторе VI ](where_gui.png){ #fig:001 width=70% }  

\  

Затем, при помощи команды chmod, нужно сделать файл исполняемым. 

![ После этой команды файл можно запустить, введя в командную строку ./hello.sh ](chmodx.png){ #fig:002 width=70% } 
 
\  

Второй задание касается редактирования текстового файла в vim. Чтобы переключаться между командным режимом и режимом вставки можно использовать клавищи i и esc. Чтобы стореть символ нужно ввести х, чтобы стереть строку нужно ввести dd, а для сохрния изменений и закрытия vim можно ввести :wq. Для отмены последнего изменения есть клавиша u.


## Заключение  
\  

Я получил первый опат взаимодействия с vim, не могу сказать, что этот опыт был приятный. Но, наверное, потом пригодится.

