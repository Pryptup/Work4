# UrFU-AD-in-GameDev-Workshop4
Отчет по лабораторной работе #4 выполнил:
- Лукоянов Владислав Александрович
- НМТ - 232202
  
Отметка о выполнении заданий:

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

## Цель работы
Реализовать и проанализировать работу перцептрона в проекте Unity.
## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления: OR, AND, NAND, XOR и дать комментарии о корректности работы.

Перцептрон научился выполнять вычисления OR в первый раз за 4 эпохи:

![image](https://github.com/user-attachments/assets/b06d173d-9c09-4f87-80c7-88752de339d7)

И в среднем ему требовалось около 4 или 5 эпох.

Для вычисления AND в первый раз понадобилось 6 эпох:

![image](https://github.com/user-attachments/assets/79338247-3a4a-4121-8252-bfaf444e3be1)

В остальные попытки обучение происходило за 5 или 6 эпох, хотя последние тесты показывали 4 эпохи.

Для вычисления NAND в первый раз понадобилось 7 эпох:

![image](https://github.com/user-attachments/assets/78092fc5-4abb-4081-bdfe-c53e7072cfe5)

Но в остальные попытки обучение происходило за 5 или 6 эпох, также, как и для AND, лишь иногда колличество эпох достигало 7 - 8.

Для вычисления XOR реализованный перцептрон не годится, что соответствует теории, и даже 12 эпох абсолюно не сдвинули процесс 4 ошибки и никакого обучения:

![image](https://github.com/user-attachments/assets/1c4f5edf-b7e6-42a0-96c4-87519ac4953a)

Единствееное, что в первые 2 эпохи перцептрон выдавал 3 ошибки, а потом и вовсе перестал попадать. 

## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.

Графики построены на основе первоначальных проверок, хотя, конечно, в каждую попытку колличество необходимых для обучения эпох и совершаемых в них ошибок отличалось

## Задание 3
###
## Выводы

