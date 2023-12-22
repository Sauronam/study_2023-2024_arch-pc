---
## Front matter
title: "Лабораторная работа номер 4"

author: "Палымбетов Амирхан"

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

Целью данной лабораторной работы является приобретение практических навыков работы в Midnight Commander, освоение инструкций языка ассемблера mov и int.

# Задание

1. Основы работы с mc
2. Подключение внешнего файла
3. Выполнение заданий для самостоятельной работы

# Выполнение лабораторной работы

1.Основы работы с mc:
в этом пункте мы научились использовать функциональные клавиши, а также написали программу ввода строки с клавиатуры, использовав при этом знания обращения с файлом из предыдущей лабораторной работы

![Рис1](image/work1.png){#fig:001 width=70%}

2.Подключение внешнего файла:
научились подключать внешний файл и использовать подпрограммы для более удобной работы кода
sprint – вывод сообщения на экран, перед вызовом sprint в регистр eax необходимо
записать выводимое сообщение
sprintLF – работает аналогично sprint, но при выводе на экран добавляет к сообще-
нию символ перевода строки

![Рис2](image/work2.png){#fig:002 width=70%}

3.Выполнение самостоятельной работы
Изменяем код, играемся с командам, что бы в итоге получился нужный нам результат

![Рис3](image/work3.png){#fig:003 width=70%}

![Рис4](image/work4.png){#fig:004 width=70%}

![Рис5](image/work5.png){#fig:005 width=70%}

![Рис6](image/work6.png){#fig:006 width=70%}

# Выводы

При выполнении данной лабораторной работы я приобрела практические навыки работы в Midnight Commander, а также освоила инструкции языка ассемблера mov и int.


