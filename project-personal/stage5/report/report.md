---
## Front matter
title: "Отчет к пятому этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Ищенко Ирина Олеговна"

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

Добавить к сайту остальные элементы: сделать запись персонального проекта, а также разместить два поста.

# Задание

Добавить к сайту все остальные элементы:

- Сделать записи для персональных проектов.

- Сделать пост по прошедшей неделе.

- Добавить пост на тему: Языки научного программирования.

# Выполнение лабораторной работы

Сначала я выполнила команду ~/bin/hugo server, чтобы получить ссылку на локальный сайт и просматривать там изменения. Затем я добавила свой проект и проверила его на локальном сайте (рис. @fig:001) и (рис. @fig:002).

![Заполнение проекта](image/1.png){#fig:001 width=70%}

![Проект на сайте](image/4.png){#fig:002 width=70%}

Далее я создала два поста с помощью команды ~/bin/hugo new post/название_поста. Мои посты были на тему прошлой недели и о языках научного программирования.

Я заполнила пост о прошедшей неделе необходимой информацией, сохранила его и проверила на локальном сайте (рис. @fig:003).

![Пост о прошедшей неделе](image/3.png){#fig:003 width=70%}

Далее заполнила второй пост о науке и программировании, затем сохранила и проверила изменения на локальном сайте (рис. @fig:004) и (рис. @fig:005).

![Пост о языках научного программирования](image/2.png){#fig:004 width=70%}

![Посты на сайте](image/5.png){#fig:005 width=70%}

Затем я выполнила исполняемый файл ~/bin/hugo в каталоге blog, и проверила изменения в public с помощью команды git status. 

После того, как я убедилась, что в public произошли необходимые изменения, я запушила(отправила) изменения на сервер.

Далее я также запушила(отправила) изменения в blog на сервер, предварительно выполнив команду git status для проверки изменений.

После того, как все изменения отправились на сервер, я открыла мой публичный сайт и проверила все изменения. Убедилась в корректности выполнения всех действий.

# Вывод

В ходе выполнения данного этапа я добавила к сайту остальные данные, разместила проект и создала два поста.

