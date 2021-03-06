---
## Front matter
lang: ru-RU
title: Лабораторная работа №6
author: |
	 Алли Мохамед Заян - студент группы НКНбд-01-18
date: 15.03.2021

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

# Модель эпидемии

## Прагматика выполнения

- Понимание принципов построения модели "Эпидемия" и знание соответствующих модельных уравнений позволяет выявить тенденции к росту/падению числа особей, восприимчивых к болезни, инфицированных особей,
а также здоровых особей. 

## Цель выполнения лабораторной работы

- Ознакомление с простейшей моделью Эпидемии  и ее построение с помощью языка программирования Modelica.

## Задачи выолнения работы

- Построить графики изменения числа особей в каждой из трех групп (восприимчивые к болезни (S), заболевшие люди (I), здоровые люди с иммунитетом (R)), если I(0) \leq I* (число инфицированных не превышает критического значения).
- Построить графики изменения числа особей в каждой из трех групп (восприимчивые к болезни (S), заболевшие люди (I), здоровые люди с иммунитетом (R)), если I(0) > I* (число инфицированных выше критического значения).

## Результаты выполнения лабораторной работы

- Ознакомился с простейшей моделью Эпидемии, построив для нее графики изменения числа особей в в каждой из трех групп (восприимчивые к болезни (S), заболевшие люди (I), здоровые люди с иммунитетом (R)) для двух случаев: I(0) \leq I* и I(0) > I*.