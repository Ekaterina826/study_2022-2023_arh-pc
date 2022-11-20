---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина: Архитектура компьютера"
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

Целью работы является изучение идеологии и применение средств контроля версий.
Приобретение практических навыков по работе с системой git.

# Задание

 1. Создать отчёт по выполнению лабораторной работы в соответствующем каталоге рабочего пространства.
 
 2. Скопировать отчёты по выполнению предыдущих лаборатороных работ в соответствующие каталоги.
 
 3. Загрузить файлы на Github.

# Выполнение лабораторной работы

№1. Создаём учётную запись на сайте и заполняем основные данные.(рис. [-@fig:001])

![Регистрация на сайте](./image/image1){ #fig:001 width=70% } 
 
Сначала сделаем предварительную конфигурацию git. Откроем терминал и введём следующие команды, указав имя и email владельца репозитория.(рис. [-@fig:002])

![Конфигурация git](./image/к2){ #fig:002 width=70% }
 
 Для последующей идентификации пользователя на сервере репозиториев сгенерируем пару ключей(приватный и открытый).(рис. [-@fig:003])
 
 ![Генерация ключей](./image/к3){ #fig:003 width=70% }
 
 Далее необходимо загрузить сгенерённый открытый ключ. Для этого зайдём на сайт
http://github.org/ под своей учётной записью и перейдём в меню Setting . После этого
выберем в боковом меню SSH and GPG keys и нажмём кнопку New SSH key, скопировав
из локальной консоли ключ в буфер обмена, вставляем ключ в появившееся на сайте поле
и указываем для ключа имя.(рис. [-@fig:004]), (рис. [-@fig:005])

 ![Копирование ключа](./image/к4){ #fig:004 width=70% }

 ![Загрузка сгенерённого ключа](./image/к5){ #fig:005 width=70% }

№2. Откроем терминал и создадим каталог для предмета «Архитектура компьютера».(рис. [-@fig:006])

 ![Создание каталога](./image/к6){ #fig:006 width=70% }

№3. Создадим репозиторий курса. Перейдём на станицу репозитория с шаблоном курса.
Далее выберем Use this template. В открывшемся окне задаём имя репозитория (Repository
name) study_2022–2023_arh-pc и создаём репозиторий.(рис. [-@fig:007])

 ![Задавание имя репозитория](./image/к7){ #fig:007 width=70% }

Откроем терминал и перейдём в каталог курса и клонируем созданный репозиторий.(рис. [-@fig:008]), (рис. [-@fig:009])

 ![Переход в каталог курса](./image/к8){ #fig:008 width=70% }

 ![Клонирование репозитория](./image/к9){ #fig:009 width=70% }

Перейдём в каталог курса, удалим лишние файлы и создадим необходимые каталоги.(рис. [-@fig:0010]), (рис. [-@fig:0011])

 ![Переход в каталог](./image/к10){ #fig:0010 width=70% }

 ![Удаление файлов и создание каталогов](./image/к11){ #fig:0011 width=70% }

Отправляем файлы на сервер.(рис. [-@fig:0012]), (рис. [-@fig:0013])
 
 ![Отправка файлов](./image/к12){ #fig:0012 width=70% }
 
 ![Отправка файлов](./image/к13){ #fig:0013 width=70% }
 
# Задания для самостоятельной работы.
 
 №1. Для того, чтобы создать отчёт по выполнению лабораторной работы в
соответствующем каталоге рабочего пространства, необходимо перейти в директорию и
создать файл.(рис. [-@fig:0014]), (рис. [-@fig:0015])

 ![Переход в директорию](./image/к14){ #fig:0014 width=70% }

 ![Создание файла](./image/к15){ #fig:0015 width=70% }

Проверим наличие файла через текстовый редактор.(рис. [-@fig:0016])

 ![Проверка файла](./image/к16){ #fig:0016 width=70% }

№2-3. Скопируем отчёты по выполнению предыдущих лабораторных работ в
соответствующие каталоги созданного рабочего пространства и загрузим их на github.(рис. [-@fig:0017]), (рис. [-@fig:0018])

 ![Копирование первого отчёта](./image/к17){ #fig:0017 width=70% }
 
 ![Копирование второго отчёта](./image/к18){ #fig:0018 width=70% }
 
 Выполним проверку, откроем github и посмотрим загрузились ли туда наши файлы.(рис. [-@fig:0019]), (рис. [-@fig:0020])
 
 ![Проверка загрузки первого отчёта](./image/к19){ #fig:0019 width=70% }
 
 ![Проверка загрузки второго отчёта](./image/к20){ #fig:0020 width=70% }
 
 Таким же способом загружаем отчёт по третьей лабораторной работе. 
 
 


# Выводы

Изучили идеологию и применение средств контроля версий. И приобрели практические навыки по работе с системой git. 

# Список литературы{.unnumbered}

Демидова А.В. "Лабораторная работа №3" - Методический материал
