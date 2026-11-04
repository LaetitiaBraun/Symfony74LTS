# Symfony74LTS

## Stack actuelle

Windows 11 | WSL 2 | Ubuntu | PHP 8.5 | Symfony 7.4 LTS webapp

### Installation

        wsl
        cd /home/webdev
        symfony new Symfony74LTS --version=lts --webapp
        cd Symfony74LTS

### Chemin

        /home/webdev/Symfony74LTS # Linux
        Symfony74LTS # réseau Windows

### Lancement du serveur

    symfony serve -d

    # fermeture
    symfony server:stop