---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
author: |
	Филиппова Веронкиа Сергеевна - студентка группы НКНбд-01-18
date: 15.09.2021

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Установка виртуальной машины CentOS и её конфигурация.

## Цель выполнения лабораторной работы

- Приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для
дальнейшей работы сервисов.

## Задачи выполнения работы

- Создать виртуальную машину

- Установить на неё CentOS

- Настроить виртуальную машину

- Создать вторую виртуальной машину на основе первой

# Выполнение лабораторной работы

## Создание виртуальной машины

## Результаты выполнения лабораторной работы.
Создала новую виртуальную машину. Для этого в VirtualBox выбрала
"Машина" -\> "Создать". Указала имя - Base, тип операционной системы ---
Linux, RedHat. (рис. -@fig:002)

![Имя машины и тип ОС](https://github.com/vsfilippova/Lab01InfS/blob/main/scr/2.jpg){#fig:002 width="70%"}

## Результаты выполнения лабораторной работы
На виртуальной машине Base запустила терминал, перешла под учетную
запись root с помощью команды su. С помощью команды yum update обновила
системные файлы и установила необходимые программы. (рис. -@fig:015)

![Терминал](https://github.com/vsfilippova/Lab01InfS/blob/main/scr/15.jpg){#fig:015 width="70%"}

## Результаты выполнения лабораторной работы
Создала новую виртуальную машину под названием Host2 с использованием
существующего виртуального диска Base. (рис. -@fig:017)

![Виртуальная машина Host2](https://github.com/vsfilippova/Lab01InfS/blob/main/scr/17.jpg){#fig:017 width="70%"}

## Выводы

Приобрела практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для
дальнейшей работы сервисов.
