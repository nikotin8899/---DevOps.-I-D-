# Никита Демин - Что такое DevOps. СI/СD


# Задание 1


Что нужно сделать:



Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.


Установите на машину с jenkins golang.


Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.


Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..


В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/b2ddbad0-8f55-4519-b519-030b3c13a111)

![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/0e124182-8514-4a2a-a811-7946e7a56e53)

# Задание 2


Что нужно сделать:



Создайте новый проект pipeline.


Перепишите сборку из задания 1 на declarative в виде кода.


В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.



![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/f3de39ca-44a1-457e-8e6e-7a76230279fd)


![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/8c89d068-dbf9-4604-9103-1119ebbc3861)


# Задание 3


Что нужно сделать:



Установите на машину Nexus.


Создайте raw-hosted репозиторий.


Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.


Загрузите файл в репозиторий с помощью jenkins.


В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/cce83a98-555a-4a5b-ad29-cfe32312d9c1)

![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/1fc3441f-8f39-4308-835a-71c00640003e)

![image](https://github.com/nikotin8899/---DevOps.-I-D-/assets/56605975/8ec1735e-b919-4197-af88-1173cef9daf4)
