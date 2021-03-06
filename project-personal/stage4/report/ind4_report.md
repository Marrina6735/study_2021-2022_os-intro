---
## Front matter
title: "ОТЧЕТ ПО 4 ЭТАПУ ИНДИВИДУАЛЬНОГО ПРОЕКТА"
subtitle: "Добавить к сайту ссылки на научные и библиометрические ресурсы и посты"
author: "Коняева Марина Александровна"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Задание

1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
    eLibrary : https://elibrary.ru/;
    Google Scholar : https://scholar.google.com/;
    ORCID : https://orcid.org/;
    Mendeley : https://www.mendeley.com/;
    ResearchGate : https://www.researchgate.net/;
    Academia.edu : https://www.academia.edu/;
    arXiv : https://arxiv.org/;
    github : https://github.com/.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему:
    Работа с библиографией.

# Выполнение лабораторной работы

1. Добавим к сайту ссылки на научные и библиометрические ресурсы, зайдя в нужный файл и изменив там данные (Изображение 1.1)

![ссылки на научные и библиометрические ресурсы](image/i4.1.png){ #fig:001 width=100% }
*Изображение 1.1 ссылки на научные и библиометрические ресурсы*

2. Добавим к сайту пост по прошедшей неделе (Изображение 2.1)

![пост по прошедшей неделе](image/i4.3.png){ #fig:001 width=100% }
*Изображение 2.1 пост по прошедшей неделе*

3. Добавим к сайту пост по теме работа с библиографией(Изображение 3.1)

![Работа с библиографией](image/i4.2.png){ #fig:001 width=100% }
*Изображение 3.1 Работа с библиографией*


# Выводы

В ходе выполнения данного этапа индивидуального проекта добавили к сайту ссылки на научные и библиометрические ресурсы, а также создали посты.
