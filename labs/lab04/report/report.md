---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "дисциплина: Архитектура компьютера"
author: "Тимофеева Екатерина Николаевна"

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

Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Задание

 1. Установить TexLive, Pandoc и Pandoc-crossref.
 
 2. Cкомпилировать шаблон отчета с помощью Makefile.
 
 3. Заполнить и скомпилировать отчет, используя Makefile.
 
 4. Загрузить файлы на Github.
 
 5. Выполнить задания для самостоятельной работы.

# Выполнение лабораторной работы

  №1. Откроем терминал и перейдём в каталог курса, сформированный при выполнении лабораторной работы №3. Обновим локальный репозиторий, скачав изменения из удалённого репозитория и перейдём в каталог с шаблоном отчёта по лабораторной работе №4. 
  
 ![Подготовка рабочего пространства](./image/картинка1){ #fig:fig1 width=70% }
 
  №2. Провели компиляцию шаблона с использованием Makefile с помощью команды *make*. Открыли файлы report.pdf и report.docx, проверили их корректность.
  
 ![Компиляция шаблонов](/home/entimofeeva/Загрузки/карт3){ #fig:fig2 width=70% }
 
  №3. Удалили полученные файлы   
  
 ![Удаление файлов](/home/entimofeeva/Загрузки/карт2){ #fig:fig3 width=70% }
 
  №4. Открыли файл с помощью текстового редактора gedit. Заполнили отчёт и скомпилировали его с помощью Makefile и загрузили файлы на Github.
  
# Выполнение заданий для самостоятельной работы

 В соответствующем каталоге сделали отчёт по лабораторной работе №3 в формате Markdown 
 
 Загрузили файлы на Github 


# Выводы

 Освоили процедуры оформления отчетов с помощью легковесного языка разметки Markdown.
 
# Список литературы{.unnumbered}

 1. Демидова А.В. "Лабораторная работа №4. Язык разметки Markdown" - Методическое пособие
