#Simple Web APP (Nginx + Python)

# Архитектура
'User' -> 'Nginx (Port 80)' -> 'Docker Network' -> 'Python Backend (Port 80)'

#Подробнаая инструкция по запуску
Подтягиваем директорию github со всем содержимым
git clone https://github.com/STT8/BaseWeb
Далее необходимо собрать docker image и запустить контейнеры
docker-compose up -d --build

