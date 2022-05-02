# Commandes : 

## Prérequis : 
Installer Composer associé à la version php la plus récente, compatible au fichier.
Laravel associé à la bonne version php


## Créer vendor  : 
```
composer install
```
## Créer .env : 

```
cp .env/example .env
php artisan key:generate
```

## Récupérer Base de données :

# Commandes installation jetstream : 

```
composer require laravel/jetstream

php artisan jetstream:install livewire
php artisan jetstream:install livewire --teams

npm install
npm run dev
php artisan migrate

```
## Si Erreur : Vérifier + créer la base de données avec le bon DB NAME
Modifier le fichier .env pour correspondre à la base de données et à l'HOST

commande : 
```
php artisan migrate 
```
