---
## Front matter
title: "Шаблон отчёта по лабораторной работе # 4"
subtitle: "Дисциплина: архитектура компьютера"
author: "Хоюгбан Ганчыыр Анатольевич"

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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.

# Выполнение лабораторной работы

Перешел на нужный каталог и просмотрел его содержимое с помощью команды "ls", а затем создал файл "hello.asm" с помощью команды "touch"(рис. [@fig:001])

![Создание файла "hello.asm"](/image/Снимок экрана от 2023-10-28 12-50-07.png)

Перешел в файл "hello.asm" с помощью команды "gedit"(рис. [@fig:002])

![Переход в файл](/image/Снимок экрана от 2023-10-28 12-51-43.png)

Заполнил файл, как сказано в лабораторной работе(рис. [@fig:003])

![Заполнение файла](/image/Снимок экрана от 2023-10-28 12-53-16.png)

Компилирую текст, написанный в файле, и проверка появился ли файл "hello.o"(рис. [@fig:004])

![Компиляция текста](/image/Снимок экрана от 2023-10-28 12-56-41.png)

Компиляция исходного файла "hello.asm" в "obj.o"(рис. [@fig:005])

![Компиляция файла в "obj.o"](/image/Снимок экрана от 2023-10-28 12-58-53.png)

Передаю объектный файл на обработку компановщика(рис. [@fig:006])

![Передача компоновщику](/image/Снимок экрана от 2023-10-28 13-00-42.png)

Задаю имя создаваемого исполняемого файла(рис. [@fig:007])

![Создание имени](/image/Снимок экрана от 2023-10-28 13-02-39.png)

Запуск и выполнение созданного файла, который находится в текущем каталоге(рис. [@fig:008])

![Запуск на выполнение](/image/Снимок экрана от 2023-10-28 13-04-40.png)

# Выполнение самостоятельной работы

Создаю и дублирую файл "hello.asm", назвав его "lab4.asm" и перехожу в него с помощью команды "gedit"(рис. [@fig:009])

![Создание файла](/image/Снимок экрана от 2023-10-28 13-09-47.png)

Заполняю, созданный файл(рис. [@fig:010])

![Заполнение файла](/image/Снимок экрана от 2023-10-28 13-11-00.png)

Компилриую текст программы в объектный файл и передаю файл на обработку компановщика(рис. [@fig:011])

![Компиляция и обработка](/image/Снимок экрана от 2023-10-28 13-12-52.png)

Запуск исполняемого файла "lab4" и на экран правильно высветились мои имя и фамилия(рис. [@fig:012])

![Запуск файла](/image/Снимок экрана от 2023-10-28 13-14-22.png)

Отправка полученных результатов на сервер(рис. [@fig:013])

![Отправка](/image/Снимок экрана от 2023-10-28 13-15-18.png)

# Выводы
При выполнении данной работы я освоил процедуры компиляции и сборки программ, написанных на ассемблере NASM 
	
# Список литературы{.unnumbered}

::: {#refs}
:::
