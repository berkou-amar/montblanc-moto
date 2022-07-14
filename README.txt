config de git de manier globale
$ git config --global user.name "berkou-amar"
ajout du compt mail de manier global aussi
$ git --global user.email "berkou.amar@gmail.com"
controler la bonne exucution de la config
$ git --global --list
la commande 'git status' verifie les fichier non sauvgarder ou non traquer dans la zone d'attante 
$ git status
pour ajouter les fichier un a un il faut faire 'git add nom du fichier'
$ git add index.html 
git add . signfie ajouter tout les dossier 
$ git add .
et pour enlever un dossier en particulier de la zone d'attente il faut executer la commande 'git reset'
$ git reset index.html
le commit avec la commande 'git commit -m "" ' en sauvgarde les donner sur un depot locale 
$ git commit -m"le titre ou le nom du commit ou de la version ou du dossier " 