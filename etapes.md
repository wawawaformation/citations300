# Les étapes d'initialisation d'un projet
Les commandes à faire sont en commentaire "//"

1. composer init //composer init
1. autoloader //composer dump-autoload
1. installation de var-dumper et phpunit //composer require symfony/var-dumper et composer require phpunit/phpunit 
1. on isole le l'index.php dans un dossier public //créer un dossier public et créer un fichier index.php dedans
1. on crée les dossier App/{Controller, Model, View} 
1. on initailise git // git init
1. on met dans le .gitignore : vendor; composer.lock et les fichiers confidentiels //remplir le .gitignore avec les dossiers qu'on en veut pas push dans le git

