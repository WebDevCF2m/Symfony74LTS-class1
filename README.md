# Symfony74LTS

## stack actuelle

Windows 11 | WSL 2 | Ubuntu | PHP 8.5 | Symfony 7.4 LTS webapp

### Installation

        wsl
        cd /home/formaweb
        symfony new Symfony74LTS --version=lts --webapp
        cd Symfony74LT

### Chemin

        /home/formaweb/Symfony74LTS # Linux
        //wsl.localhost/Ubuntu/home/formaweb/Symfony74LTS # réseau Windows

### Lancement du serveur

    symfony serve -d

    # fermeture
    symfony server:stop

    