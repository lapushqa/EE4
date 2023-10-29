Задание:

Как системному администратору данной организации вам поставлена задача собрать на докер образ Django
(Linux, nginx, Django, Postgres, Gunicorn) сервера. Все нужные сервисы должны быть проброшены на хост по стандартным
портам, реализация HTTPS не требуется, версии Django, nginx и Postgres не имеют значения, как и версия ядра Linux.
В проекте просто должна работать админка с заранее прописанным логином и паролем.

#### Установка docker:

Для Linux систем:  
`curl -fsSL https://get.docker.com/ | sh` //Установка Docker  
Для Windows или Macos:  
`https://www.docker.com/` //Установка Docker Desktop

#### Запуск приложения:

После установки docker, загружаем проект на git

В командной строке, переходим в директорию проекта и набираем:  
`sudo docker-compose up -d` //В среде lunix
`docker-compose up -d` //Docker Desktop (Windows или Macos)

## Данные для входа:

логин: admin  
пароль: admin
