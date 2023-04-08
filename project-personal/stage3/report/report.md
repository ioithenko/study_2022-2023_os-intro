---
## Front matter
title: "Третий этап индивидуального проекта"
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

Добавить к сайту достижения.

# Задание

Список достижений.

- Добавить информацию о навыках (Skills).
- Добавить информацию об опыте (Experience).
- Добавить информацию о достижениях (Accomplishments).

Сделать пост по прошедшей неделе.
Добавить пост на тему: Язык разметки Markdown.

# Выполнение индивидуального проекта

Создадим два шаблона поста: о прошедшей неделе и о языке разметки (рис. @fig:001).

![Создание шаблона поста](image/1.png){#fig:001 width=70%}

Заполним посты (рис. @fig:002) и (рис. @fig:003).

![Пост о прошедшей неделе](image/2.png){#fig:002 width=70%}

![Пост о markdown](image/3.png){#fig:003 width=70%}

В файле ~/work/blog/content/_index.md внесем информации о навыках, опыте и достижениях (рис. @fig:004).

![Внесение информации о достижениях](image/4.png){#fig:004 width=70%}

Проверим изменения на локальном сервере.

Запушим изменения и пеосмотрим на итоговый вид сайта (рис. @fig:005).

![Итоговый вид сайта](image/5.png){#fig:005 width=70%}

# Выводы

В ходе выполнения индивидуального проекта я добавила информацию о навыках, опыте и достижениях, а также написала несколько постов.

