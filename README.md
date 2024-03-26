# Домашнее задание к занятию 8.02 "`Что такое DevOps. СI/СD`" - `Кримчук Георгий`
### Инструкция по выполнению домашнего задания

  
### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### ОТВЕТ:

![Скриншот-1](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_1.png)
![Скриншот-2](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_2.png)
![Скриншот-3](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_3.png)
---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### ОТВЕТ:

![Скриншот-4](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_4.png)
![Скриншот-5](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_5.png)
![Скриншот-6](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_6.png)

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### ОТВЕТ:

![Скриншот-7](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_7.png)
![Скриншот-8](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_8.png)
![Скриншот-9](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_9.png)
![Скриншот-10](https://github.com/George210890/-DevOps.-I-D-/blob/main/8.02_10.png)
