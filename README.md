# InstallFest de THP

Salut! Ici il s'agit d'un reposotorie qui te permettra de faire tout l'InstallFest de demarrage de la formation **The Hacking Project**. 
Ceci est une solution pour tout les flegmards qui ont du les refaires 10 fois.
Se qu'il va t'installer: 

 - Les Librairies necéssaires au bon déroulement de la formation. 
 - Git
 - Rvm : gestionnaire des versions de ruby
 - Rails
 - Mise en place de GitHub
 - Branchement de ton git  à Heroku 

## Prérequis minimum

Une version de Ubuntu supérieur à 16.04

## Comment faire ?

Voici les lignes a rentrer dans ton shell pour lancer l'installation:

    git clone https://github.com/BarbaraC12/installfest_thp.git InstallFest
 
Modifie InstallFest1 dans l'editeur de texte les ligne 15 et 16 ("TonUserName" "TonAdresse@Email.yo") par tes informations personnels et de préference les même que sur Github

    cd InstallFest
    bash InstallFest1
Il te demandera régulierement des validation accepte les toutes.
Ensuite fait un : 

	cat ~/.ssh/id_rsa.pub
Tu obtiendra alors une clé  **SSH Public** , copie cette fameuse clé. Il faudra que tu te rende dans ton github dans la rubrique **Paramètre de compte** puis l'onglet **clé SSH et GPG** pour l'enregistrer.

Tu peux alors passer à la suite de l'installation . Pour heroku si tu n'as pas de compte utilise la même adresse mail que sur GitHub.

    bash InstallFest2
Et voila installation terminé.

## Vérification:

Pour vérifier si tout c'est déroulé comme prévus:

    bash InstallVerif
Les versions installer doivent être:

 - Ruby 2.5.1
 - Rails 5.2.3

Création le 09.04.20 par Barbara Cano
