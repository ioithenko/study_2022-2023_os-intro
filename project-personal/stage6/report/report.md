---
## Front matter
title: "Отчёт по внешнему курсу "Введение в Linux""
subtitle: "Глава 1. Введение"
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


# Выполнение курса

Знакомимся со структурой курса, проходим вводные тестовые задания (рис. @fig:001), (рис. @fig:002) и (рис. @fig:003).

![Общая информация о курсе](image/1.PNG){#fig:001 width=70%}

![Общая информация о курсе](image/2.PNG){#fig:002 width=70%}

![Форум](image/3.PNG){#fig:003 width=70%}

Переходим к первому разделу "Как установить Linux". Выбираем операционные системы, которые я использую (рис. @fig:004). Отвечаем на вопрос, что такое виртуальная машина (рис. @fig:005). Запускаем виртуальную машину (рис. @fig:006).

![Операционные системы](image/4.PNG){#fig:004 width=70%}

![Виртуальная машина](image/5.PNG){#fig:005 width=70%}

![Запуск виртуальной машины](image/6.PNG){#fig:006 width=70%}

Переходим к следующему разделу "Осваиваем Linux". Осваиваем текстовый редактор: открываем LibreOffice Writer, настраиваем параметры шрифта и сохраняем файл с расширением xml (рис. @fig:007). Добавляем ответ на задание (рис. @fig:008). 

![Текстовый редактор](image/7.PNG){#fig:007 width=70%}

![Текстовый редактор](image/8.PNG){#fig:008 width=70%}

Указываем расширение установочных пакетов Linux - deb (рис. @fig:009). 

![Расширение установочных пакетов](image/9.PNG){#fig:009 width=70%}

Устанавливаем в систему плеер VLC: использую набор комманд 

sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm

sudo dnf install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

sudo dnf install vlc

Запускаем плеер и выводим информацию об авторах (рис. @fig:0010). Добавляем ответ на задание (рис. @fig:0011).

![Плеер VLC](image/10.PNG){#fig:0010 width=70%}

![Плеер VLC](image/11.PNG){#fig:0011 width=70%}

Выбираем назначение Update Manager (рис. @fig:0012).

![Update Manager](image/12.PNG){#fig:0012 width=70%}

Переходим к следующему разделу "Terminal: основы". 
Выбираем синонимы для "командной строки" (рис. @fig:0013). 

![Командная строка](image/13.PNG){#fig:0013 width=70%}

Отвечаем на вопрос о команде pwd - команда должна быть написана символами нижнего регистра (рис. @fig:0014). 

![Команда pwd](image/14.PNG){#fig:0014 width=70%}

Выбираем варианты написания ключей команды ls - команды могут быть написаны в любом порядке: в виде сокращения или в полном виде (рис. @fig:0015).

![Команда ls](image/15.PNG){#fig:0015 width=70%}

Ответим на задание. Предположим, что вы находитесь в директории /home/bi/Documents, причем /home/bi — ваша домашняя директория. Какая(ие) команда выведет содержимое /home/bi/Downloads, при этом не показывая содержимое других директорий? (рис. @fig:0016)

![Команда ls](image/16.PNG){#fig:0016 width=70%}

Команда для удаления директории - rm -r (рис. @fig:0017). Ключ -f служит для удаления файлов.

![Удаление директории](image/17.PNG){#fig:0017 width=70%}

Переходим к следующему разделу "Запуск исполняемых файлов". 
Если запустить через терминал браузер, а затем ввести команду exit, то ниодна из программ не закроется (рис. @fig:0018).

![Работа программ](image/18.PNG){#fig:0018 width=70%}

Отвечаем на вопрос о запуске программы в фоновом режиме (рис. @fig:0019).

![Фоновый режим](image/19.PNG){#fig:0019 width=70%}

Загружаем файл с программой, добавляем ему право на исполнение и запускаем (рис. @fig:0020). Вывод программы загружаем в  качестве ответа (рис. @fig:0021).

![Запуск программы](image/20.PNG){#fig:0020 width=70%}

![Результат программы](image/21.PNG){#fig:0021 width=70%}

Переходим к следующему разделу "Ввод / вывод". 
По умолчанию поток ошибок выводится на экран (рис. @fig:0022).

![Поток ошибок](image/22.PNG){#fig:0022 width=70%}

2> -  Перенаправить стандартный поток ошибок в файл. Если файл не существует, он будет создан, если существовал, то будет перезаписан.

2>> - Перенаправить стандартный поток ошибок в файл. Если файл не существует, он будет создан, если существует — данные будут дописаны к нему в конец.

Отвечаем на задание (рис. @fig:0023).

![Направление потока ошибок](image/23.PNG){#fig:0023 width=70%}

Сообщения об ошибках от программ в конвейере выводятся на экран (рис. @fig:0024).

![Сообщения об ошибках](image/24.PNG){#fig:0024 width=70%}

Переходим к следующему разделу "Скачивание файлов из интернета".
Отвечаем на вопрос о том, в какую директорию скачается файл и под каким именем (рис. @fig:0025).

![Команда wget](image/25.PNG){#fig:0025 width=70%}

Для того, чтобы команда wget не выводила сообщений на экран, используется опция -q (-quiet) (рис. @fig:0026).

![Команда wget](image/26.PNG){#fig:0026 width=70%}

Отвечаем на вопрос об опциях команды wget (рис. @fig:0027).

![Команда wget](image/27.PNG){#fig:0027 width=70%}

Переходим к следующему разделу "Работа с архивами". 
Отличие gzip от zip в том, что gzip удаляет архив после его распаковки (рис. @fig:0028).

![Архив](image/28.PNG){#fig:0028 width=70%}

Zip и tar могут создать архив из директории с файлами (рис. @fig:0029).

![Архив](image/29.PNG){#fig:0029 width=70%}

Чтобы запаковать файлы в указанный архив нужны опции: c - создать новый архив; j - перенаправить вывод в команду bzip2 (рис. @fig:0030).

![Запаковка файлов](image/30.PNG){#fig:0030 width=70%}

Также в этом разделе предлагалось сделать практическое задание, но курс корректно не смог считать решение.

Переходим к последнему разделу главы. Команда find может найти файл по имени или расширению, если символы указаны в нужном регистре и нет лишних символов (рис. @fig:0031).

![Поиск файла](image/31.PNG){#fig:0031 width=70%}

Команда grep выведет все использования запросного слова, если регист символа совпадает с запросом (рис. @fig:0032).

![Команда grep](image/32.PNG){#fig:0032 width=70%}

Скачиваем архив с произведениями, распаковываем его и используем команду grep. Вывод команды перенаправляем в файл с результатом (рис. @fig:0033) и (рис. @fig:0034).

![Выполнение задания](image/33.PNG){#fig:0033 width=70%}

![Добавление ответа на задание](image/34.PNG){#fig:0034 width=70%}

# Выводы

В ходе выполнения первой главы курса мы ознакомились с основами работы в операционной системе Linux.

