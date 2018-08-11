## LARABLOCK ##
 
### Installation ###
 
Ajoutez le block Clients à votre fichier `composer.json`
```
    require : {
        "laravel/framework": "5.1.*",
        "larablock/clients": "dev-master"
    }
```
 
Lancez la mise à jour de Composer :
```
    composer update
```
 
Ajoutez le Provider à votre fichier `config/app.php` :
```
    'Larablock\Clients\LarablockClientsServiceProvider',
```
 
### Publish ###
 
Publiez le module pour récupérer l'ensemble des vues
```
    php artisan vendor:publish
```
 
### Félicitation ! ###