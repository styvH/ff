## Commandes : 

# Prérequis : 
Installer Composer associé à la version php la plus récente, compatible au fichier.
Laravel associé à la bonne version php


# Créer vendor  : 
```
composer install
```
# Créer .env : 

```
cp .env/example .env <br>
php artisan key:generate
```

# Récupérer Base de données :

## Commandes installation jetstream : 

```
composer require laravel/jetstream <br>

php artisan jetstream:install livewire <br>
php artisan jetstream:install livewire --teams <br>

npm install <br>
npm run dev <br>
php artisan migrate <br>

```
# Si erreur : Vérifier + créer la base de données avec le bon nom
Modifier le fichier .env pour correspondre à la base de données et à l'HOST <br>

commande : 
```
php artisan migrate 
```
