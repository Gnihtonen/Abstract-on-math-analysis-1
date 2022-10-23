# Работа с Git

## Если вы не умеете пользоваться Git

Отправляйте вашу работу в телегу мне (@Gnihton) или Максиму (@m4xig1).

## Что отправлять в Pull Request

### Если вы техаете

Добавляйте в папку с **вашим** билетом 2 файла: `.tex` и `.pdf` с исходником и с готовым конспектом соответственно.

### Если вы отправляете фото/скан

Добавляйте в папку с **вашим** билетом pdf с фото/сканом вашего конспекта.
(коммент от Макса. Не делайте так пж, оформите хотя бы в ворде! Пожалейте нас)

# Для техающих

Если кто-то хочет затехать и помочь остальным маленький Style Guide:

Для начала, если начали техать чужой вопрос, напишите об этом в оглавлении вопроса, если что-то непонятно, напишите автору, спросите что он имел в виду. 


Название вопроса, номера оформляем в `\section{название вопроса}`.
Каждый подпункт оформляем в `\subsection{название вопроса}`.
Все что хоть как-то связано с математикой в mathmode (`$$`)
Доказательство желательно оформлять через `/begin{proof} \end{proof}` попутно используя `\begin{itemize} \item[1.] \end{itemize}`
Ограничений больше нет, но есть расширенный Style Guide [тут](https://hse-tex.me), посмотреть пример кода можно [тут](https://github.com/hse-tex/hse-tex/blob/master/course-1/mathematical-analysis/mathematical-analysis-colloquium-1.tex). 

Библиотеки, подключение которых может понадобится: 

```
\documentclass[12pt]{article}
\usepackage[utf8]{inputenc}
\usepackage[russian]{babel}
\usepackage[left=1.5cm,right=1.5cm,top=1.5cm,bottom=2cm]{geometry}
\usepackage{graphicx}
\usepackage{color}
\usepackage{titlesec}
\usepackage{amssymb}
\usepackage{mathtools}
\usepackage{minted}
\usepackage{hyperref}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{fancyhdr}
\usepackage{enumitem}
\usepackage{mathbbol}
\usepackage{titlesec}
\usepackage{changepage}
\usepackage{listings}
\usepackage[titles]{tocloft}
\usepackage{tcolorbox}
\usepackage{tikz}
\usepackage{tikz-cd}
\usepackage{ulem}
\usepackage{nicefrac}
\usepackage{indentfirst}
\usepackage{dsfont}
\usepackage{amsthm}
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=cyan,
    filecolor=magenta,      
    urlcolor=blue,
    pdftitle={Overleaf Example},
    pdfpagemode=FullScreen,
    }
```
