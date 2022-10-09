
**Exercice 2 : Prise en main de l’interpréteur de commandes** 
convertisseur : https://www.vertopal.com/en/convert/docx-to-md

Manuel
1.    « Which » a pour rôle de retourner le chemin d’un fichier qui pourrait être exécuté dans l’environnement actuel.
2.    Il s’agit de la commande « man –k option »
3.    Pour quitter le manuel, il faut appuyer sur la touche Q (quit).
4.    La section 6 décrit les jeux et programmes disponibles sur le système.
 
_Navigation dans l’arborescence des fichiers_
1.    Cd /var/log
2.    Cd ..
3.    Cd ..
4.    Cd -
5.  Cd /root, les permissions sont insuffisantes pour y accéder
6. On ne peut pas exécuter directement la commande cd
7.  mkdir Dossier …
8. rm permet de supprimer le fichier mais pas le dossier
9. rmdir permet de supprimer un dossier vide
10. il est impossible de le supprimer puisqu’il n’est pas vide
11. pour supprimer en une seule commande le Dossier2 et son contenu il faut rentrer : 
rm - r Dossier2

_Commandes importantes_
1.  La commande date affiche l’heure et time permet de mesurer le temps d'exécution
2. Ce sont des fichiers cachés
3. Il se situe de /usr/bin/ls
4. Non il n’existe pas une entrée manuel pour cette commande
5. Il s’agit de la commande ls /bin
6. Elle affiche le contenu du dossier précédent
7. Pour voir le chemin complet il s’agit de la commande pwd
8. Écrase le contenu du fichier pour écrire bip
9. Ajoute le mot plop a la suite des mots du fichier
10. La commande affiche toto pendant 10 secondes puis nous permet de retaper des commandes
11. file permet de déterminer le type d’un fichier
12. En modifiant le contenu du fichier texte original, lien_phy change aussi.
Malgré la suppression d’original, lien_phy garde le text qu’original avait précédemment
13. le contenu de lien_sym sera le même que lien_phy malgré les changements. En modifiant le contenu de lien_sym, le contenu de lien_phy sera lui aussi modifié. Ils partagent le même contenu.
14. Interrompre : Ctrl + S, 
      Reprendre : Ctrl + Q
15. 
 
 

16. La commande permet de lire le buffer du noyau de la vm
17. Affiche les identifiants, mot de passe, groupes, mot de passe utilisateur de chacun des dossiers. Il s’agit de man passwd qui affiche la page de manuel de ce fichier
18. trier ordre alphabétique inverse : 

19. la commande est : getent passwd | wc -l.
20. man -k conversion | wc -l : on trouve 141 pages ou conversion est ecrit dedans
21. find -name passwd
22. 
23.  

**Exercice 3 : Prise en main de l’interpréteur de commandes** 

1.
