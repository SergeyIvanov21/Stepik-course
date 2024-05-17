---
## Front matter
title: "Отчет о прохождении 2 этапа внешнего курса"
subtitle: "Работа на сервере"
author: "Иванов Сергей Владимирович, НПИбд-01-23"

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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомиться с функционалом операционной системы Linux.

# Задание

Просмотреть видео и на основе полученной информации пройти тестовые задания.

# Теоретическое введение

Линукс - в части случаев GNU/Linux — семейство Unix-подобных операционных систем на базе ядра Linux, включающих тот или иной набор утилит и программ проекта GNU, и, возможно, другие компоненты. Как и ядро Linux, системы на его основе, как правило, создаются и распространяются в соответствии с моделью разработки свободного и открытого программного обеспечения. Linux-системы распространяются в основном бесплатно в виде различных дистрибутивов — в форме, готовой для установки и удобной для сопровождения и обновлений, — и имеющих свой набор системных и прикладных компонентов, как свободных, так и проприетарных. 

# Выполнение лабораторной работы

![1 Задание](image/1.png){#fig:001 width=70%}

Удаленный сервер - это компьютер, находящийся в дата-центре, к которому можно получить удаленный доступ через сеть Интернет. Удаленный сервер обычно используется для размещения веб-сайтов, приложений, баз данных и других сервисов, которые необходимы для функционирования сайта или бизнес-процессов компании. Пользователи могут получить доступ к удаленному серверу с помощью протоколов удаленного доступа, таких как RDP, VNC или SSH.

![2 Задание](image/2.png){#fig:002 width=70%}

Только id_rsa.pub, так как он является открытым.

![3 Задание](image/3.png){#fig:003 width=70%}

-r = Recursively copy entire directories. Note that scp follows symbolic links encountered in the tree traversal.

![4 Задание](image/4.png){#fig:004 width=70%}

Проверяем интернет соединение на предмет того, что устройство не может соединиться с сервером, затем проверяем то, знает ли оно вообще о существовании такой программы.

![5 Задание](image/5.png){#fig:005 width=70%}

FileZilla — свободный многоязычный проект, посвящённый приложениям для FTP. Включает в себя отдельное приложение «FileZilla Client» (являющееся FTP-клиентом), и «FileZilla Server». Приложения публикуются с открытым исходным кодом для Windows, macOS и Linux. Клиент поддерживает FTP, SFTP, и FTPS (FTP через SSL/TLS) и имеет настраиваемый интерфейс с поддержкой смены тем оформления.

![6 Задание](image/6.png){#fig:006 width=70%}

1. Проверить, есть ли другая версия этой программы (специально для терминала)

2. Настроить сервер, чтобы он поддерживал вывод информации на экран компьютера

![7 Задание](image/7.png){#fig:007 width=70%}

![8 Задание](image/8.png){#fig:008 width=70%}

FastQC supports files in the following formats

FastQ (all quality encoding variants)
Casava FastQ files*
Colorspace FastQ
GZip compressed FastQ
SAM
BAM
SAM/BAM Mapped only (normally used for colorspace data)

![9 Задание](image/9.png){#fig:09 width=70%}

-align
Do full multiple alignment.

![10 Задание](image/10.png){#fig:010 width=70%}

Комбинация Ctrl+С - завершает процесс.
Комбинация Ctrl+Z - приостанавливает процесс.

![11 Задание](image/11.png){#fig:011 width=70%}

![12 Задание](image/12.png){#fig:012 width=70%}

Если сигнал не перехватывается процессом, процесс уничтожается. Следовательно, это используется для изящного завершения процесса. Команда «kill -9» отправляет сигнал уничтожения для немедленного завершения любого процесса, если он присоединен к PID или имени процесса . Это принудительный способ убить/завершить набор процессов

![13 Задание](image/13.png){#fig:013 width=70%}

Команда kill шлёт сигнал о завершении процесса. Но программа обрабатывает сигналы только когда она исполняется, пока она остановлена она не может обработать сигнал и приступит к его обработке только после продолжения работы. 

![14 Задание](image/14.png){#fig:014 width=70%}

Запущенная программа потребляет ресурсы CPU, а остановленная нет.

![15 Задание](image/15.png){#fig:015 width=70%}

Приостановленное приложение не выполняет новых действий, поэтому не занимает вычислительные ресурсы компьютера (CPU 0%). При этом, в оперативной памяти оно сохранится, поэтому оно будет занимать столько же оперативной памяти, сколько до постановки на паузу.

![16 Задание](image/16.png){#fig:016 width=70%}

Although it is possible to specify the TID (thread ID, see gettid(2)) of one of the threads in a multithreaded process as the argument of kill, the signal is nevertheless directed to the process (i.e., the entire thread group). In other words, it is not possible to send a signal to an explicitly selected thread in a multithreaded process. The signal will be delivered to an arbitrarily selected thread in the target process that is not blocking the signal. 

![17 Задание](image/17.png){#fig:017 width=70%}

![18 Задание](image/18.png){#fig:018 width=70%}

```
echo "306174 reads; of these:
  306174 (100.00%) were unpaired; of these:
    11 (0.00%) aligned 0 times
    305580 (99.81%) aligned exactly 1 time
    583 (0.19%) aligned >1 times
100.00% overall alignment rate" > bowtie.log

```

![19 Задание](image/19.png){#fig:019 width=70%}

![20 Задание](image/20.png){#fig:020 width=70%}

exit завершает работу tmux

![21 Задание](image/21.png){#fig:021 width=70%}

Мы заходили на сервер с терминала, который и закрыли, а tmux будет продолжать свою работу на сервере.

![22 Задание](image/22.png){#fig:022 width=70%}

Ещё будет предупреждение о том, что работа завершится. Запущенный процесс во вкладке, конечно же, при её закрытии, пропадёт.

![23 Задание](image/23.png){#fig:023 width=70%}

Ctrl+b c - создать новое окно;

Ctrl+b w - выбрать окно из списка;

Ctrl+b 0-9 - открыть окно по его номеру;

Ctrl+b , - переименовать текущее окно;

Ctrl+b % - разделить текущую панель по горизонтали;

Ctrl+b " - разделить текущую панель по вертикали;

Ctrl+b стрелка - перейти на панель, находящуюся в стороне, куда указывает стрелка;

Ctrl+b Ctrl+стрелка - изменить размер текущей панели;

Ctrl+b o - перейти на следующую панель;

Ctrl+b ; - переключаться между текущей и предыдущей панелью;

Ctrl+b x - закрыть текущую панель;

Ctrl+b [ - войти в режим копирования (подробнее ниже);

Ctrl+b ] - вставить из внутреннего буфера обмена tmux;

Ctrl+b d - отключится от текущей сессии;

Ctrl+b : - открыть командную строку.

![24 Задание](image/24.png){#fig:024 width=70%}

Можно закрыть одно из делений вкладки выполнив команды Ctrl+B и Х.

По половинам "разделенной" вкладки можно перемещаться при помощи Ctrl+B и стрелок - как описано в задании выше.

Делить экран можно только в текущей вкладке tmux, а не во всех вкладках одновременно.

# Вывод

Я просмотрел курс и освежил в памяти навыки работы с архивами, скачивание файлов, команды grep и тп.

# Список литературы{.unnumbered}

1. Введение в Linux

::: {#refs}
:::

