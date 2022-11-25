POur afficher la console git
1- Sélectionner le dossier principal de votre TP avec "touche droit souris"
2- Sélectionner "Ouvrir dans le terminal intégré"
3- Créer un dépôt avec la commande "git init"
4- Dans l'explorateur pour voir le dossier .git,
qu'on appelle le "dépôt",
il faut sélectionner affichage/éléments masqués
Si la commande git n'est pas reconnue, il faut installer git
Chercher "git download" dans google pour trouver :
https://git-scm.com/download/win
Télécharger la version Windows 64-bit
Lancer l'installateur qui se trouve dans le dossier téléchargement
Fermer Visual Studio Code pour le relancer
ce qui permettra à Visual Studio Code d'accepter Git
pour voir l'état de votre version
"git status"
Si les fichiers apparaissent en rouge,
il faut les indexer
"git add --all"
en de nouveau git status vous constaterez que les fichiers sont verts
Une fois que tous les fichiers modifiés passent au verts
on peut faire un commit
"git commit -m "s13 Début du TP2" "
Pour créer un compte "Github"
https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account
Créer un dépôt dans votre compte Github
Il faut d'abord sélectionner "repository"
Cliquer sur "New"
Entrer le nom du "repository" en français nom du "dépôt"
On veut créer le nom le plus simple possible ex: "1w1"
On sélectionne pour l'instant un dépôt "Public" à partir du radio bouton
On sauvegarde le dépôt

Vous revenez à votre terminal "visual code" et entrez les commandes suivantes
changer le nom de la branche principale: "git branch -m main"
Créer un alias pour l'adresse du serveur distant "github"
"git remote add 1w1 https://github.com/RoronoaEnnyl/1W1---TP2.git"
Pour vérifier que l'alias a été bien créé
"git remote -v"
pour créer un readme.md
https://markdown-editor.github.io/