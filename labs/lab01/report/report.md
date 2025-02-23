---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Установка ОС Linux"
author: "Баранов Никита Дмитриевич"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

Установить ОС Linux

# Выполнение лабораторной работы

Установка системы на диск(рис. @fig:001).

![Устанавливаем Fedora на VM](image/1.jpg){#fig:001 width=70%}

Установка обновлений(рис. @fig:002)(рис. @fig:003)(рис. @fig:004)(рис. @fig:005)(рис. @fig:006).

![Переходи в режим суперпользователя и обновляем все пакеты](image/2.jpg){#fig:002 width=70%}

![Отключаем SELinux](image/3.jpg){#fig:003 width=70%}

![Обновляем пандок](image/4.jpg){#fig:004 width=70%}

![Доустанавливаем пандок-кроссреф](image/5.jpg){#fig:005 width=70%}

![Устанавливаем texlive](image/6.jpg){#fig:006 width=70%}

# Домашнее задание

![Анализируем последовательность загрузки системы командой dmesg](image/7.jpg){#fig:007 width=70%}

# Выводы

Мы приобрели практические навыки по установке ОС на ВМ, а также настройке необходимых сервисов


