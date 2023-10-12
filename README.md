# MAJDAE2WEBSRV31
Description de la mise à jour du programme dae2 via git sur websrv31

## Se connecter sur websrv31

```bash
$ ssh websrv31
```
Vérifier le mot de passe dans Keepass

### Aller dans le répertoire 

```bash
$ cd ~/fabrice/dae2
```

### Taper make pour faire apparaître le menu

```bash
$ make php.bash
```
Voici la copie d'éecran :

```bash
gestion@websrv31:~/fabrice/dae2$ make php.bash
 🐚 php › 
    docker exec -it --user cakephp 6d3c9d5c5aec87cad32bc04cdcb3f5be6059e30c4a2f7c8d52db0fcc63b0866c bash -l 
cakephp@6d3c9d5c5aec:/var/www/html$ 
```

```bash
cakephp@6d3c9d5c5aec:/var/www/html$ 
```
- Élimination de modif intempestives sur le répertoire cible
```bash
cakephp@6d3c9d5c5aec:/var/www/html$ git checkout .
```
- Tirer la nouvelle veresion depuis Github
```bash
cakephp@6d3c9d5c5aec:/var/www/html$ git pull
```

