# Социальная сеть любителей котов Kittygram
### URL
Проект развернут на сайте:
https://ed-kitty.dynnamn.ru/
### Описание
Интерактивный сайт с личным кабинетом с возможностями публикации 
фотографий котов, а также присваивания достижений.
### Запуск проекта в dev-режиме
- Клонируйте репозиторий и перейдите в него в командной строке:
```
git clone https://github.com/Bem6u/kittygram_final.git
```
```
cd kittygram_final
```
- Запустите проект с помощью команды:
```
docker compose up -d
```
- Соберите статику Django с помощью команды:
```
docker compose exec backend python manage.py collectstatic
```
- По адресу http://127.0.0.1:9000/ сайт будет доступен.

### Автор
"Эдуард Насыров" (https://github.com/Bem6u)