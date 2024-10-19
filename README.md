# Projet Cherry Pick
# Utilisation de `git cherry-pick`

La commande `git cherry-pick` permet de sélectionner un ou plusieurs commits d'une branche et de les appliquer à une autre branche. Cela est utile pour transférer des modifications spécifiques sans fusionner l'ensemble de la branche source.

Ce qu'a fait la commande dans notre projet :
Nous avons utilisé la commande `git cherry-pick <commit_hash>` pour appliquer les modifications de fichier3.txt à notre branche ajout-contenu. Cela nous a permis d'intégrer uniquement ce commit spécifique sans prendre tout le reste de la branche, ce qui a gardé notre historique de commits propre et évité des conflits inutiles.
