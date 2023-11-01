---
## Front matter
title: "Отчёта по лабораторной работе"
subtitle: "№3"
author: "Палымбетов Амирхан Еркинбаевич"

## Generic otions
lang: ru-RU
toc-title:

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Задание
1.Обновить локальный репозиторий и провести компиляцию шаблона с использованием Makefile.

2.Изучить структуру отчета и заполнить его.

3.Загрузить файлы на github

4.Cамостоятельная работа

# Выполнение лабораторной работы

1.С помощью команды git pull обновляем локальный репозиторий, в данный момент у нас самая 
актуальная версия, проводим компиляцию(пришлось подождать).

![Рис.1](image/work1.png){#fig:001 width=70%}

2.Изучаем структуру и заполняем отчет

![Рис.2](image/work2.png){#fig:002 width=70%}

3.Загружаем файлы на github

![Рис.3](image/work3.png){#fig:003 width=70%}

4.Выполняем самостоятельную работу с, заполняем отчет в markdown и компилируем pdf и docx файлы и отправляем файлы на гит

![Рис.4](image/work4.png){#fig:004 width=70%}

![Рис.5](image/work5.png){#fig:005 width=70%}



# Вывод

Мы научились оформлять отчеты с помощью Markdown, а также можем предоставить отчет сразу в трёх форматах.
