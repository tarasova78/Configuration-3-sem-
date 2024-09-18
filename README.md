![Screenshot_20](https://github.com/user-attachments/assets/94754efb-aa76-43e0-bfb8-df6ee034fb47)
![Screenshot_19](https://github.com/user-attachments/assets/263ba09c-c1d8-4a38-8cbb-d7b8143d3afd)
# Configuration 3 sem
Конфигурационное управление (3 семестр)
Преподаватель: Мирзоян Дмитрий Ильич

# Практическая работа №1
## Задача 1 : Вывести отсортированный в алфавитном порядке список имен пользователей в файле passwd (вам понадобится grep).


![2](https://github.com/user-attachments/assets/364676df-8400-439c-8253-71723efa5ced)


## Задача 2 : Вывести данные /etc/protocols в отформатированном и отсортированном порядке для 5 наибольших портов, как показано в примере ниже:


```
[root@localhost etc]# cat /etc/protocols ...
142 rohc
141 wesp
140 shim6
139 hip
138 manet
```
![3](https://github.com/user-attachments/assets/13e6b338-b240-4d84-9a26-0aa3958d8f42)


## Задача 3 : Написать программу banner средствами bash для вывода текстов, как в следующем примере (размер баннера должен меняться!):



```
[root@localhost ~]# ./banner "Hello from RTU MIREA!"
+-----------------------+
| Hello from RTU MIREA! |
+-----------------------+
```

![Screenshot_18](https://github.com/user-attachments/assets/a4154bd6-2c88-4b96-aacf-eecb3e56e8a7)


## Задача 4

Написать программу для вывода всех идентификаторов (по правилам C/C++ или Java) в файле (без повторений).

Пример для hello.c:

```
h hello include int main n printf return stdio void world
```

![Screenshot_19](https://github.com/user-attachments/assets/4a7f3243-80f1-4110-9790-f70993369409)

![Screenshot_20](https://github.com/user-attachments/assets/a04f2dd3-ef4f-4382-9c6b-4b44fded886b)


## Задача 5

Написать программу для регистрации пользовательской команды (правильные права доступа и копирование в /usr/local/bin).

Например, пусть программа называется reg:

```
./reg banner
```

В результате для banner задаются правильные права доступа и сам banner копируется в /usr/local/bin.
