# Symfony74LTS

## stack actuelle

Windows 11 | WSL 2 | Ubuntu | PHP 8.5 | Symfony 7.4 LTS webapp

### Installation

        wsl
        cd /home/formaweb
        symfony new Symfony74LTS --version=lts --webapp
        cd Symfony74LT

### Chemin

        /home/formaweb/Symfony74LTS # Linux WSL
        //wsl.localhost/Ubuntu/home/formaweb/Symfony74LTS # réseau Windows

### Lancement du serveur (WSL)

    symfony serve -d

    # fermeture
    symfony server:stop

### Vérification de la sécurité de l'installation

    symfony check:security

### Vérification des commandes

    php bin/console

### Création du premier Controller

    php bin/console make:controller
        > PublicController
        > no (PHPUnit)
    created: src/Controller/PublicController.php
    created: templates/public/index.html.twig

           
    Success! 