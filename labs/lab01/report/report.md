---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Дисциплина: Computer Skills for Scientific Writing "
author: "Живцова Анна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: cite.bib
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

Установить актуальную версию дистрибутива TeXLive  [@book]. 

# Задание

- Установить дистрибутива TeXLive на операционных системах Windows и Linux с помощью установщиков.     
- Установить дистрибутива TeXLive на операционных системах Windows и Linux вручную.    
- Обновить дистрибутива TeXLive.    

# Выполнение лабораторной 

Произвела установку дистрибутива TeXLive на операционной системе Linux с помощью установщика apt (см. рис. [-@fig:001]).
:

```
apt install texlive-full
```

![установку TeXLive на Linux с помощью apt](image/3.jpg){#fig:001}

Произвела установку дистрибутива TeXLive на операционной системе Windows с помощью установщика choco (см. рис. [-@fig:002], [-@fig:003] ).

```
choco install texlive
```

![установку TeXLive на Windows с помощью choco (1)](image/1.jpg){#fig:002}

![установку TeXLive на Windows с помощью choco (2)](image/2.jpg){#fig:003}

Произвела установку дистрибутива TeXLive на операционной системе Windowsвручную (см. рис. [-@fig:004], [-@fig:005] ).

![установку TeXLive на Windows вручную (1)](image/4.jpg){#fig:004}

![установку TeXLive на Windows вручную (2)](image/5.jpg){#fig:005}

Произвела установку дистрибутива TeXLive на операционной системе Linux вручную (см. рис. [-@fig:006], [-@fig:007] ).

![установку TeXLive на Linux вручную (1)](image/6.jpg){#fig:006}

![установку TeXLive на Linux вручную (2)](image/7.jpg){#fig:007}

# Выводы

В данной работе я установила актуальную версию дистрибутив TeXLive на операционных системах Windows и Linux с помощью установщиков и вручную.     

# Список литературы{.unnumbered}

::: {#refs}
:::
