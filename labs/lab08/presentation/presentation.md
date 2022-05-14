---
## Front matter
lang: ru-RU
title: Презентация по пятой лабораторной
author: Pupchin Sergei
institute: RUDN University, Moscow, Russian Federation
## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
---

## Цели работы

- Получить первый опыт работы с текстовым редактором vim.
 

## Первое задание

- создать файл hello.sh, котрый представляет собой программу на языке shell. Создать файл и сразу открыть его в vim можно при помощи команды vi hello.sh


![ Текст в редакторе VI ](where_gui.png){ #fig:001 width=70% } 


## Второе задание 

- Второй задание касается редактирования текстового файла в vim. Чтобы переключаться между командным режимом и режимом вставки можно использовать клавищи i и esc. Чтобы стореть символ нужно ввести х, чтобы стереть строку нужно ввести dd, а для сохрния изменений и закрытия vim можно ввести :wq. Для отмены последнего изменения есть клавиша u.

- Затем, при помощи команды chmod, нужно сделать файл исполняемым. 

![ После этой команды файл можно запустить, введя в командную строку ./hello.sh ](chmodx.png){ #fig:002 width=70% }



## Заключение

- Я получил первый опат взаимодействия с vim, не могу сказать, что этот опыт был приятный. Но, наверное, потом пригодится.


