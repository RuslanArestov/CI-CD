### «Что такое DevOps. СI/СD» - Arestov Ruslan

## Дополнительные материалы для выполнения домашних заданий из блока "Введение в DevOps"


- [Дополнительный материал для занятия "8.2. Что такое DevOps. СI/СD"](CICD/8.2-hw.md)

- [Дополнительный материал для занятия "8.3. GitLab"](https://github.com/netology-code/sdvps-materials/tree/main/gitlab)


### Задание 1
Что нужно сделать:

Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
Установите на машину с jenkins golang.
Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

#### **Решение**

![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/result_assembling.png) \
![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/repository_git.png) \
![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/branch.png) \
![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/shell.png)

### Задание 2
Что нужно сделать:

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

#### **Решение**

![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/script_pipeline.png) \
![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/pipeline.png)

## Задание 3
Что нужно сделать:

Установите на машину Nexus.
Создайте raw-hosted репозиторий.
Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

#### **Решение**

![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/pipe.png)
![alt text](https://github.com/RuslanArestov/CI-CD/tree/main/images/repo.png)