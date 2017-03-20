# caramonis
Projet Hackathon Adonis / Simplon
Affichage dynamique / slideshow.
Contexte :
Le groupe Adonis souhaite déployer dans ses écoles des téléviseurs d’information.
S’agissant d’un circuit d’information interne d’information dont nous avons la maitrise matérièle
comme logicielle, quelques règles de bonnes pratiques peuvent ne pas être appliquées :
-
-
-
Tout doit être prévu pour une résolution d’écran Full HD, navigateur en mode plein écran.
Oubliez le responsive !
Un seul navigateur cible : Chrome pour Windows.
Pas d’interaction utilisateur, réseau privé => la sécurité n’est pas prioritaire.
Vous avez des pages web (modules) qui doivent s’enchainer suivant une programmation
paramétrable.
Informations générales :
-
-
-
-
-
-
Un serveur puissant vous est exclusivement dédié. (6 cœurs, 16 Mo de ram)
Vous disposez desssus d’un serveur web (apache), PHP7, Mysql
Adresse de PHP myadmin : http://hackathon.groupe-adonis.fr/phpmyadmin/
Récupérez les codes de la base dans le fichier connexionBase.php
Si vous devez créer une table, préfixez là avec simplon_n°équipe_
Vous êtes responsable de vos propres dossiers. Gardez toujours une copie en local !
Concernant l’utilisation de Framework, librairies ou autre :
-
-
Priorité au code fait à la main mais vous pouvez utiliser Jquery/Boostrap.
L’utilisation de bouts de scripts trouvés sur le net et qui simplifient la vie (vérifiez les
licences) sont vivement recommandés ! (Gestion de RSS par exemple). Ne recodez pas ce qui
a déjà été surement mieux codé que ce que vous pourriez faire !


Modules :
Module 1 : Afficher la météo du centre du jour !
Tables concernées : centre.
Module 2 : Anniversaire d’un prof !
On est gentils, on n’affiche pas l’année de naissance !
Tables concernées : Prof, Lien_F_Cen, adonis_tl
Module 3 : Blogs !
Notre site principal dispose d’un flux RSS :
http://www.groupe-adonis.fr/blog/feed
Indices/pistes : RSS pour récupérer les url des 3 derniers articles.
« Extraire des informations du DOM en php » buzut
Module 4 : Emplois du temps :
Affichage des 3 prochains jours dans la limite de 60 « évènements ».
Informations minimales requises :
Jour, début, fin, « groupe », formateur, salle.
Tables concernées : Profs, Lien_F_Cen, adonis_tl, locaux
