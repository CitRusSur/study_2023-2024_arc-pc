---
## Front matter
title: "Отчёт по лабораторной работе №2"
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

Получение навыков работы с системой github

# Ход работы

Создал учётную запись на Github и заполнил основные
данные.

![Рис.1 Ввод данных о владельце репозитория](image/1.png){#fig:001 width=70%}

![Рис.2 Настройка utf-8 в выводе сообщений git](image/2.png){#fig:001 width=70%}

![Рис.3 Ввод имени начальной ветки (master)](image/3.png){#fig:001 width=70%}

![Рис.4 Ввод параметров autocrlf и safecrlf](image/4.png){#fig:001 width=70%}

![Рис.5 Генерация пары ssh ключей](image/5.png){#fig:001 width=70%}

![Рис.6 Вывод созданного ключа, его копирование в буфер обмена](image/6.png){#fig:001 width=70%}

![Рис.7 После вставки ключа в поле на сайте github ключ был успешно привязан к аккаунту](image/7.png){#fig:001 width=70%}

![Рис.8 Создание каталога для предмета Архитектура компьютера](image/8.png){#fig:001 width=70%}

Далее я перешёл на страницу репозитория с шаблоном курса,
задал имя репозитория и создал его

![Рис.9 Переход в каталог курса и клонирование созданного репозитория в него](image/9.png){#fig:001 width=70%}

![Рис.10 Переход в каталог курса из каталога «Архитектура компьютера», удаление лишних файлов](image/10.png){#fig:001 width=70%}

![Рис.11 Создание необходимых каталогов](image/11.png){#fig:001 width=70%}

![Рис.12 Отправка файлов на сервер](image/12.png){#fig:001 width=70%}

# Задания для самостоятельной работы:

Этот отчёт был копирован в каталог /labs/lab02/report моего рабочего пространства и загружен на Github
Аналогичные действия были проделаны для отчёта по самостоятельной работе №1: он также был скопирован и загружен на Github
# Выводы

Были получены навыки работы с системой github, а также
отчёты по выполнению лабораторных работ были загружены
на сайт Github

