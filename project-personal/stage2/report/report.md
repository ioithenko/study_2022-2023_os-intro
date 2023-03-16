---
## Front matter
title: "Отчет по второму этапу индивидуального проекта"
subtitle: "Дисциплина: Операционные системы"
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

Добавить к сайту данные о себе.

# Задание

Список добавляемых данных:
- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему: Управление версиями. Git.

# Выполнение лабораторной работы

Для того, чтобы разместить фотографию владельца, я перешла в каталог 
/blog/content/authors/admin и заменила изображение avatar.jpg на свою фотографию с тем же названием.

Краткое описание владельца сайта, информацию об интересах и образовании я добавила с помощью файла _index.md в каталоге /blog/content/authors/admin
(рис. @fig:001).

![Добавление информации о владельце сайта](image/1.png){#fig:001 width=70%}

Проверим вид сайта, внеся изменения в локальный сайт с помощью команды ~/bin/hugo server (рис. @fig:002).

![Информация о владельце сайта](image/2.png){#fig:002 width=70%}

Напишем пост о прошедшей неделе. Для этого с помощью команды ~/bin/hugo new post/last_week. Отредактируем шаблон статьи (рис. @fig:003).

![Добавление поста](image/4.png){#fig:003 width=70%}

Проверим вид сайта (рис. @fig:004).

![Пост](image/3.png){#fig:004 width=70%}

Напишем пост о гит (рис. @fig:005). Для того, чтобы прикрепить фотографию, добавим ее в каталог к файлу статьи и переименуем в featured.jpg (рис. @fig:006).

![Добавление поста](image/5.png){#fig:005 width=70%}

![Прикрепление изображения](image/6.png){#fig:006 width=70%}

Проверим вид сайта (рис. @fig:007).

![Пост с изображением](image/7.png){#fig:007 width=70%}

Запушим изменения, предварительно использовав команду ~/bin/hugo. Итогый вид сайта (рис. @fig:008).

![Итоговый вид сайта](image/8.png){#fig:008 width=70%}

# Выводы

В ходе данного этапа мы добавили информацию о владельце сайта и прикрепили два поста.
