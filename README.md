# Projet_collaboration
Boris FYOT / Henry LECHINE

Etapes du raisonnement :
Il faut créer un projet A, le mettre dans un repository Artifactory
Il faut ensuite créer un projet B utilisant dans ses dépendances le projet A pris depuis le repository distant, et le mettre dans un autre repository Artifactory

Sous étapes :
Modification de l'environnement pour permettre la connexion entre les deux machines
Création de deux repositories projet A et projet B sur une même adresse
Création d'un utilisateur usera ayant les droits de lecture, deploy et annotation sur le repository projet A
Création d'un utilisateur userb ayant les droits de lecture, deploy et annotation sur le repository projet B ains que les droits de lecture sur le repository projet A
Deploy du projet A sur le repository projet A
Ajout de projet A en dépendances du projet B
Deploy du projet B sur le repository projet B
