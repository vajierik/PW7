# Запуск

## Клонировать репозиторий

git clone git@github.com:SkillfactoryCoding/DEVOPS-praktikum_Docker.git

## Скопировать данные

mkdir -p /srv/app/conf
cp ./web.py /srv/app
cp ./web.conf /srv/app/conf/

## Исправить web.conf, собрать образ и запустить

docker run -d -v /srv/app:/srv/app -p 80:5000 <image_id>

