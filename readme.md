Задание:
Сделать блог на ларавель

Технологии:
Html,css , bootstrap,laravel, php, vanila js(если надо)

Требования:
Фронт:
Список всех блогов ,в каждой карточке картинка, краткое описание кто создал . Простенькая верстка с использованием бустрап .

Админка:
Ларавель дефолтная авторизация,в админке CRUD по блогам, тоже простенькая верстка

Так же сделать сиды по юзерам и блогам для теста

=================================

Создать базу данных blog в phpmyadmin по адрессу
````
http://localhost:8080
````
нужно выполнить
````
composer install
````

или если используется linux в качестве хоста, в корневой папке проекта 

````
make composer-update
````

Команда для быстрого применения миграций вместе с сидом
````
php artisan migrate:fresh --seed
````

Пароль для пользователей: password