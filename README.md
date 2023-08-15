#Fonte
https://www.youtube.com/watch?v=V-MDfE1I6u0&ab_channel=AlimonPito

#Executar make setup

#Entrar no container
$ docker exec -it laravel-docker bash

#Criar projeto no container
$ composer create-project laravel/laravel .

#Alterar arquivo .env com o nome do banco e senha corretos


#Corrigir erro de permissionamento do arquivo laravel.log

#Try to give permissions to the storage folder.

sudo chmod -R 777 storage

#after that run:

php artisan cache:clear

php artisan config:clear

php artisan config:cache


