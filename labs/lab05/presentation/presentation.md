---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №5
subtitle: Дисциплина "Computer Skills for Scientific Writing"
author:
  - Живцова А.А.
institute:
  - Кафедра теории вероятностей и кибербезопасности, Российский университет дружбы народов имени Патриса Лумумбы, Москва, Россия
date: 11 сентября 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Живцова Анна Александровна
  * студент кафедры теории вероятностей и кибербезопасности
  * Российский университет дружбы народов имени Патриса Лумумбы
  * [zhivtsova_aa@pfur.ru](mailto:zhivtsova_aa@pfur.ru)
  * <https://github.com/AnnaZhiv>

:::
::: {.column width="30%"}

![](./image/photo.jpg)

:::
::::::::::::::

# Вводная часть

## Актуальность

Использование LaTeX  критически важно для исследователей, так как это профессиональный стандарт для подготовки научных статей. Он обеспечивает отличное качество вёрстки, позволяет легко работать с библиографией и ссылками, что значительно ускоряет процесс написания исследований. 

## Объект и предмет исследования

- Дистрибутив TexLive          
- Оформление таблиц
- Окружения ```tabular, tabularx, longtable```     
- Пакеты ``` booktabs, array, threeparttable, tabularx, longtable, siunitx```       

## Цели и задачи

Освоить опции оформления таблиц. 

- Изучить материал         
- Протестировать изученные опции оформления таблиц     
- Ответить на контрольные вопросы     

## Материалы и методы

- Дистрибутив TexLive         
- Компилятор pdflatex     

# Результаты

## Практическая отработка изученного. Код 

``` 
\begin{tabular}{>{\itshape}l<{:}cr|p{2cm}@{ : }m{2cm}!{:}b{2cm}}
Animal & Food & Size & tro lo lo lo lo lo lo lo lo lo lo tro lo lo & ioio & nono \\
\toprule
dog & meat & medium  & lala & tata & lolo \\
\midrule
horse & hay & large & pupu & papa & meme \\
\cmidrule{2-3}
frog & flies & small & susu & nana & bebe \\
\cmidrule(r){1-1}
\cmidrule(rl){2-2}
\cmidrule(l){3-3}
dada & baba & kaka & fufu & tutu & mumu \\
\addlinespace
gege & hehe & meme & nene & \multicolumn{2}{c}{unknown} \\[4pt]
xexe & wowo & koko & haha & rara & haha \\ 
\midrule[2pt]
yaya & yeye & yoyo & popo & bobo & jojo \\
\bottomrule
\end{tabular}
```

## Практическая отработка изученного. Результат 

![](image/2.png){#fig:006 width=95%}

