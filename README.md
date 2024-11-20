# Projet GIT
Ce projet nous a permis d'apprendre et de métriser les bases de GIT. Nous devions créer un mini projet permettant de montrer l'utilité de GIT lors de travaux collectifs.
Ici, nous avons pris l'exemple d'un travail de groupe pour créer un site web en PHP (pas fonctionnel, juste pour montrer). Chaque membre du groupe possède sa propre branche sur laquelle il peut créer ses dossiers/fichiers, qui sont ensuite "merge" sur la branche principale (main). Le seul fichier commun aux membres est "tâches.txt" permettant de lister leurs tâches, et lorsqu'on le "merge" à la branche principale, il est complété avec les versions de chaque membre, créant ainsi un fichier commun où l'on peut aussi voir l'avancée des autres membres.

Commandes principales utilisées : 
- git branch nom_branche
- git branch -av
- git checkout nom_branche
- git status
- git add .
- git commit -m "nom_du_commit"
- git push origin nom_branche
