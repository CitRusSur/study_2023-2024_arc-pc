---
## Front matter
title: "Отчёт по лабораторной работе №4"
author: "Цатурьян Лев Вячеславович НММбд-03-23"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться работать с файлами на языке ассемблера (NASM)
Научиться создавать объектные и исполняемые файлы из файлов с текстом программы

# Теоретическое введение

![Что такое ассемблер?](image/th.png){#fig:001 width=70%}

# Выполнение лабораторной работы

![Рис.1 Создание рабочего каталога и файла в нем, переход в этот каталог и открытие созданного файла](image/1.png){#fig:001 width=70%}

![Рис.2 Ввод текста в открывшийся файл](image/12122.png){#fig:001 width=70%}

![Рис.3 Компиляция исходного файла hello.asm в объектный код и проверка](image/2.png){#fig:001 width=70%}

![Рис.4 Компиляция исходного файла hello.asm в объектный obj.o и проверка, создание файла листинга](image/3.png){#fig:001 width=70%}

![Рис.5 Компоновка объектного файла и проверка](image/4.png){#fig:001 width=70%}

![Рис.6 Компоновка объектного файла в исполняемый (исполняемый файл имеет имя main, а объектный obj.o)](image/5.png){#fig:001 width=70%}

![Рис.7 Запуск исполняемого файла, все работает без ошибок](image/6.png){#fig:001 width=70%}

#Задание для самостоятельной работы

![Рис.8 Копирование файла](image/7.png){#fig:001 width=70%}

![Рис.9 Открытие файла lab4.asm с помощью gedit](image/8.png){#fig:001 width=70%}

![Рис.10 Внесение изменений в файл: теперь программа будет выводить мои имя и фамилию](image/9.png){#fig:001 width=70%}

![Рис.11 Компиляция исходного файла в объектный и проверка](image/10.png){#fig:001 width=70%}

![Рис.12 Создание исполняемой программы из объектного файла](image/11.png){#fig:001 width=70%}

![Рис.13 Проверка: все работает корректно](image/12.png){#fig:001 width=70%}

![Рис.14 Копирование полученной программы в рабочий каталог](image/13.png){#fig:001 width=70%}

![Рис.15 Загрузка файлов на github](image/14.png){#fig:001 width=70%}

# Выводы

Я научился работать с файлами на языке ассемблера (NASM)
Я научился создавать объектные и исполняемые файлы из файлов с текстом программы
